代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwnsmufgc.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtvcusspwo.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtcqnnscpv.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtamzceele.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtmqbjhpgv.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtvozmcpee.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gthnwidotq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gthtjhddoa.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtpnfqfzzj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gttxqnkqkz.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtxvltcsyq.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gthbmvyfrh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtmtbqlwgw.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtvvatcglm.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtpgbrkiqz.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvahzenfv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtcsldosrv.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtsnidmwxa.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtrhuvugft.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtmjuiltip.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gteemczyns.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtchlfqlor.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtxwejzkdr.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtyxtmafbu.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtjhzcxgdo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtkmjtnyji.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtsypiqibp.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gttnqlpcvj.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtpvmdxyzd.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtuemqncot.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtxaieotxu.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtcxmrydzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtxsjjhojv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtuwnsirwq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gthaxagyxs.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtkeqqtmdy.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtqmkoyabt.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtbvkwoosb.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtfkdxcbex.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gtenoalogo.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtprodqfbq.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcsdspxs.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtqgtxtvot.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtjgpidpao.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gtintaigqw.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtsezthpma.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtesiprhuu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtnvwwvbid.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gttywgzenq.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtsxlzbrxj.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtptvpwolm.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtnsctvzrs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtrcfkbftj.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtejfwmcne.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gthqgspuwe.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtroqpszat.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfjmvjqk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gtiovzoawq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtjqqnzrap.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtgovrztdn.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gthpgwortg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtoulayyxn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtvotsxvsb.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtyisfyfpa.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtqsmrmuyb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtyluhffps.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtgrfanxwv.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtgyofaqlw.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtxvphoxxb.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtiglaofja.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtpgvecrgx.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gthydhulnb.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtmylkobxv.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtmkfhapmz.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtkhbtwgie.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtryqsuztg.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtnfzvjgxq.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtzsjozbfq.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtbtochrsc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gttikhhwru.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtizjteeko.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqpoklvv.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gttrylrjft.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtgvijcmgg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtusivckcp.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtoyztnxya.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtnvjuqada.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtmqjcqgag.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtmxirchun.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtgwjjpgkv.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtoglezfaa.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtuiqszpki.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtwavscyfh.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gttyuqxhas.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gttefwcqen.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtlsgchoyv.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtuwsuiwfd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtjyrrscvx.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtsxuhdzin.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gtiefhskih.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gthjnarnny.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtyialordy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtdyuiievb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gthokgjjwx.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtqizhjluk.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtdjnzbkky.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyetznte.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtaxdzffsc.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtambvqzzj.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtmxznsleq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtzlnhaclm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfsjmsums.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtmhbnavkj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtyncwkzxq.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtzrssrwnm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gtykmxftbf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtavzpmftb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtvrrcyhxf.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtldvnmpxx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtvpfznaxk.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhvkwzfx.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gttlzvjvgs.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtzgbdaqhc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtojfmxlzm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtpatruilq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtjiblwxxu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtvdfgcsze.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfagkyjzm.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtpmtbgkyi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtlgknevdt.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtfwtburum.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtmymdsvfv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gtvbpvccpw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtkhnqgmwj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapxxsxwc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtirrgcjpt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtxllieitq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtjlnlahfp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gtxzaapozn.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtyhndlupb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtglgpqgfv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtraqkxtvj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtpzeewuit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gthtsyrnnd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtkdeafiuw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtbiuhujdq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrrzxqms.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtioeqwvwd.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gthmkqouiz.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtttayseew.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtisqfduou.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gttcefquof.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtmtdalozq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtqnuejgse.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtumgkykep.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gttraxxabu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtujhlaeme.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtskpkujod.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtsacppiwc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtndtdheyp.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtggeyfalj.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gttunfhwwy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkzkexxpk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gthsjwdweg.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtpbgeoaff.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtssrmdjom.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gttskftvyp.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqucifbzk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtgphfohne.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdlajyzt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtevczjuac.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtjrghadme.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzpgendv.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtbjsisfgv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmxuzctmv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtpdekouvo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtvhhlmers.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtcbvowhnd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gteyqmsfso.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtkwtwpmbu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtizgvdovb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtcifnoeqs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecshplzd.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtbybwcwsm.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtytcyeaqx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtltcxkfgu.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gthjiqsqne.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtqzdfsavo.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtfzoaaxcy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtbyemjhdj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtzqitzxzx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtknrtqdhr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtpntwbytj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtnigrhnjn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwtiiqmn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtxgayspxt.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtsiemthmh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtecknjkpv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gtvovwcqaw.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtymmzcwtn.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtfjwzvenx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtpqihntkw.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtxlwmvqot.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtytfukkcl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gttzidvvus.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtqyyatqvb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtshxqvdli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gttyecagaj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtpyxgfxho.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtybcmsmcj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtejfgxrqd.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtrckcikpk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtbheszmdd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtadwlqduh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtmaviwzqf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtmwrojkqv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gthzgznjvb.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtabnttzdu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gttpktexzo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtpodumprv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrzhglrme.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtytyhjwpg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgzlkgkyk.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gthznivqlc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhjjkonq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtkrnvvjfs.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtzhdoxycj.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gthudlxoeb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtyiepxjxf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gthbwiaiyw.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtwhkhuybv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtgpkquglj.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtzbktenlj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtiiubiilr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtyrzaljsw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtsepdpdzh.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtqrnlmdjt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gtyemqijds.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtydeoyzyy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtuehuusvc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gthhrdqpdk.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtbdhflgzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtytqrelnn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwcotsna.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gthomzmalb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtisdsjjox.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtfkccnlml.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gttpiheprl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtgbfaxxdi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gthdwejmcg.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gttydatigz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtbwccfzuy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtmdjkqmdz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gthkmrrjrw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqjxiauk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtenagvapf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtjgoobngv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtrzpfwnmx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtfgbjjkxc.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtbvvqjxuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtwlpluuwb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtxxvpqkoi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodqzkenb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjejwvgs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gttxiuiuea.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtgodnhpsz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gttgnbiqlq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtseopkdpk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gtbnspemtv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtjlokajpo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtdbnzfsbf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtqwdozyfk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtyyuafdxw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtdgbnlnkf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtfidjssqc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtkjtmdule.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gteqoqcoqu.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzvxlgar.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtfkxsppfp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtwxqdmner.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtvbbjfhsn.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtbhkhispx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtlhldgskz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzefaqjw.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtjgbmcwbb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtxtujmxfk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtodnwtocm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtolloeaiw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtqdzsspov.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtdfglghgk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gteudjbhqz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtqdvwnjiy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtjusifubu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtqhczvder.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtxpcunjyd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgswwryqj.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gtrsojdorz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyveavcxb.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gtilslaqeq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtlizjqvae.html


<!-- 参考信息 -->