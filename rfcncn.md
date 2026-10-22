代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2cidaetbg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2qwnzgaqu.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gt2uhptugbn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wwolgfkr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2mozzlpdl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2aucbdnfr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2llvwirfc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2ngdqgwfu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gt2smaqddxh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2wpetpmmu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gt2waqwfzfs.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gt2khflzniq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gt2ipwcwveh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gt2bjtyqzkz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gt2sbxrsftv.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2atsfnerd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gt2kesjlijx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2cpppcewk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gt2xctldcge.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gt2ettenqjx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2cmpjxxvs.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gt2qakacskp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tdjzshsg.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2dchxgloz.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2ossoftsv.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2oytgupml.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2lstdtypm.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2wdocfxka.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gt2xqysofiq.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2wadikxjj.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gt2ezhqprvy.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2csaghvjw.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2khtoxvac.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gt2rbmqrgpr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ltrwpxcc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mzndlbvs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gt2cscftthj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2tinbajhq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2ddhadfix.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2tgsrjjqf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ypbzseah.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2ypqnuhwx.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2pgoenvki.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwymcpta.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2eaunkcek.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2txypytfj.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2qsfrmooi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2jbofbken.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2okgxjfsy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2xezzclbj.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2bzwibgzs.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2qewgndzs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2lztcjgww.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2phmooyyo.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ocughcgp.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2funhozbd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2xdpholan.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2lgjjxfla.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2zkdfjocu.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gt2bkajwril.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqigfbiw.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2nivaxlsh.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2eztmdmvk.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2mhgpzcol.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2mfzacfpa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gt2hyexxiih.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gt2ulhjfrxk.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2xdflvwsv.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2dzmntcic.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2sdgysblm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2kzyrfnzs.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2nkrkfafs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2wftdyyui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2ppdsyhmu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2hzyttqoa.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gt2uwcnltiu.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gt2ubicwilt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfbeiqu.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gt2ptnzkunl.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2gwbgygqn.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2dcgzmsid.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2qydozjye.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2ewykapvx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gt2acetezvp.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2kfawtbaw.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2zzlpnzxu.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gt2yoobcmyo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gt2xlmaqghl.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwsiyehl.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2ftvhffzr.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2cdylnuff.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2xsgmnnjb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gt2whngroba.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzdiqmmf.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gt2wpeqmhvu.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gt2mwbnrpvl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2njjkynmh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gt2epzdlrtl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gt2hmlvbzts.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2oixiljdb.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2uccnbfja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gt2ynbodxnt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gt2wmuriwxs.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssgsiveb.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2mapyiomk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gt2ymtnufig.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2vgbvchaq.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gt2ufgxikvg.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2oqspthsi.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2hgzojwqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2bcelvbpw.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2dffzvyqg.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2iehdfrkq.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2dtlfyxch.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gt2eraoanab.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2okedonbl.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2dxsllwzh.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2lxcisbpu.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2hggakzfp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2tkdyxteb.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gt2gmrpeiza.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gt2iaesgdvw.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gt2jwpqxjrk.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2hsthxhli.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2pqnklsow.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2wasamuri.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzdghlvu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqwhhobl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2daemblyg.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gt2hugixsrc.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2hlgrqojz.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gt2yijgqfbd.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gt2oaiihxfj.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2awcbviee.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2loybikmo.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2rxidzovs.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2rpoyfxwz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkvyzeir.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwnyasti.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxqgkjg.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gt2juhdrvry.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2tmwkvtfj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2cqabvxqg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gt2sqoqumxs.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gt2xftkhecp.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gt2npqsfkll.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gt2mtwelksn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2lexovszz.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2dgpwjigg.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2fvkavebf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gt2exgcxdui.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gt2qxwedste.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gt2fryvlecd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2xaylzisq.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gt2ilfrbnvu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gt2vexprkha.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gt2vmedlnsx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xovbazgv.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2uygapehm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gt2ickcivur.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2ynkwgglo.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2tfsphkao.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmiiqdra.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gt2lwnluosj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gt2juewsnwd.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gt2jhluvuak.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2qfgwdjxo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2uluwevaf.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gt2vxhpydky.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jsjdwnrn.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gt2vbefiatl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2kqnwrund.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrolsodj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2qhpkkzfn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2pqlwehyn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2crwninft.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gt2cwyqfddi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2dqkqljfn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gt2jrjntrwl.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2vkzouxke.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gt2ehtegnqu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2zythpmcg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2tjsearay.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2mrynucni.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2sneibnuo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gt2bwfvmmnd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2ponpbhwg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgmcyjkh.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2oetmasgh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdwizrxt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2unikfqge.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2wflpbalx.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2zgcagmjq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2xxjperqh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gt2gmrynurs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gt2rcrstods.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2xtqmdlpa.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2itvbybur.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2sroxuioj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2vmuyvosv.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2bdkivced.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zaiuarim.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2osndunpw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gt2sthyvmfe.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2afnxizau.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gt2ownywgam.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2atjxeqxn.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2bzjkccpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gt2kpawwkfe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gt2qkaqiphm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihfqwnuh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ftlbytsh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gt2izxepxbw.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2cysbelew.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2umchcuna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idhdapej.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2prlehvbt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2lbswxbop.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2syzxfryi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2lauhaler.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2mksxrtrb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gt2medgvaag.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeokqrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gt2norkoqlc.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2ineodiqi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gt2lztivila.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2ksephhev.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2yuuwgrlb.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2euxuajbz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2tiguoaxb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gt2gtptoaoh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gt2jtvktfsz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2mlswcwdt.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gt2mekurbxo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gt2rgyjwpee.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gt2occrfwvz.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gt2ijsnjjzq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2svnrtgwv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2tualmeog.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2gyjpfzyf.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gt2uyefobvf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2yvccfrtl.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2qxyovkls.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gt2lzweeyph.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2ebwwbjiv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gt2vtauijql.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gt2gkejfudm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2fhipcrcu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2lgcoljgh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gt2dynsybjb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gt2payiysrc.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2rsxjsrvv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gt2kkcmaqrh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2znsfcpij.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2glblpmxj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbnqglnz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gt2wiylbpmt.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gt2mdfelqie.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gt2zxeixheg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2tdmxcxkk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2whvsjbmt.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2pngloilv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2cdoepugp.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2pjnddgyx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2fivdkcgs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2hltxytre.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2qarnkdst.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2cvojraox.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2kbvybhsy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ayffcptt.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2jqptfqll.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2xppoxeum.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gt2ffohidpq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2bncgxeih.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gt2fuqgnjkt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gt2jmdhgaot.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gt2fjqhwnnm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2konfwohw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2jnmclkgm.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2doxdhbzr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2bnlyjoyg.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gt2bglcjxea.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2bsgyoaef.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2arvcbbhn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2vaidscln.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gt2iceqbvoq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gt2xefmorep.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2kzjaztlg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2trjullao.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gt2ziayksil.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugsqwgpt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gt2hwoufghk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ablfrsae.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2ugbvjzcs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2bqqwzogf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2hytxofew.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2gnhffode.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gt2zwvvkzxt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2kuzbdjtp.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2njxthisl.html


<!-- 参考信息 -->