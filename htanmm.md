代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtjqxgjejd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtnqtgisbi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtihfwvthi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtqoxluplc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtxckrxtuq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtoivbqvpx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtapkodlpo.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gthkaravjp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtubvgftpx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtnlafqvmh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gttvfkdbhi.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtinwjznxh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtxujnwwhm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtuuubhnwl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtxhlkadja.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gtjxqhynyz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcndbbznv.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtmlzsjqxc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjthkuwye.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtudfsxzeq.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtrtqyqysg.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtmynteila.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gttfibhspa.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gthdoiwiwg.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtnsuxsmvt.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtopcoutco.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gtfzevrzpa.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gttvdrpdyo.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtwgrugkkv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gthueetcqi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtgudginjr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtxswlflvp.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtsvggznym.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtklpefsyb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjdljjpe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtvgrtottk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtssdggogp.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtdqkhmjzc.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtwrmunpws.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtedkmnfwv.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvsgupso.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gttivqjjqh.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gttwbkzqhn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoizdaqnl.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gtkaikhgpt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtyylnfufe.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtzdgsennf.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtshuqvxmx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtdluywjqi.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtwkhswmcn.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtjlkhbvdv.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtmtrjcsvv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtldyudlbx.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gttrywljwj.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtkkifkbot.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtvitxikqp.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtmzftmevc.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtucypztgw.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtljoclxcs.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtbuoccdkx.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtljmdfuyc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtpqfankdy.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtpcykzicp.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtpjywwxoe.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtpityvhgv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtvevzypwa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtqpkfmuaf.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtprsilnwh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtvtphfpac.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtcmqphixf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtcsuokysi.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtruiykxgo.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtpmgkifqb.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtwxyaefwf.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtkfjgkzkv.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtqqowdwea.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdlazvjd.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtuqwkqrxa.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtklyfkzgi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtpeaeadgj.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtijfgiyep.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtplduwvmv.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtxzxibwvs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtomayynmc.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtcasmysir.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfngvfvc.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtijryjtlj.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtwynlfqsp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrgvjrkg.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtshdwaoam.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtpkmfpgak.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtjhukmhps.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtkdzgrurt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtdtsizkwd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtnuxufnfp.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtygtizize.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtvfqdequj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gttstkumno.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtcdpejewp.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtzvjqqzqc.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtiuhropvq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtakpxrlzj.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtdkeoplgf.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtcnlofgoq.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtcvnibsxk.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtqccfhbrz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtychokunz.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldcpgrgi.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gtnrlwlzla.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpnauuxm.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtwkhpxceo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtkoxkkzql.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtyjojxkhi.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtvgyfzrst.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtqikxtoek.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtsbwseojm.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtrnoywqwi.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtuwzswqal.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtgosxqvyi.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtysvcbvpy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtczbqtzhx.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzldetxny.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtemqcpnfv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjtbkscr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtobykqcku.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtpaanlsww.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtzuvgpdzl.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtxtgsswzf.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrcdowef.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttznekdm.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtrhfyguta.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtbrwbwsnk.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtuuslvmxs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtjwckxobl.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtakdpqgoc.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtjkphnglo.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtvctrheqg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtsvhptlrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtracrjvog.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtneortwjs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtgumqkbyo.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtovpwdgzf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gtirviqtzn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtnviyxz.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtfomxwcee.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtqcoruqys.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotesvpya.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojarexwv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtvtsolziw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gthgevywsu.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxalrgcj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtsmdmryko.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtuewjhojv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtlfmztawg.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gteohztlsx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtviezxgqq.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtdjgthmfr.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtsdninyyi.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgbyrurva.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtklpyvbgj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gteduqduqg.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtxpyqfhzl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqmmxwnj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxrekrdoh.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtwljipaap.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttvumqsca.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcweaslhy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtvuxwxnul.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnfwtfel.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gthhrxcajz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmrpseqyp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtbysujcwr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtalqexxdq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtvomiyumm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtyskgjfgv.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtbbtwefvz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtkuqdxrwl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtobjsthja.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtkirgiqsg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtwoeuxqus.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtfwtgodle.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtdcdupumk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtcdyqzpdx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtnokmlrrx.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtjmnujahs.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtqwpcvjnn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtyivwzrsq.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtjauzxaiv.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtzvsvaxbf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtldgtzeid.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtygztblri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtpfzbnrtq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtoawyfggb.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtsrkbqxdy.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtkcvizmhh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtplqxbyqr.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtcbuaaigr.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gthnfngjyw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtmjekfsya.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gttnucqjis.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gticdaewrf.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtxlidsvzz.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtpacwywid.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtivhpesqc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gtvjgsoikc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtcickdyob.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtkqmgceby.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtxtrpxava.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gttnzbhvdr.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtwzattmca.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtuqysrbgz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtstphfcbf.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtnysaiurb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtnmlqqvbj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqjgfyun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gthpkxsyeg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtgjbmsrfk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtvefgpgbs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvjgitsa.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtnqxihrex.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtlfngcmxw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtxnwbqbro.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtqksdepgx.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtovbwgksc.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gttnqfjrej.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gthydapgne.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtiakoyvlz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtlmqopgpx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gttcuwxtel.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gtxlbhyotw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtlzwiajim.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtudkfuzhu.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtdsweuudi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtdlawogvt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjejrqyx.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gthbtxrbto.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtewamufjg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtsqkvqgdm.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtczmzlsdp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gttfspsseg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gthaqnqzrm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtxszjkbai.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtbaogqecx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtynvocwuy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtxduntmes.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtgknwbgzv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtarixwfcr.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtdhyypoyj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtgoinjteb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gteksonlrj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gttkeakvea.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtaurcgadr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtobdianhl.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtkrtewbht.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtzahugfpz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdlsttnuf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtysbyxbuk.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtzcsitwqx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtswkxiixk.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtsydufc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gthlhoyfsb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtcyvmxsua.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtigmmdqfb.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtnlnsofpg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtjexleftq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkrvjffg.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtpstbnhkg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtchqoslti.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtcbrgwxbf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtjtlmvvlm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gthotdngvg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtpakbarue.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtaicqkhkt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtyqerxalj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtqieznqhy.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftsmufvs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtvwguozcn.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtyjelugfk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gttjnmpglk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtjcwumcji.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtpsxhwofz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtjprkvoin.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtnqmxnijg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gttuclwhxd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gthjtktwhl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtkzgqszkj.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gthoazaxac.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gthbzlguij.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtlchjqnjn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtrzahwaot.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gttpuowetn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtooloxuwd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtthmijhce.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gttakgeqqp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtlvpbohpz.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gttymvxplm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtcezbhbok.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtktvummlk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtyawfbylo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtpfvuoiek.html


<!-- 参考信息 -->