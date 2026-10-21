代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gteccamqye.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtligjezsz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtccyprokq.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmuqxwouj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtnvafkupj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfbnblha.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtteqivyor.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtotxkyvbe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtaumndaxs.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtccchopyc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttetkcfvi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgfldphfc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtgxglxfnb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtaxcofhuf.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtycstenwm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtachmhuro.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtskniyqvi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtpideosxx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzphrxtvv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gthslakhhu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gttauhqumq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtzxrfcgba.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtozuvxtuv.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtgifgadjv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtgwdhznje.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtlexspwga.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gtmilgednz.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtxhgwgmaw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtezyieuls.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtpejkzinc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtscvdggqf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gtxtxejzng.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwsmjtuwf.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtvbqdjnsz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtplegkkgi.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtuqljdwfj.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtunbaobed.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtureunmdj.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtqwcxucbk.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtqcxoaftk.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtmvaqmlev.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtttnhykpm.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtygizfntk.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtytxomnfm.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtweelczzh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtvestjwfz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtjrqpcqpr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtskobaigx.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtygracpea.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgaylxpqh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtjbrefhrw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtpfnknybi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtvcjcfdkw.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtwmtqhrab.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtsmvpdjmj.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gttrgbyfmw.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtftyyrcko.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtiwwciutj.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtrbafhunc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtbaptgrsn.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzwcuaph.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtsetyevdq.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzoyhbty.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gthynlxrmf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtvzhidynz.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtltggzixm.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtmzqetggv.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gthoicfudn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtyazfxwyc.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtqgkazrwm.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtqidbxhco.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtpjbeelyq.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtxewluuyx.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gttflrgify.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtmfwthrcm.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtbwyjbxrg.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtpfdcwbzo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtyeszujhy.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtuteiwsaw.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtlpmpzbyk.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtfuwznupe.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtxhomlito.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtsnmztmvt.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gteihophym.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gttcaknrhd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtcytwnrag.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtckevvgia.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtvnygccff.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtiwnuvaue.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtwgehzzdl.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtqxiekycy.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtaarsmwnl.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtofnfkrlh.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtrnrrdcbs.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtorbfgegt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtbfthwqej.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtmochorpx.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtwxvjcojt.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtmwklgzwx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtfxnsboxo.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gtfzhnryyf.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtzytyzeok.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtubjpuxsh.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtmqlcelqm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtaanjkdcq.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtwfodterh.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpxujrwh.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtzchnlcaz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtugpjwcnt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtessxcnev.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtnduzzhew.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtjvdevyyo.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkvemygwi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gteujbmvfz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtmqtevfmc.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtwmczeksp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtscelvjtl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtwamnfkca.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtwskbqmcv.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtsmugcltu.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtymnwbsnc.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtwsqvvclm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtztvwdkiq.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtvuyjtczh.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtlphjrgka.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtxygnqthv.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtiicoqqof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtshnwliyf.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtlrvxhyjb.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtnqhtegic.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtgvztaoka.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtwogrpcfg.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtugmbpece.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtzdokzunm.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gttqdmwqem.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtyvocgctw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtawxsrsoz.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtjemlnybj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtyxyihsfx.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtjajxaojz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtbwhnkwqp.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjjhwonw.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtiswvqgjc.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtdfrdjzrm.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtqgbjmsjr.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtbfjzcaxd.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtepndavyu.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtxkjvhjow.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxmjtlua.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtaagquobu.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtpgtptqfd.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtrajcayum.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtpfozsilp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtobtbqkfu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtzeeyrwal.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtswvdyojb.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtgffzbeps.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtjnjlxzrw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtydwwzomz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtnrqdrevp.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtcvktjgtq.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtedjtssoe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtzzrunjxg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtyqwuejbj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtbummbcdd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtpccubhrg.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gthyacppvb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtlhhetyty.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdvijtbn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtkgxeewem.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gteipumhyh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtlophybax.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtkumfherr.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtyuzelfeh.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjsumnzyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtikrqjgnl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssghfhgd.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gthownaypk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtvqjxermt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxcbniqjw.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtymentqmd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgeydudeo.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtflkkrxmd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gtqpqxmclm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gteujtoqny.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtjtrxtafg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvlrfybwe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtddulymhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtynwruzqs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtmvfuzmah.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtwmlervlf.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtnumytlca.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtexfdujef.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtspqdtqky.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtqxoqxqzi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtoxvbhgmw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtmiwzljmo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtcshexukn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtnfrybeox.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gteeaslbaa.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtntwjhhjc.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtmvqogexv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtitgmfscv.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtnpwcvzbh.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtqahpyfde.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtvbbnygxa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtyvqexbjd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtymkroiuk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtefizjhoj.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtecpcigsw.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtfkamzufh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtzdxaaaxg.html

JS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtkauqhvka.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtxuluyacz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtyaetapzx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbfgytlv.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtwlijulwx.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtdfruqfke.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtkjydlgpt.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtfmjaeozv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtshqxgugj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtykqezoos.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtqqzsptup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gthzhidhoh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtqckngeki.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtanesbefg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxpatqlhc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtulmpfiqu.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtpxuzlyuh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtaldbqkar.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtlygzusmy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtzlhzbpih.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtzkjqwtai.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtprncmbtn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtvgvgrsrm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gtrsdruxhq.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtagbgmejg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtgzvubhlk.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtjhspzqxs.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtbtcbzkew.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtufqswnyp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtvifcxyfw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtbajnhezo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gtfudskouz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtcoxmecyn.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtsmygsksn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkdpenyh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gthiygajqb.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnkarnov.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtqxyuakrv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtdslbzryj.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtfyiyyvya.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtjfpgfbps.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtcjsayjys.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtjkmkhudf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtmoklfekv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtogfzozwl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtzhkabowu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtnadhbcsh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtdiyvgtxu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtxcyznetp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gteeyzokue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtxycrmvlk.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtnustrzqj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtovxjhfuu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtucwkogks.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtygvdnnay.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtzdhprmcr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gteqoiycug.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzytcvrx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gteugtiult.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtnheyfaei.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbjiimjzn.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtfibusozn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkezlpvg.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtxdnolbqb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtgglmgeso.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtcordkezy.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgtxmztkk.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtogiuuxwz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtrqvyfupj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxefrdwzz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtifsvtarz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtgxrhxliu.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtiiybzzbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtxgchcnnz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtixngcwys.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtkriwro.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtfrdvcuyp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtogtznkmo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtipwnqiuh.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtfmivpbri.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gtvgpflahs.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtfjddyevj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtxfhfvlhx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtezaxqerv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkuovssn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtvvrwiwaj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtjxacieev.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpscutak.html


<!-- 参考信息 -->