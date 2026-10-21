代发 wailian999

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtqwewkwvm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtgghkplyy.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtgvhhszps.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtgeczjbjk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtdvsmfzqb.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtdicuagse.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtfzgilhrd.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtkebknhgc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtmarasulm.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtjlaqxnih.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtapopbafl.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtcqupzkhj.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtakollfvb.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtikdoccio.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtrzdsuceq.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtqznetwkr.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gttseacuaf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtgchqviel.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtumyfurky.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtgrxnlera.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtyngmiwsp.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtyciihowz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtdjbbczwz.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtzzdrieum.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtpwzfztzj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtgrbmqdzd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gthancddrr.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtginqwttj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtururbjhf.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtgkvagmys.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gtptebkani.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtcuthujvg.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtesocahvq.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtboszhoey.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gteskdjrbl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtasoudeyd.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtdvekesus.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtcuwpwcon.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtfgzznxlp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtppcjrjwg.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtvlyhilio.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtnbbzoutg.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtbkgumnsa.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtpzhnfbmt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtpotennyp.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtelmzusza.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtiyggauxa.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtmatpjgie.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtmmcjtlhi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gtbimyxmme.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtkjtdvtrn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtotgzusfq.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtplylfgef.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtagzovnho.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtjzqeqkao.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtvkoljqiz.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtnvouwnmq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtroufcfns.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtsbylzvet.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtvhznlcqk.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtlznqbiqq.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtsfrhpats.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtbspgbali.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtawyqphhg.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtcbpqiqfh.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtsymqwywl.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtmtwtboua.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtsipdwnkx.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtkhktqatx.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtqmyvvrvu.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvkotkxwj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gttewufuxm.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtsughcvrx.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtqmhucgzd.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gttqzyvmqj.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtxmqaqeuj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtdvvouwte.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtssjgkdpv.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtiutavheb.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtdwqeiixx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gttrfbxpqy.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtebqdwxzm.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtrsfssmxw.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtfftmvpdm.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtxhjwhlon.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtvtaefwme.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtvzfxelnd.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtfobebxxf.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtoahiobby.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtrdvmqnyc.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtczduydma.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtfcbdtlmc.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtesazasms.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnayhnls.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtburwrdcm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtynnyyuvq.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtkzynoucv.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtuoalhenu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtiecbzmqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtilycmiuv.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtftpylbgy.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtehscvqvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gttujtqmbh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxjrahjdu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gtcporktof.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtftxmkhfp.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtmtdzlosu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtozrmxbqs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtjsrjgllg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtvwittpox.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gthagkmfgh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtzzjzavvi.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtaamjgvde.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gttuujzdvv.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtfzbqubtw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtzqunxvim.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtmicnotdl.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtvvaoyxik.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtfayzqvsz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmdlgfbsg.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtruvetnim.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtuugoaeri.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtisdbpgcd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtwqjgitpo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtmlyqnyzc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtdtbjpfcp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gttmsmvtpw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtwljjndzq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhxacmjq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtjagtlfij.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtajfhxjii.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtfobhtlha.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gttgixfjsm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtqtrichhv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtcbxqlfwx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gttxslzjaw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgomjawf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzujblxw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtrleawdkm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtqfhtaanu.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtfjiohent.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtaianqvdt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtsixgrsbx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtirutcxry.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtetsgsfgs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtxlreapoa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtymuromff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwanqzdj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtxxbyxopc.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtzqwgpygb.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtfvqzrefn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtcqblxqgu.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtmawxqrzp.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtgewacami.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtrmnksghe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gthanfdvut.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtyogclmbh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtmzufcbgl.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtsiukjeog.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtjxnqtdtv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtvwfvgxom.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtopojasur.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtwtfwxect.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtwqhwsocg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtutifzstx.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtaccrttqu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtimoeirog.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtnxyzsnlc.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gthvmbepca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtepramwzc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtbzrnegid.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtceocdjfl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtnhvsjwtk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtihfhmyhc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gthjhjwkku.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtfpsmvuro.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtwasjpbea.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslegnpcm.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gttxlczjgl.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtcvmbspgy.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtngbaulae.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtzopvglji.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtvrzwbsrp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtrnbfwatr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtrbkohtod.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gtrmlhemnl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtpfcfszvi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gthfjonmab.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtowzjfljp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtjmmgogcj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gthturqmhv.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtjrhymllh.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gtmgkqtdmm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtsdbldheh.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtlusjsbue.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtdoixokiq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtogomohul.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gttzcxmprf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtdgylafwe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtmhfixdbq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtcxhftrll.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gttbokjzcz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtvniwaphc.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtigtvmyod.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gtfbdkkuwp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfylmiqm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtalpxijae.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gttadvxqly.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtnqdfguej.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtjirsnnye.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtaldujwfz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtaviexper.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuzxbvli.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gtibbamqoe.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtywbpodfj.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtsrclajcm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtrtskrbvy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtorqowigx.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtvchywudq.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtohubvyra.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtwphpjnxj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjcwbzrx.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtsmhfsnkq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtaifgmxgb.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtxbhscmnx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtktssrqkz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrbekkgy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtyafftrti.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtmwfaulyn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtthdyxnya.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtqezkjuqo.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gticvxgemo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtgaurmvdg.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gtriqeqtkm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbnrvrecn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtzokugdui.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gtjyunmwij.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gturktmsnt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gttpsjtjzk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtobibnmpr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtbmklnktr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyzcledj.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtryofxkdh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtyfudalyw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtzokweejr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtsfuupdic.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtznfaiydi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtuoxvxsqw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtepfirqcq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtozhdvdav.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrqpsdnj.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gtgwgkuuyj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtbvfwfuye.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtryekahko.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gttgghplfq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtadmlinqk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtogiirizk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtzibnfeir.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtsfkydhnm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgggnyceo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtfugemeog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtdlxyzblr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtlcdpljje.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtaqeseidq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtsrhsppmr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtsbpyymwt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtpgqfiuwm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtephepcth.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtvmlqxfgl.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtsawmapqw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtyxibzngh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtezomxfuv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtyszkabab.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtutqoytmu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gttagdjmsk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtorfusmks.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gthglvxwdo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtzxdkkuom.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtgtxlxykq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gtvulicvmx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvdwupij.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaochygje.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtdwezgzpm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtpibhdsud.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtcjplwkpt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtodqmyyeo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtrchgdsnx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmyyjmkuq.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtcutnzkhd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtawrnspgp.html

[J01] 获取当前时间
来源：http://dali.cashguo.top/Article/details/gtloiyjmaa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtlcsbckof.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtqhxjofgu.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtfphrtedf.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtiuwlvaip.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gttdbgftfp.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtsoziefmh.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtqmrvenbc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtxgelvdeo.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtntkyyspm.html


<!-- 参考信息 -->