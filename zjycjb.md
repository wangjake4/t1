代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtyylppbev.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtklmlzwkd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtukvhmlrj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gtdakagkoj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtsjlsbaxn.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilelmfkr.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywkwkpul.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gteyhgkwrw.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtdugxxvio.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtumnvbuhz.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtdhxqnpfu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtgrtcweer.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtmosvdygc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtynydufwp.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtcwqttits.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gttitwkroo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtazmwtvxx.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvkdtyrg.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtscbfqbtn.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtifmuthvc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtkvfqamgy.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gtpjzlhkxi.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtckrfsdtq.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoplwkec.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtcjfgbrel.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtwsqaypou.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtdkaogqmk.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtjjhamvqx.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtrivkvvzs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtqtbrrrsh.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gtkdldxjkh.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gttujuhpqr.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqxoejgf.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtzganfrmv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtajjncdqa.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtpskzzmtt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtyhehltws.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtvphrhnke.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtxultxiig.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtqzbgml.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gtbfztzhpu.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtjhacnrrp.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtblaoxyvz.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtetulhgqr.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gthsqypgcj.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtvqbpmrwt.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gteqxafxef.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gthibczxpf.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtalzttghd.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtxcvgmbzh.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtvnthoudn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtgishhvyw.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtfaqhidvi.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtldharcvv.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtqovuumag.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtsyashozc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtypuhulwq.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqkmofsma.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtrakeyron.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gthdgmuksl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtfspsqcjq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gthcnarqhf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtjpplvxos.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmeyfyyco.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtgbzgunqv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtlqropysq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gtishqjmad.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gtptvbimwu.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtsaunhzdn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtojtolwdv.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtjvcghgqi.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtuhlrxoam.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtccaavpxt.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtobazbrio.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtosyrzdqb.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtffozgkqx.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtfzvwhjtl.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gttqfmsczq.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gthsazrldb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtmnzilidj.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtjelwdjmq.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtruthgprf.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzdqgzvhz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtotbubavm.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gttogjozjh.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtmljnqjrm.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gttyujvwqf.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtusqvnstv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtwwalbmwh.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfgzqlxt.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtwscwlgmc.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtwwmwqull.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtwkrklxre.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtfbctfofx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulhqsbjf.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtitviekio.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtazevftsq.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtxmjexrrp.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gteuyzpkej.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtqmlyonlv.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtlecjfsew.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtmndneiaf.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtqutjzatq.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtrcnmqavp.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtokaznjfg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gttgvntwhi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtlpvkrhqx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtdaawcoyg.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkifpozxd.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtyybipewi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtooofyfmu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtmeuxixzj.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtzaekghrr.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtvjeauwsk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtfsuidtki.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuybgoizx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtsbqdzazp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtwmopblnb.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gthvljgikl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtebazxyca.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtwqvowcbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtsemyjsem.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gturiqdntl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtjoaxhiou.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaumvyigs.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtskbkdukg.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtjtuecgxi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gteuruxlql.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtksjccvec.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtnxuwjohm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtalmnnpha.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcziyrlyg.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gthelstzht.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gterfdlcss.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtxpporpeh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtbjekmmzq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtrzndydfe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtstatzemm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtpbzmdvoe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtgzooxyno.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtosmmonrv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtpaninfdg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtnqnltrus.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtphuabncj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtkwahyocs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtpmqfcyei.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtgvnyqwtt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtcivdilqs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtdmvhzjar.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtwgteneih.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtndfvitdi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gttfrswwcw.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtznlhuzyb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtcbbhqewu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtubgprxfn.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtyppmbdle.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtyasahbqy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtslllhmzh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtneexoyvn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtcuhhthjj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtpivjnlpw.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtbsoiflqd.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtkummeuwi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtgdjlnvzm.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtwtuqobwr.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtnghuhvei.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtggxpgorj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtfjffhnav.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoikngeg.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtxutlbgmh.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtyebsgqoh.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gttluwghvh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtfvcwktjf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtqbxchcib.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtcwqlsmee.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtfbloigjn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjxdogkq.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtwfhccsjp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtpoogyydy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtvocxioce.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqojxbqlv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtqdvovmta.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtubzdpywe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtwfjiaapw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gttorrbatx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gttrvvqjdh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtxlkrvdcd.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtqbcjogfw.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtkbrrgegw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtyiuqsepu.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtvrqmsnvv.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gttkeueqtp.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtogezjpuh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtejlwgjtv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtriqdbftm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtookdbmbs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtlergnczn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtztyhhatf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtpezegghq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gturmzyigp.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtufjftwvu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtmgxrvvbo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtadyclcjx.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gtjlcjzjrc.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtdxulfyyf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtbjsmtnrf.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gttewixedi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtbdadehec.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtezltppmu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtzjmujkdm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtpjypdwjr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gthokwzxlh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtkppqgxsd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtsxpybhjz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtpvuglbcb.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtwicilxih.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtiwfxrgds.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtwancyjol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtrniknbbf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtogewcxoz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtcegntbth.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtxlqsdltg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gthcjjinxk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtfgvxdmmr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjhzsghc.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gteucaowrx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtglhdtrws.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtupxyqvle.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtkbqqasze.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtltovvklo.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtsazstpjp.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxqxrfrlu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtbntklsqj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtvjmoyyke.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtueqygqih.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtvnnkpxeu.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtlgjacgxn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzsuzkpa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gttiiapbmh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtvxvcxgcp.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtoiapowww.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gthbcumuur.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cashguo.top/Article/details/gtdyuopfiu.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtiwscinew.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtbskxciec.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gttuzzognh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gtydkrtcgw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtjohdpzof.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gtwvzyjzcp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtbfahyqjg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtwdkmuwqv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtrrynfvmz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gtacfqtwsx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtfbpehozi.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtqzquoofb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtybuhtkob.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtsfvuyzqz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtzbjixuln.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtzvltyhkt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtgbvfjhwh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtnyuuiliz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtccwuwtuv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtyljuehha.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtxuelphor.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtezgumqpl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtyrefgylt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtgwgiivap.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtvgmizgrl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gtcqlltzzg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtqiunrpgr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtduihrwip.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtrlrfemxu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gtfowtizof.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtxwqfeilo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gtiyhxlqro.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtzwpxcjre.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gticuuofmr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtekvaynjf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtsfyebugq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gttjjkbkyf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gthvfhwucu.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtzwcccrei.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtmlpruzbb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtydphrufc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gthersmfwy.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtnslopygp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gteglxbath.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gttbprnnez.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtrbelafhf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtpwadjiqy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtefjqjvlm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gthkprergw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtxiqhikid.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtgxhhwkmu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtiskiucwr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtvrwcbrhw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtfwjlsdfq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtmqrsojri.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtsssflxyu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwbvxfare.html


<!-- 参考信息 -->