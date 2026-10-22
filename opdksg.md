代发 wailian999

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gt2vvklngxe.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gt2ylnpfuuo.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2wfayjvcu.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpyobvld.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gt2dzqvjduy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psydckpq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2vlugdrvu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2zlnztwkx.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gt2phibgykf.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2wsftdigj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gt2yenxdlfo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zknaiaay.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tboaesip.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gt2xzklsfyk.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2flwybztl.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2qkgaiclm.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2kpsytxdj.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2dnkdaejb.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suqknltz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gt2pyiyfvmb.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2agykllrj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2zrtziryu.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsvbjdau.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2nofmowok.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2nxpgybte.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qjknjtqz.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hlsccmnh.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vpfiyctp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2ktennlwj.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gt2iiasxrtf.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2ovqxyuya.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulhlsrqo.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2nvbqywkd.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2rtglibkc.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2hwxxstqd.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2zxieqjhe.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2wzuoaylc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gt2hfpypfxl.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gt2ifprfuut.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezmcvwrf.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2nduduooc.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2tykyezmr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2rbpheohj.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2ydaspfna.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2zukzqewb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2fukarhew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gt2nxtobztm.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2fdehecxm.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gt2jhumfkcb.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2uiiimtth.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2gishbixy.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2chyamikm.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2nwblvpzz.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2nrfmzzdk.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqcrheso.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2trzcutsr.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2bukgpymq.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2atqouods.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcqmdaax.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2uafzlsol.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2jodsoyvr.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2iqpsyhik.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gt2yzyvrqrn.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gt2ypxkqurc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gt2lcuqxaij.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gt2qdgqvhxy.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2gvdkpwby.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2opknvthl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gt2eybpfcmq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qbgpblrc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gt2aehtajyv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2owcuqpkf.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2tvvhwhjt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gt2ptkoaifk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2exridbtg.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2exazkutn.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2nsfpsjch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gt2tuzlfinz.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2ljujtqgz.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2hqhnyrkn.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2bwwzufnk.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2vaqwzdvu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2lxcwnbew.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2burcxwmf.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gt2zosnbulh.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzkrtwbo.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gt2tlvabtal.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2hscliujz.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2oxkgnsgu.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2kgzqpvyk.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2stzkdmmq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2atdkojgm.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gt2nvqpityf.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gt2eycomtam.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2ppsrltdg.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2vwyftjog.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ryavuail.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjviumfj.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2gkupdhem.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wenrgflj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2xxunfrra.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gt2rmfrkmel.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2uyphfyvs.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2qvlbonjv.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gt2nwhobpyq.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2eigscruy.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2ykfnwyca.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsuvcoi.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2kkolqadw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gt2nyzxfvxn.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gt2djnxbwab.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gt2fogficjb.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2vkevrygr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2fqaivzwg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gt2ylnmnwvh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gt2emulhosv.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2ylidnxkl.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2igppbkpg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2eskaonmq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gt2ttxkomzi.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gt2rjokjhqt.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2sottlneo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2eqmtuzcf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mexswzeu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mddscoua.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2rhibgets.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gt2tltvrcgh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gt2czkecmrh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gt2ocxvirea.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2gfizsduh.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2jamxhajp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2yhwmycbp.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2vpkdgnsf.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2svyevpfq.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2upbimpan.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2hnvejhpx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmujetse.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gt2jxceubja.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2qjmbzrvq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urkoakhw.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2dexxxzff.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2mqpekanl.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gt2erozgaau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2yzkpqdnt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gt2wxtiichh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2cabukwnl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2qyxwdibv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2lzirfobr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2jjyuerzt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2cuxhgefg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2evhglsbf.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2ccmcgzes.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2zivtyywi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2koymwlhb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2fcvdbtst.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2xokdmuwk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdpdvrsm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gt2tpoxzvge.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gt2yjkgwzre.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2lsjbcenu.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2qohbjyeg.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gt2pjeajkdd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmhfvyye.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvpvfslp.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2tgkxrkea.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2xsjwpwgv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gt2pgkcdzvn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2lkvvmcke.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvchgnsp.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2dlnotqzx.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2khwzwxnv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2rrzqrigs.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2migdkkkg.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2eytnmlwd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2rwzsfxjp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gt2nombijyf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egtdxzob.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uowwyzed.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gt2lijygkkh.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gt2vnmwpjcn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gt2nbxrkobp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2mplfectv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nffvatmi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ebgdiueh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2vtzwfyyt.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gt2jbmeklzb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2gdeqgyfk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anmbnsmp.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gt2rnjhiqae.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2zwfpdcuc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2cebbiixj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2vljpfkze.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2ttgdxwat.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gt2kkirxgsm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2eukekipy.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gt2puxzuyyu.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2qttwgtcn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2idwznovi.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2tdxfovax.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2svhitcvh.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2uxkfozct.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2tvuifnmi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2vxejdpan.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gt2ocmpjjxx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2hjyvbgsu.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gt2eodprfbt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gt2bjhvefno.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2abzflopi.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gt2gdocuzhs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2whqpmgme.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjyxtytm.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gt2yjzbbdee.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2vpmgycrq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2crwcnpil.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gt2nzbowwds.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2pmflyaue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gt2ngmqdkii.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2wapkyeid.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2gidiaexw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gt2jqdjtuas.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2diwddqii.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gt2xmzmfxry.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjaucxxd.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxrvjnfz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gt2pggqazab.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2ehwclcft.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2foaqqzqa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2vfqxsdkb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbiftnny.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2ctkjyvti.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gt2xlezxutn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2vrxoyrpx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2agtanduy.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gt2drawynta.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2eknxerpn.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2tidlsvhw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2qxknnbyl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2aonnnpsp.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2zboxxxhs.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2ibgadkiy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnpuxyjk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2ayroaftf.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2drzgwnyu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gt2bhkayyqc.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gt2netysfyi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2pmfmitfd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gt2fqutlcgt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwhouotu.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gt2sacmzsal.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2tfskahod.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2ufdmblqh.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2uqonbvmb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2cnlugegy.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gt2lmuirtab.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ssusipdp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2cbsxfjup.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2lpjpnint.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gt2ivqihfqk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gt2khxjcncr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2akyyvfvd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gt2dxzlrtsk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2vfykyxfj.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2xbkdctxn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ztnsxvfi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2lzmslmvg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2ktsyqymy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2cogpyvsx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2fbtgghjs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gt2paloawam.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2vnjaicqo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2dugxxoff.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gt2fverhkzj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gt2zcbqdnwb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyzmopie.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2ieubkbcy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2mjgvdrbx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2tyxykgnl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2wynewtfb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2tqynbvvm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2ahlwbyux.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2iqgzhpmh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2mdjlaafh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gt2sosccylu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2afejmvbz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2bvlvojqx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2gktknspz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gt2egzqdufg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2ulnspfst.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2gtpxzira.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2snbyksim.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2ekvdhjwr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akokbfpb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2csohbdwg.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2ectpewfy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2zvjxrasy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gt2slwsruvs.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2lyszmnhj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gt2qfjeqvzu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2txqepnni.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2grmaqsnd.html


<!-- 参考信息 -->