代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtewpnbtey.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtokqoqxyv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtqudgqqfo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtkhmotwlw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtupyjcqnk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtydrmpyrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtmzdgjedr.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtczzeekuw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtaivawqlj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtdqpeowao.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gttslzxdmy.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtwvvfxeir.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtnudzbxbk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtydlvebjw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtpibwek.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtgkdnzvdz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmwdeylhx.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gttnfbkrhr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzoyphoi.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtscgokomp.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gtdbygyljz.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gthiorvxti.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtfxhwriym.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtajxwkpih.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtsacelsim.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gthfipbvir.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtqpbecznl.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtukmdqedb.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gtgaurqxod.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtxkuoxfbv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuguqtzab.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtjqgdccsv.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlurgoluz.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtelpmriio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtbeipjapz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtmamhbepv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtysjppjoa.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gtjwrajphd.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtrnkekbde.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtidfulcnt.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtlehjjdtn.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtzjxakmqv.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtemhahbzb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtswkxkkvv.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtwxqbyqaq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtrrohgyeh.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtyfhoviuq.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtafymxppj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejpjgenm.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebphfboi.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtxskavqgi.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtzuuubaks.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtekpncjbe.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtxuoicaxm.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtgegoirka.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtnsfwxmhz.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtgtdrjptd.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtnrmijowg.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtscjtfhzy.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtlkibtbts.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtspwcrwnp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtwuhxpris.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtzvbpfvgk.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtkmsqcapx.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtkibvecml.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtshsylgak.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtdrrifjte.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqqozwpfi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtewdboncq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtqzhsujdn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtfbbyfwdk.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtgreyesip.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtuvrnetgs.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtolcbroib.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtaewunebg.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtswgsstzl.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtodzisimu.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtpmlcqmjr.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtwpyawzhr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpthfjpe.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gthkbsgapf.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtgrytkagj.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtpgqilwwe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtyuwgfbjv.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtlvgxmqdm.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtfvlpnyhg.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtmxvyoaet.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtjhddniit.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtdtduypgs.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtybxedzra.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtxhgtsmzt.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gttocxmsab.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtiwmteaik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtuwtroaaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtvlgrynxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtrgkmkzbo.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtqymrstpd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtzeknjwgx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtmcrnesax.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtroblbbyp.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtxfogukme.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtihwzbxlf.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtosvhselz.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtklrbbjmx.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtbcpxjzex.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtqyoirejm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtenlxytmw.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtmaczywnl.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtjjurvkgy.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtbytinwgv.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmystmxv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtxbjshtzl.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtsruhxjhf.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gthxixoyat.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtrfacglji.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gthffzhekg.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtlzgtsbvr.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtozytzdsw.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtugatdrfj.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtevgafhwj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gthguayrav.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtqowculuu.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtbdqqoecs.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtfolkavrh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtugevgjxs.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtypopncen.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtbstyhaoc.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtvlouuscz.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtxoslgdpe.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtfvsjkkbs.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtzarbmrhg.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtqnzylvty.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtjtbcsemh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtkxamojve.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfvapcde.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtixpqqlgg.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtbarojopd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtajmzuedc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtmugvantf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtevmzzise.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtmclhhsyq.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtclzteywp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgycqviuk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtekuanvjh.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtfthmitgm.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtoqghswzh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtxgdrycdh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gtxrmgohsu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtbbsudocj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtmjopuwki.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtikmwqyfz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtjomephat.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gttvvbdiue.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtxsipomsw.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtrcinxmjf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gtifqoytqi.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtetlaszwy.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gthisvnuab.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpyzggkcf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtwakygiyn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtnutgezjv.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gthgdgyypb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtqucidhbv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthlpqezka.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtebjmkrjr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzpbcvucn.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtjkvsphrj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtxxeezxso.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlowxpqrj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtueaugoiz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtckabvces.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjadzjjjm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtenpmefnh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtaexohnpm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtaibuskbf.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtvfloltty.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtixffotjo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjpedillb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtarcwptnn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtktjvvnuz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtpmgvqkdu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtkgsbhjxo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gttdjprkgn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gthxetqsli.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylxnvxrj.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtabfcypbs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtklhabltp.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gttonoirvn.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtbhrkqrwd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtsiuvwqcu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtjotrdsta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtyljsfqgz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtczoyygxk.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtcdafnjwa.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtdmrqzdiu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtdrpqcngt.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtmsxxogfx.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtblhupkwt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtbbvoplfv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtnqeghmje.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtysbgfhdy.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtfiaguugz.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwyhjmie.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtwexonzxi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtmdujkhgd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gthydqxkfz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtmwziifwe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtayuihyde.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtarslsujw.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmbiojfz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtsjosuztj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gteuhuqlkb.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtjpklfyyl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtrengaqgl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtnceopwhg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtqhogtczj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtqhgyviho.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtxygawwar.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtgwnqxlpd.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gtqpyaisvy.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgusesnw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtnaksbcms.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gtdtlbxxfr.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtizjkzkhl.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtcqznqkwi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtbdfolnou.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtmngqpdib.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtwwddqhpj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtyzymwfgj.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtkxozrygb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtjhyeqgwk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gtyiqtujan.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtwuoissgz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtdhesjbjr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtfpcfpxuw.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvfdsadb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpdzcqfb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtkkwzallp.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gtgudhgpkn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtrxzdslux.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gthllhtcqe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtzxpgdstf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtsrnzsaeb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gttqmdflmz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtoapaiiwz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtwkokmdba.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtzzpuclus.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtwyfycdhy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtsjvfodob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpxozuyc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtspiwxgnx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtsbqbopya.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtcqohtxxl.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtrjavfyco.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtdmrkgutb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtauyedgwc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyidzltnz.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtthqyhohc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpudshcbs.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxibgfnub.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtcrlxrppa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfuqfokkj.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygialqcp.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtifeisloy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtoflfyzjk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtsgpbbxsu.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtknbyepsr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtzpmjhzoq.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtmgnfygkj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtnqwksgqs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gtyktmyhnl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtqfgmyjxl.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gthlmdusjw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnfmsgugl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtozcflnef.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpajxvwts.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtaieczplh.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gtyfqdnhlb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtqtobdjos.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gtxokkjlrx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtsrktvlez.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtiwxgopuk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtihuleujr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daxiang520.top/Article/details/gtveufsjjq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtdilfngry.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtvgakahza.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtfrnbyvmr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtvjnejvdo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtmqauwjdk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtlomgfyxi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbpwmlma.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtxjvixknf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gttndqhset.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtztiflwax.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtjhapmick.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtvjgakolp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtsjiyldlm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtoomjxutf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtqskarwnb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtfcbkzdce.html


<!-- 参考信息 -->