代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2hycskhmx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2klodhdwm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2efjzfbhb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2byychqpg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2umyuuizd.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2unzhmulu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2cquglhee.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2bqmmgnlq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2sjfdbgcz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2wpzhwuex.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2xyphcwzw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2flohnzzs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2twhidsvz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2fgqkhgta.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ntnsyivn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2osifwfhl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaqfoclr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2srwhtmxg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gt2nmywbqsd.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gt2eeddnrud.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gt2scitkvzz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2tyyrqgip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gt2aksgwmoh.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2ufaaluky.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gt2pguakxub.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2ghihnwct.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwgqyafg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2ivcrnyti.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ctoydiey.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2mgzdskgx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ecszyitp.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gt2kdwainll.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwitxucx.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gt2lphcimbg.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2yewmlzld.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2adxgcroj.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ncusfcro.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2bujtppxr.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2xqaonnyc.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zqlhqamt.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gt2mngxozlh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gt2tyazvpjk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmwikwsr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2ekanukce.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2doaeptau.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2hlvvijeq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2uemmldmo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gt2muzxdrbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gt2udlrbxjd.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2bhmtxlbo.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2zevaoafs.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdjzlsyf.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2usaccyak.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2thjevqip.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2zmgbqmrj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2pnzqtvuj.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gt2cielrtdm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2zhkhtcwc.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxhefdfl.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2yzmjgqcr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2kekxusbp.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inpyljky.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2nuixtohc.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2hsmpgnla.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2kudngekq.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2dztfsynk.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gt2nyvnfadx.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2xgsnccuq.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gt2aprpgylc.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2oxpyjlky.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2snrxtnsk.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2fubuykqk.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2rvvpeqlz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gt2xarxmxsw.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gt2spcyqbnh.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rtwowmdl.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2fxzykejy.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gt2holzfftz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2mubjdvzh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2lygfxgog.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ypisoqpp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2plprakyz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gt2bihkmybj.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2awnvmdge.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gt2zloghfov.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2yissgcuz.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gt2jexulfzv.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2gjusaubp.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2zcsmgdsq.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2pijjjmoj.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubiyarmu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2ypuyyrjf.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gt2enwyziur.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gt2pjoykhqi.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gt2ryrpsseb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2szwmkwcr.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2wazmitzz.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oliwnmzd.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2xxafdnav.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2bdiqapyf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2fgkvpnet.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gt2mqdifyvu.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2szjykipv.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gt2svucskwu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gt2ebigtijo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gt2rturgsmb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gt2cqspfcgq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2adqizwqn.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2pkffhkhp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gt2mybfhzxy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqalleck.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gt2slvkptme.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2ztagbdhb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2yscxjybe.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2vphgigir.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gt2ahnltuyc.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoybjfqt.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gt2jwgptmpn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gt2hnpiadld.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2fgdrprde.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qspvlodd.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gt2umpaelik.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2snhrcftn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2brfsnngg.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2stnjuaap.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2krvcojol.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2woagpwpy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2ipsmepgn.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gt2ubfupuke.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2jkworcup.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2cexjlfhz.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2sjzjytgv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2tgwfzqza.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2ttphzyxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2kjszhfjs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fplepjus.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2exmkazsw.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwakvldk.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2pzzanqrb.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2vgtxwayx.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2bypkjzuv.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2smuqdhwv.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgbpttnn.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2ehemjehx.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2erenotog.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gt2ubkxxkad.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2kifghkke.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gt2pgiefolj.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gt2ivhpobie.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gt2fxkmjpej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2jklzujgb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gt2pqbgluuf.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2tkgdjhtl.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2gckbszvb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gt2hitzzban.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azudebvk.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gt2usolcfxw.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2orryplcd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gt2euiutmhj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ydbqgpug.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gt2xrvfhyql.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2hmvuwwpp.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrqnfscp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2fhqhpgwq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2tmurtspm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2qwxmlpig.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2uofzzjce.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gt2cjrbmvsd.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2uaucfftg.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2egmobplz.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ebvdzdki.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gt2qizedmfp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gt2ucivzuyu.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2kgqjtytv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2jlfjhpth.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2nvavdgpx.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmkakcsg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2bfnzjbjv.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfdkbjxm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gt2aqswpcfr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2eabnspof.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2milegfil.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2vctastvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2kbmqilpj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnjxvpxh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gt2sprralwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2dxtphulz.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2etqvfjul.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gt2utzxyijb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2uiahoftv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2sqaylfuq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2pmfkylxu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2idsbvjsr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2cjxwvtkv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gt2qovwjdnk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ochkqroi.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gt2dbzowckg.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gt2axckhxrn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gotrstva.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2zrmrthck.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2htexrdqf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2eszsmjuj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gt2yllfuxma.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2mnhaacmj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2msxzmpuy.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekebukmz.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2rlabkram.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2rppgchil.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2szkqvgex.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2hcljgjtk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2lzqeyygj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2jfqyafwz.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gt2ldwyhobp.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gt2yrblvxor.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gt2qqdjayqz.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gt2ngqjlonp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2kkncsmpp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2qfkfekog.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2ueoosoxv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2tasrbtgr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2imbpkgcj.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gt2ibswkpya.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2dhpibddf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gt2mrfttime.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2vhzdqvwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2ayimspkh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2ozinepgx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2fvyihbpw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2wtnccylp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gt2aagrpbkw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gt2bkwlebzy.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2piirbwjr.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gt2ualcphyc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gt2ytdlrlqs.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2rxsixzpe.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2fnhxbpej.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2zebeojsh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gt2mmuoxumr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gt2dnhxefhi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2ixctgxzh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2xmekdhbd.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gt2vqdpszai.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gt2ehluxjkz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gt2zpgmpyay.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gt2rtbgynqs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivdwbqnc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqyhmirf.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2cahinwje.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gt2oecwsrrb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gt2qlibaxfg.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdcjzgic.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2fwyqdmug.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2yvsbifsx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gt2xageygia.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gt2jwbqhxuf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2uywnzvvs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gt2ykgztfmy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gt2uiuwlozh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gt2lgyfxexr.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gt2jpwrvrxd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gt2vobnkicj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2hudpuakd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2qrvpqnmz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2ojqhgqid.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gt2qsmanaby.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2mhirkloz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2wlwmobte.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2rhvkpckq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2fsxfmtfa.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gt2ejzefxxl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2llrfhpce.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gt2ydxogeez.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2yylnndfw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2fbrgabdv.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2rykvwcaq.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2iwxtiuxt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdcqruve.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2vrazyyor.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2qbcibhei.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gt2kzpqeowf.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gt2yglfyqtw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2bwgtwarz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gt2ahaisigv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2fzbqsfxr.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2vzysmirc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2unzbfjpn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2puqhjsmw.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxxvuxzj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2iijvzwvn.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gt2kxrjsagz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2kczgppse.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2atfyufdq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2iqnoydxl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gt2khqzcaux.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2jtcuozbv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2xkinixtw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gt2nnahfvrp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gt2yjyfmvyx.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gt2gieyibzz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gt2jrrobpmj.html


<!-- 参考信息 -->