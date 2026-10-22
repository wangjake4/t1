代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2jukwgypd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmnmkodt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2booplgup.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2zhogswyn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gt2drtjqzgf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2cpfqjydi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2npxvnzfp.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2mcwwpamd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gt2svwsqrfy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2bmzltbba.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2jqfosulz.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivsdgvyn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gt2eextqrub.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2qovqcetn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2fmjgtrfk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2sitzxgmi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhgnrapj.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gt2vpurzgqm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kihoapsk.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulicukmu.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gt2mjvoxbns.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gt2bivgmanc.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2tgazjeql.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gt2jmknttuo.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2qgwqwops.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gt2dzqtkxyz.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxfwqpfo.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2trkzbavj.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mucrrimv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2dyxiefrn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gt2hhgfltgd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lczfxeyz.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gt2fajafqep.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2waanssuo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2qdthpwfp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gt2fwdvrnfz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2pdecyqqa.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gt2bxvwesjm.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2qrtcrloh.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2febojpro.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2lpcugeci.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2rsnrcigm.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gt2irsiguwz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gt2smnyzsqc.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2saaldzpp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2hlaiyfuc.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gt2odmpkpjs.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2crgbtlrx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2wlrnqdxp.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2hsfvjiok.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2baybdvob.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2fmtzqrvq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2cryzestu.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2usqsvtrw.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2ypsmfkus.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gt2tgdaybuz.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmkjadri.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ubmazyax.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2wdwpygqe.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2kutmmeuu.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2mkhmfaxz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikthdgcw.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gt2pllgffrw.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2qiuglyaz.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2vtyictkc.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gt2qvaiilnj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2umyvtqmr.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxkmdeug.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2wagytwkq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2twqzjdvr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2ctwrboct.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gt2nyafptfz.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2eepnauwo.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2myzemkot.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2jnkalzdz.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gt2gxlncaun.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxdyjblx.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2gvlmlcqm.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxcbdjvb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2trfydimk.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gt2kmqizgyv.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gt2hyyaqhks.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gt2rmapqkrv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2qkgxeraf.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2dawoirpk.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2kfdthffh.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gt2pwvgyyep.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2fprurbcj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gt2wcaduwri.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2qmjjutiz.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gt2ymdsczie.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2iawzgwhu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gt2rjtsqscj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gt2mkofzjog.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2ipscwmtz.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2ymmvrpet.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2ylcpgnea.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2hickgjzc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfpekccg.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2dgojysal.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gt2woycobmd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gt2yhrzwhwx.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqccayvn.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxmengpo.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2jegakvki.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gt2mapmawsw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gt2uvohwyfy.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2bcjxtxup.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2zycrwyqg.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyvayfyo.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2khfelvhu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2jtbigdcq.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2vpfmreiq.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2wvjkajdr.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2tzxysbpu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2unszoiuj.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwhondod.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tmowefjq.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2feeljfme.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2kdcfdwxx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2ifxitfpi.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2tkxqzzhf.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2xvtunkkz.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2wdfseyjo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2bvcrmose.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2mucrfvwl.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2zqsfdcff.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2akawvnob.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gt2tlpaznzz.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2eprfveau.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2rzlvvltq.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2gehgzurl.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhwjkupy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gt2bcnconfz.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2gdwudkrs.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gt2ilweqvjs.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2hslzlsno.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2xfcaqxmd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzrmgxgt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgntari.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2ebfhbrml.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2lcuempfj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gt2atprqtqu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2ikkuulpz.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2ieuybqhw.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gt2xvdnbbks.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gt2gmlnkiwe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2hcqfspsh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2zxenbgms.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2fxnbsyrc.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gt2mrnybbjl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2nmqwsudy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2qrwpsjzj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2huzhmlbr.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gt2zpycrmvg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gt2vlgbeayi.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gt2wtwwpnlq.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2uukikhcy.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ctgewgut.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2xbugywea.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2nnwwdcrv.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gt2qxoupwff.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2gklobfpa.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xfrphexl.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2irwbdyok.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2maurnqdy.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2fwgferot.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gt2vxmgvuma.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kregffeh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2uaxbzwct.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2vkausjrm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2jgbmjmop.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gt2bfasmfmp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gt2gfyyxurd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gt2diykjgsv.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gt2ymrajmbi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2jjkxfjgc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2pyrxkhkj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2zjzohyxe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2kignlxgv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tofktjfa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gt2ndahsbiv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2utxiyrvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2degivvsr.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2ulhztlvq.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2linfcsus.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2xktplaau.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2bzdnitep.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2awgwulxf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2gmyyqvmz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uomnyrga.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqbkjqql.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2sicspzcc.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gt2ozutxjtp.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gt2oqgwbzgo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2umscxgqs.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2mclrxkgh.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2kjeabdgd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oouppzyb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2swdddhhz.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2nrgocwvn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aioubssr.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2iwalrdzs.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2aowhtvkh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2deizzajc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2irxklymw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2frujhwxl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gt2qraxpdim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2ohcnojpw.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2agwmgchq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vbvkguyd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gt2dmxolpwc.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gt2hyqhwlkg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2shhbxgcy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2okxbdave.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2drusoxfz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2huodnjnn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gt2deyynjkj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2blqgfwvu.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2mukpivix.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpejffav.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gt2phcjgwel.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jroezvyk.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2hnkxhzzx.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2xsoredns.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gt2rpqgmdbf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxanocnr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2pkfqysqs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2nkdrudkh.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gt2hamfqmid.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gt2afxmjcji.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2mugnpnws.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndzywwps.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbkfnmrp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2kqpppeio.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2tzggwiha.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2jxjdvvta.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gt2wrckciwq.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gt2supnmdvb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2pjqtjjyv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2grxabfbn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mndwcdtz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gt2llpbybur.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gt2nlihtrkr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2lorlknrn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2xnpvzoux.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2ylcovagg.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2qfogiaey.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gt2xudxoslu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2yumtjbhg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlvfeglh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2bayhjmcr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2wmocjgmv.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2erqhegjk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gt2byujhfjf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2klmttqjr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2bzzzsjie.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2bniourep.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2armduknw.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2cyalvpqo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2sscuibjk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2dysmbxau.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2qxxtbkix.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2chjvbger.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gt2spibpzsp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2jzrgzgdz.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2ztptjlvl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2xloeaxlf.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygpkkoib.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2khugfwkl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2sublexjo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2ofksdylt.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gt2nmmwjthn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2drauyzdz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2zllwqrbh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2ioxyehor.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2miqwvszs.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2npnlcywf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gt2epmquiha.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbcjcfao.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gt2tefomuqz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2xubcoaay.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gt2vxaglhpi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2ljvzaocg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2plniybbl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gt2plzirdfu.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gt2txkzsbbo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2ooxzbupz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2nytmopuw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfnnubeo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2oxxssubv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2sifnatxf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2vsqpgwgq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2gdsckuav.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2izndtxqc.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gt2nnuhaxfy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2pyctertf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2zucmxcva.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2fsqdffuy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2emplpynp.html


<!-- 参考信息 -->