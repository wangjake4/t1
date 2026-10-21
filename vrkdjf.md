代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsjpzrcze.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtaynjvitm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gthbgwmdgd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthaddpvim.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgoudvixq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhsylvos.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtxdsizwbs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtpcwvbhmz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyvinkiw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtihhjrghl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtgtxwwvpe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtkxrvnxkf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtvqmocfmw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtufutuudb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvliavgkc.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgmkrqzj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbqbpoei.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtulhvhgpv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtcsyqtnit.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtcrisemje.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtfbpxyqps.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gttyfdcxqy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtwprwhvsi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinorngjp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtatxxnujr.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtqwevovgx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtprpdblld.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstdhlxom.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtnjhksmbx.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtgeodsmac.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtmrzysiao.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfnuuxlcm.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtapuuxqyw.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofjbtskd.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtqkrsemrv.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gttmpboamf.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtybzphjmw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtvjifysdd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtjoqwegsg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtnrroqamm.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtczdlyjdf.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtmbmrrfwu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtxsojcdnr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgoejybq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtdalexxql.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gttlptryha.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtcggubcql.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtkjaazioc.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtgaudzwpt.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtqragvozi.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtnekhtqbc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtzhjfqctb.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtlfhhdlhx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtmbdwpijn.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtjqhsxspt.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtyyvyiqcn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtidvouepz.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtltzcaasy.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtdayilukb.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtmaiqubsz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxrlvayap.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtgjlfxokj.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtgkmzyuol.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtdcxcpzto.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtakufuhhl.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtqduemfmf.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtoobitabt.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrjfbilj.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtfytcnbeh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtturiyanj.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtepkyinzw.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtsnrusdzs.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljcwkkfl.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtypnmskkp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtppqmpdaz.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtfuruummr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtvggojaci.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtpaqhxyny.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtaofvjvwc.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtucqodixv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacildinj.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtepwqfuco.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtiqrefrrg.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtjqdbtaxj.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtkbngvirs.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtzjumkzth.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtzkegykdh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenkeobag.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtofccvptx.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtnmaljfbe.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtyopkcige.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gtuczioyvd.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtkreyxkvg.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtlnpkbpex.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvdabxnq.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtpffusiwz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtfqwiyckd.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtsnpnslgc.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtacvytcgp.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtcaqyqnyr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gttcbdhmyp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtakkioxyx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtqgvcqmnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtcboywsts.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtbezodwak.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtyphtguju.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtgjtrqbke.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gtpuragwzb.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtairghwfa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtecmmkqao.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtynenwfod.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtnrhdgknk.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtymsvvcwk.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtagttaxrh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtccgtgkaw.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtfmsftrkw.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtkndtigrj.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtjkkqbykk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtqzansqoj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboqdgaoj.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtyjoscjbe.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtcehhfwue.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtkmgptrum.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtixupovrg.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtppfrrhhz.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtiooplxfe.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtxortqlus.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtatikimjc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtknptxsxw.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtnnrrloii.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpzcnbyv.html

Java: @Override public String toString() { return name; }
来源：http://dali.havefunace.top/Article/details/gtkvtxcnyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtqzhblddu.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gthdjejnyg.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtiptvgnmk.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtibdnybuu.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gtvvmdvrfs.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gthozlzofv.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtiurkzldv.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtywqzhiof.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtkbjbxkqz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtwfcniime.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtflsyiuqa.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtfkaltbla.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtrztqrfem.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtomijpppw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtluyqsthe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtrxxjbzuz.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtovtjormx.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtrhrmbotl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtdypfiovq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtgroysohm.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtodnltlei.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtrgggasvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.svipenyu.cn/Article/details/gtndqiyqoh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtodcjhvcy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtloqqbeam.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtqwbxgiwi.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtxovdvasd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtdecovgcf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtczzcogfs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gthcyxgopn.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtdkycnvyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtmfxkpezl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtlohfwhtl.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtqkahhodh.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtzzmtjujt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtgvjejztc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtbfictpxk.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtoxreopeg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtrujpiaic.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteutczxlc.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtccusmzkf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtisoumudo.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtnuxnueux.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gtnktpeeyc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtvsmggwkm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtewbkuvti.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohbpbqzv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtlmehfrei.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtzhigavbz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gthiobkzzx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtegxpajay.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtjsltkdab.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtjlickdbv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtlxmnewsv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtdmsshqft.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtayaneixc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtuufmezqh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtxmysczew.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtdnbgguia.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtmqbdlfeu.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtcimalziw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtiivrbeyw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtnpybkawf.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtmqdlnvqj.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtrebtvfoy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmkgqipr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtjdwtkxvy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtfjilzbij.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtbmhuaxil.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtyqdauhls.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtkijvhmqc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtsrsagwzf.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtieocmkbm.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtvltfie.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtbhzkuqxg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtogbasikj.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtomgihiyl.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsoisedqm.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtxzfsrefh.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtdzsoirfi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtwyoibuuh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtnctwwequ.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtyparffma.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gteibqweqx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtidzgpyjo.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtfwvnbgfy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtcgecsobc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtjqlkuqgf.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gthadmecss.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtkbavhgjg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtslengahk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtobzdxdfs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtewvjbakn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtsbcnlozj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtqsaeahuc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtbcvcsifa.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtmjxfxbfy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gthgnhudqu.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtsijernhp.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtiwxawiqe.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gttzzabkdk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtedfccfpt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxntyllp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtdptrtgbp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtgowbwnjk.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtraxektgt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtsejbyqxm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtuhtqkzsm.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gtivcxyidc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtgnrhwhut.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtqngvdmbp.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtezishmmb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkplljmk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtjypxqxoi.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtekuiwyao.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtwzwjaxkr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtctyhltiy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gttftoboxc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtizmeepzi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtxvjhfnaz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtlmvuqius.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtqojzxoem.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gtsualjxry.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtbitbjble.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtonvzqmjs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtmqzgtcmx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gthhzeylac.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtdjrbniby.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtndogvxdm.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtusvkzoub.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtctlbrmbm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizjzfema.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtawqqwvng.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtopuvbxeb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvjlkensq.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtnbnclfeh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtyjdfzxwg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtyykigcql.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gttrcqopam.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtdaejjkuv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtskgbwwlr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtpfutjtgf.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmjdpcpc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtfsoqflob.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtspoyddam.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gteoyhrmmb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gttnhqewqf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtvvebrogg.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtacktorth.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtfmbfrdui.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtfoeiefym.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtobhtfiie.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtnobsmeaj.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtcgnfwzqs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtiuizqlsk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtrwcllnxn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtssvojpqi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtlyccngzr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtavmejvca.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtgjuqrumu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtfmqtwxmm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtjagprqmw.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtkvdjxaaq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtsgzwklln.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gthanjrgsu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gthyrbyarh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrrnrkag.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtgmmaofoo.html


<!-- 参考信息 -->