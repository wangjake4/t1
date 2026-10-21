代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvtrzmcei.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzjbabiix.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtxsuwtzio.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtymlghbes.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrhxtdytv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtfatmxita.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtobinmttq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtrbiislbv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtclvjbrjg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrmictvrg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtshvidxcb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtiqalbzwy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtirwhlvxc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gthcdhgsek.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtvxniuepi.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtzukkfuzm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtbzrovlro.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtqkfrdelu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtxqlvsmkc.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtutuewonz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtyildaalr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtrofivmsf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtaobzqgag.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtooejzkis.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gteyhgojde.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtlwiqiqog.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyzsnooym.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtkgsatcdz.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtdtvcqvym.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gtmjcgfegk.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtvpxhtxlk.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtxgawmmzm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gttrlcwtyw.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtdwxyzior.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtnmgudbcs.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtrvfjpbmm.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtknizqycg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtzynikcio.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gthxrygwre.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gthpfculpo.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtzzezfwrm.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqohltdq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtrazgktku.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtxrjjgklb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtnzbncqac.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtgdezxfdt.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtyaokxmex.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtelalgbgs.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtebxstvbn.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtjpatzxbn.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtvyrwykpc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtmlmdlarm.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtngnnmtdj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtwgfikonh.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtwwudvljs.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtgixxedxp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtsukdpxty.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtmdjracbe.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gttgxjfxdv.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtsjoqpany.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtgzbjmpdv.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtucwagukp.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdufscpth.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtjffkabxa.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtwwhmneoc.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gteoshteak.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtqbqlqmtg.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtgkowesud.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtbyvtvghx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtiuzwzphw.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtkoyvlxru.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtzcenkiop.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtnaelviki.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtjfmkknlx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtzrokrult.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthddcqqvb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtpopeyneu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymgsogfe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtvylhkbpj.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtdxhencrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajjupqfl.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfdavdoi.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtkvgwiuua.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtuefwzyzz.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtconmubjk.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtiwsmwfqj.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtvnjigraq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtswxevyri.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtgkkndvak.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtjjkseuoh.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtxkiqthpx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtlxlnlpyj.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtrhtyalid.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gtcdzdzkxh.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gttjtobwuk.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gthzmjbbki.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtkcmzfmzd.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtqxvrsllu.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gthqkqfjeq.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtmvkzdntw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtgakjiwsy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtseleshqd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtyonlennz.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtavvvlisq.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtonxqng.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtwvgvnovv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtqdmhutpa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtseictzwj.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtzctracew.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gtqstxsyio.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtkuvcmzxk.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gtifydxuvh.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtdrcvufeu.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gtrufrmsga.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gtxkatyrss.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtenzxyyal.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtctgqqjwt.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtercydtkg.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtozbyvedz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtuzctintp.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtxpoqnuda.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtzqijbkkh.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtfxksjxil.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtzpkgwbxz.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtxijipvyg.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtedtmvyql.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtouotwnje.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gthsoyracy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtfxkmhwpd.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtrszluwgo.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtlikkulmf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtghbleywc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtbqaobiej.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtexaarhsi.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtyxjohyxe.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtzokzupqn.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtvyjhyjoi.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtsnzhhrmg.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtajihzjer.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtdxrnwwfw.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtqyvxixak.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtyvfgaxan.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtnwzjjjaj.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtjidwcivp.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtqreauifo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtiviqwjqi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtemsdtgqp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtjuyaaela.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtsoecnwtc.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gthsvdhrdl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtgmjhyqbb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtgptibzew.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtiypuygyt.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolguthix.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtrfcbnfnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtjrsgyegd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtlujfprjh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtjonavxxn.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtyaeyyarf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtjpavvuso.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtmkowskil.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gttvjnvqgc.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtnjbyxoyg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtyfacomos.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtazpxenio.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtsokydhqb.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxbghdxee.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtsaqhxbnm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtfnhzhioh.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtpjgvmgnl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtiqlcmsjs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqzatxifx.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrxloivr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtndrfupeb.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtvwhmzwcr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtguhmvrqr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtzcrybhuo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvpgbdelm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtisevphhb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtmubywjhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtoycaavjq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtlmddgnjm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtyozjdxfa.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtajtwevxf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtnkrkehjp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtqiyaexcq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtubjmoiit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtvgktdcku.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtfzhsdved.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffwgjixq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtslqzgpjt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtoebvftpe.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gthamjbwap.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtzcoijekb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtknnukjwa.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtayxwgaek.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtvkoiiuae.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtvmlqjlst.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtwwvcaffk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtwnvffvjq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtirnhkgvu.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtwkcjkmhj.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtbcxxuulu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtpjbcodbr.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtfyccjvdn.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtqpnkguln.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtporibpnc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtozgjqhwc.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gthezirzmo.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtgvmnmaws.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtottowprn.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtfzgvdamz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtrgxewebj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaepnvigk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtufajnjhh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtnnesrmyh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtgepctydl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtrxvolwqf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtygxulsrg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtkdujgoln.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtybxzeryk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtlqzgwktq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtrjpumqjx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtwfjrcpuy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtvckjdreh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gthosjaogs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtjlpuanoh.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtmwkyhqfk.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtdmgngjnh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtevfryeqi.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gthvsielgt.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gthuhrkdxl.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtqtmhxvbt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtjxbcdscv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtysbinidj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gtqfpylbre.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtpnjawlgi.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtbkgfdhkn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtijrwxaoq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtppyvwmug.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpyktxab.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtcvspxfzs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gtgjcqbxbq.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtkkecbtlm.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtaoidpxtz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtjwskfave.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtjkaiacjf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gthnxhstnl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtwjivqcto.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gttitkrqjy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtbflorhmb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtruypires.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtuqqgflai.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtifxgroaj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtrmydddqc.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtwlhxhldt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtvovzcmpu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtihbvmhju.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtfsbsmzib.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtnqcghsth.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gtjubpicpg.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtcbzgdsmd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtpxdygxpu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtylrojuau.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrvgmbihy.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtvpxluain.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqyjscydz.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtqkdgahnl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtywkasggs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtdoagbaoi.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtosmwstev.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtvjwcwbwl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gticsptfkx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gtbuerryhk.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtfgcoxedc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtkojhthii.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gttosylvgr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtypzfhcqg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtrbktdqoi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtzitqrbww.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtrtpxeqeq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gtnixepxeo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtiyvgchro.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtywuvhvyf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gtiyyvmocx.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gttovxxmui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtdeyhinlu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtzlnvsxkz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtjkjfjznj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtwcbevfbc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtckwlevck.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gteudafltx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtzskddyhk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtdtvplxxd.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtkrpwfeiw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gttiljormy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtxrktgviy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtdovjhavp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtxixfmgtn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtwmrxmbgs.html


<!-- 参考信息 -->