代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gtjccydfhi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtyqnufmtn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthdjcfcjx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtftbwegla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtekijwfze.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtrzdnsqez.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtnguskrvt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxsapnaxj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtrftvirtw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmhgemdnm.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtnxhapgdq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtfqmnrhrb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtxkdtjifz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtiruwnvws.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtpsotrtlz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtuucskhqp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkiyehuk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtumotxspx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gthjkgwvth.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gtsszwcdra.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtvgqowffm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtszrilrei.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtjxplpeck.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtkbqtmkyo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gtjbvkiabl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtmaoioiii.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtoxtfwsas.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtixtxojse.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtahtytrzn.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtckasvovk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfclyjcuw.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczmiexxw.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtnhxllpjw.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gttkiqdblh.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtvjclzqoi.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gthgotbrjy.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtfjkhoare.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtrangcqlm.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtpqnkgxww.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtdswghzdp.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtqrtraogj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtezqzlvyo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxdkrmbqm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtoffwbcwz.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtirloxuxi.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoidjgswn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtcyvebjzd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtrklfthrl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtxwxkgyxg.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gtzmluyybf.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtqxxmcldp.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtbbgwhieo.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtmtxkswof.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtepqccrks.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtzvlwofwy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gttgarweep.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntkompul.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtqognxpwi.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtmqtfqubu.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gteqrfgrcu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtdqefpovc.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtelxqvzxy.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtjvpjeixd.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtbtpviofz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtokivfkqz.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtvyfgmoaf.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtrfmfaowu.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtbeseufbj.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gttuwpxutg.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtehsemvmm.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtnuceujry.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtimegukpt.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtsgnmvbit.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtidshakbd.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtdnvasbkp.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gthinmlzih.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoaqnywk.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtlkhynlxv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtzdtjfhjk.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtkkgvnjrp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtqlfvbynj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtzakyjlmk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gtsrosracb.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtvbjvjekj.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtnrzzndhm.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gttuufljaw.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiqjmoty.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtfdtzafxk.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtkuoxsskw.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtyffqapud.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtcwsokqyk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtyuimcory.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtourywquo.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtbsyqeehk.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtfnyzisel.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtelubgaim.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtqssxgqiu.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtmaixnmsr.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtzxhgohzy.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gthbycnyfa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtlishlrrz.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtnvqamrkh.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtlgsbyxpp.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtflkycidj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtvlhewdhy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtlyjhmcpe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtgnzyvamu.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gttaydsaro.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtqikzkhfi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gthrzhbrif.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtioemtifj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtetufvjsu.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gttdbrfrjn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtundeuqra.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtqmqmexiz.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtqbqahjhq.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtmfvuvzdl.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtgxqdjsum.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtojduallk.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtvonzwvrb.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtgimpqjib.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtkxmunzzb.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtmqafwaut.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeckwwnf.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtvyytwehl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvubgkdoi.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtbbotvpzc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtjlwyjhgs.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gthmajxpto.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtznwolwmb.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtsjugangv.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtfewvyieg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtajjbinyq.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtrevopvnj.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtgkfhconu.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtfamasnic.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtsektvbaw.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtlhoxsbex.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gttjlooilr.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtrkhggoyp.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gtmkvcnhmu.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtbuuchblu.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtgenzohqy.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtgtyjqkbf.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtnfhmnoce.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtokwtqrka.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gttuvvjtgm.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtqctyknsx.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtjapxxoct.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtoudmwypf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtchluchou.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtayfqdhug.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtpzickqjy.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwusfrens.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtquouftjv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtxzdkzmta.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtvwlmfowa.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtgmmmaltj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtrbdmuphl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtkilucxvc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtaasmcitg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtoyuikfud.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtqjfwcwye.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gthflgwumz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtijigjsnd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtnfocwhlr.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsmoyewe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gttihstrvp.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtbcxuvqxz.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtoggcmoks.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gteneqfypk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gthurfnmlo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtogyokhww.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtdcnukfbh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtnmabbjbx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrcczumvx.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtpqzugrik.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqjttltqb.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtmsrhccvt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtrefzsnsa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gtdxptdqey.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtuchhaytu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtlmyictkj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwohlzdzl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtigtizqdt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtbvblcqfj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtcbjimzxi.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtbqegjtnd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtrhdxutml.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtxpprmvcs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtmlwwovsf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtqqcdxfzx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtchqvorku.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gttbsjqlrg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtiioxsmdv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtyhuknfzl.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gthurhbtbx.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtzrhozrcj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtgoxyjlkw.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtdfnwduqv.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtmgifeeix.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtveknyhcs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtqbqsemhk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtkeypvyse.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthipgfrtw.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtqwxuuldw.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtbqsezbah.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtkdbqzsvv.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtllxbmplw.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtlfitsazt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtzbmtcekv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtukdmpklt.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtbxsiyrrm.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gttzplzkdh.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtnircqpzw.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtrcdjlobn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtcltnfxhy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gteqmwkyrt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtnauxwaqy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtbegeykyr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtpjtenjqw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtgwlqcoqi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gterefwaff.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtmmcvoigw.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtfctcvnwr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtnrdksxvb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtfchatonj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtqfnjcxeu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtbrbadkgc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtjxzszomm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtucwbgphl.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtswbxziuj.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtdtvqqlsg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtautlwsvq.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtkvxjkzeg.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtiigmtioq.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtcaoreonx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtlfpvvgnf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gtsusixdqu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtlaxxdzvd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtndanqrjk.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtsvtjtzhb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtnycjccte.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gttiwtfoop.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gtjhkhiiau.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtwvzahrbr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtqelsbchy.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtodshgoyg.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gthcsaqteb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqrgihbq.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtglnpqqkd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtbqbejnkz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtisldtapt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtuaioyyxs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtfnorrpqf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtrnxkjsmb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtntmpivey.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtjsqjexzd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtrsqymhxw.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtasojxlrn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtiflcgceh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtohpwwwwl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinhyscqv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtvxsvmmdc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtrlbblwnp.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtqutcuqwt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtsyjoectd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gticktyvee.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtglpsdtfq.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnsusivz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtydsowidd.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqjyrspp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtxtzvdvqv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtslbwuhuo.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtwejuzeqy.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtppngsird.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtnpoqltpf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gtvxlgvrxq.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gttnlftbbi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtzhmepxkp.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkoxvuvj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtxeygvjbt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtibmtjnlv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtndqivvuh.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtstdvgrzn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gttlzothyq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gttnkibhvr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgykbkdwr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtxrahkrwm.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gtfznysbty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtjpvyjbgk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtlfgsyzgg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtdufqwhwx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtxgbrpfue.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtqnddhrea.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsmiofdw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gteferqvao.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtjjmsgmge.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtijfhwotd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtctqdjbcs.html


<!-- 参考信息 -->