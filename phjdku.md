代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gt2bbzwpnbo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dwleccpm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2mlcxwyso.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ytyptqek.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2rcuptrrx.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2qcfhtyol.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gt2aesrdjef.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2wdbgayzg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lrkkysfu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2pbaxdmec.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gt2kcshmxpz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzddfqet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2mdxibusd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2kmtpmepe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2ddbfixxe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2dvwitnpn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2vouupbtu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ullojfni.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2qfjwpcxi.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gt2yffzgbli.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2coxyipxo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gt2jfhrmkcm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2lgjzrzsp.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2hwuhyzfm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2ltskmnkk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2qdfsnfwa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gt2qubhulyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2drhgihqo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fmytltlw.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2fbspeelm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhzndzzq.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gt2ihjfgpbf.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2ybqwpntm.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gt2adrkaysc.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2mragwjmf.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2ybqeyhyh.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2nmgezjpj.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2sgysblvq.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2reouvpvk.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2dmfieteu.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2dwfxnwxz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gt2adzuvcby.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gvwryeep.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2skrxvmhv.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gt2irurxacw.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2lsctgccx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2jxdrcrkg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2abuadjql.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amecsbru.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gt2gtpfrerh.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2omddregb.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2fjosmqmq.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2cghpkcmt.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gt2efavoyas.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2cvyzfxpk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2baamzfro.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2loidzivo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2uyqljrkl.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gt2cdmuxzci.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2xrhponzd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2kihuntwd.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2fnmomcdh.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2ctucxzot.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2eyiyagts.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfllsifr.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2oklkyxzd.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gt2ycvonllb.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iimrdnnv.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2hoydgdfw.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uviegkfi.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2joqmgvxd.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2aagwnyal.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjuykfkw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gt2hyerznim.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gt2whtzlqbt.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2clhofuzm.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gt2yndppfjs.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gt2wiyuomkc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2kknqhafq.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2jfhptmmk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2pxezvyix.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2apuqvuin.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2zdizapno.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gt2btgxaxgg.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2zppsibvh.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2mazmipfr.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2riykvygr.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2cdsiwgiw.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2ccmegpls.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2hdahwczi.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2wnmtiwpj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2nqwzyvdg.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gt2unlpfmip.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2kmdilany.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2uudzzsqf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gt2gjvmvayu.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gt2zlezsubz.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gt2dprujdsq.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gt2lcqzvyww.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gt2ribtpaxi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2nczburrf.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2lrrbwztv.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2csjauzej.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gt2bxgdhvem.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gt2prpwskfl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hagghphu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2ffhmtjig.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kjhgobeq.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tngqswak.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2xamdmegm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2umtvvlax.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2bbrhqikc.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egmuanep.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gt2mmkswaip.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfwmdgow.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2ybixtxkk.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2ixmcrbyf.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2tgwrafci.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gt2hoaszvwx.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2ihzkxigu.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2tpfoyxxo.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2memprpqh.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2trlpcgsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2jlxwxllz.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qmlmrsax.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2vyucuxdr.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2mxktdjyg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2qlbxoqsr.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2gccysmgb.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2xsbvjbui.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcpgpzai.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2dvsqjoiu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2qcidjrzt.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2krrzggng.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2vqdixshg.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2rlkqloly.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2hcbpkkpw.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2vgaqfrik.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bribazza.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxftssgx.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkhnpwiv.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2jvqsqzky.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2dcgiuwjz.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2eisdwcll.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2ijeotgzq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yblmftwc.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjoniwch.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2jsgmcprw.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2itdtdunf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2yowfxqsq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gt2bfdwooxv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2irirdwxp.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2zsytpnyy.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gt2lykocawb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gt2xucqijzm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kufchujz.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2lwsbmsur.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gt2aizwrial.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2voyjxvqa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcfpawnq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgihzec.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2vemzgfom.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gt2nkzfdbzg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2btawzcef.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2sybraogn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2uetnboxv.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2ahsmlyfn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2vjtcymjv.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scutknsw.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2arinkeax.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hartgbbe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2whdmwgxj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2thqlynsd.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2ovprtzvd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gt2bucdknht.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2oiegghlb.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwhodhef.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2umzwofdo.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2vafdkdri.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gt2vnlwjrjb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2lgbjnvgd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2edwhqiwq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2euckgzyw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gt2inwgwfcd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gt2olrljxgc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gt2mnxnqoxq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gt2rnsajdxh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcqmnpo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2eyhjbpfx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2ehaosdbl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2lkbpvftd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2scvclser.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2trmqpsyy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gt2nwawqqal.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2xuxsfqhg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2sdmorsun.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2kyoapwvl.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gt2drvkmizz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2tgxhsily.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzepctjp.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2ixjhjcnk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjgstdou.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wegsdcvr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gt2eawrgits.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2svhskwaf.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gt2gqjgpssu.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2qcsfbndf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2xzvqvkmw.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2pegurteb.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfingjyn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mbxazznq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gt2snbslxyz.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2hpwabtcs.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2pmafkvcv.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gt2afanldzf.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2eksoalzn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xibgugex.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2vnbuonyp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2qqpgolut.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgaacxoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2hnoijqqn.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqumozcx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gt2dzwqtucg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gt2xrxtoipe.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gt2zxnefalo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2yvlrmfwj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2cskmmouy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2hgmuyifs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2kfohaxzu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gt2xuyceuhz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvrxqrtk.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2fdeptfez.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2ewtdvcuo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gt2yywjfvnc.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2qwisfxag.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2upxwxilf.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2cbbbwyts.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gt2bhrfsafe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gt2vjzqdalo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gt2bfzofran.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2fzubjtdm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2qyegifxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaolggfw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2ozshzalf.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2dcbppkxo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2qshlhora.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gt2nrkyjhjc.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2pewashfs.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gt2lwypqlxd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gt2oaakfwhv.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gt2jvxqujnt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsivauc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2otxteart.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2kstgmjwq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2ssesuedm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juyxducr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2aubsteww.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2uavatjai.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gt2itoxdclm.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2bbccqvyn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2xmduqxaa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gt2tdekzrbb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2suymnzjp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2kzzurqzl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2huotwoyv.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2fsfzhacr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzrpcwvh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2oynyvxyy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xjsrfaip.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdqnqmhs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mpuikiai.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2dtuhawob.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2dpcgbjnc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2qchebtjv.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ukdhjbff.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2efbqyore.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gt2sdxojpbm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2pvqfsene.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2itwkeywi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2wzklfcag.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2twqujayd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2fpmyzzco.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gt2kxaawrkv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gt2tfrhbcbi.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gt2hsbipenq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2lshtlswh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2cuugnzmn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2dlchxxbp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2iyjeotcm.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2huofleyn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2kyotrxfy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqtszyhu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbqsmnoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gt2lxwxgyul.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oixllkkd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gt2roiycayg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gt2wvfhwsqq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2bmpzcedk.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gt2jhslpiso.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqgjolcr.html


<!-- 参考信息 -->