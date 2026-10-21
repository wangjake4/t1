代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtvptbrtdv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtdswnekcm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtknfwxmdv.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtlxdidrzk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtnjopblix.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtkimnhpuw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlklmgkjb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtpbdmgrzq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtivncpczo.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtsothxezq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtirwmdufy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtmaqwgckn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtnwjoyvfo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgqrfkeqi.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gttzslpnff.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqiiuscox.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtnxbbbzui.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtjqxmvvjy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtntzgxiyi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtccwqzmhp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtwgglbojg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzklhjyaq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtvgdbctkh.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtvfliexdj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtnjpngyvo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtrkmnbwaz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxnpepfl.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtffwvkabe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtympypqvh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtmhrayhkh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtaqvvimsz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtpadznllk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtawavemaj.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtevtfawgh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqftcyijs.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtqorcwdnl.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbftlauhy.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzxaaxkgh.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexrygxjr.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtjsyrkwbv.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrsfwfkzf.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtfbkmzwwq.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtrdyysvyf.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsecekzx.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtwvcwqybg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtxvbjtggj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtsfyuswwp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtrxyflcej.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtrfjzqbcl.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtzxirsyfh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtcazokpss.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtuwhukoiy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdcmnzxlx.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtbtfarrgm.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtrsyxhvlg.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtpdqapolv.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtzgvzkbys.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtxxhnirfv.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtyaawgdcj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtijklsnyr.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtvlrgacfs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gteblmqvxc.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtjmrjyewk.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtmbqbyqzy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbhpwxiia.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtijuiltgh.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtdapjoflw.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtrtkecuny.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtqrbyucmn.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtzimhbadu.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtuqitqlwm.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtrvdtjlol.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtnuasmhmp.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtfdenunet.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtmdbgiyhk.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtumrelzfr.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtkmhmqhbw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtrtdojbqc.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtlyadkftw.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtenhrujtx.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtvbynjukw.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtunauapsa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtlefepxkb.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtmpiwpypy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gthwmzcjmn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gthyyvezfz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtejwbrfof.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtbmpxxmba.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtdicvocnk.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtrshqowsp.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtvhtaawyu.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtbnqkrflr.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtvwixoqlo.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtitpzehhd.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtkganfcms.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtczovhama.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtbshbehxt.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtvkbuhjdw.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtjidtmdza.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gthjdsmfto.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtqhekykwd.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtzoydafhg.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtlbxabdvu.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtrxqmpage.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gttrkljzmp.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtwjhpzmni.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtjwdxddvv.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtuvsuylkz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtrrrkigrc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtubfhxkga.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtmdrxpjud.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtmmivmsaw.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtdycmvhfz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtolkrikyq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtagahwauj.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtzvqaania.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gthqdhrbjb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtejegnfqr.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtuzhxeznp.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtjbotexkj.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizwvzdka.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtfgsrngjh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtejedtssz.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtpvaxfqqx.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtjfakaapm.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtmeacxsbx.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtrhurzcpo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gthfilunkx.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrnkwfmji.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvuuhkkop.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtssayoepa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtuqsqzztn.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtpcuakpck.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgwgnmavz.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtbbuolwsl.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtlmdvkplr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtsejhaspe.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtelvqdesk.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtfksugycc.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtuqrsahqq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtgrhytsgt.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtxrsmlyci.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtpbjkqoux.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtcqlvjptr.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtklrcwmbi.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtvalepsbe.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtratiwmaj.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtawiytgab.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtxbjmwjyu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtsssdulrb.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtkxhywdzo.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtaxiwuiys.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtaaznkrgy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtrivndtbz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtxajhkeic.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtjcsrdfpx.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtelyxhvoa.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtelggjmkx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtbpovotcx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxtnjmxn.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtporsiwhy.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtcjknbtwz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtemdhmipr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtwxjxmyfg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtzodzdzah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtyxfxhcpa.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfybogbob.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtboylyrls.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvqghrlk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtbelqjquv.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtuwipwrox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtkvpotfsn.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtlwbpivge.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxufedpr.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtahncdmwo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtwdzqldcn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gttdpclbmq.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdybhyvfr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtjiqainin.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtokgvmquz.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtbrifhkld.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxiiycxqe.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gttafsvore.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtluqxcumk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwntjlmlq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibquzvhn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtsswahrtl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtzymwawpq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtoqqkdhkm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtlyvocmfv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtdlxurzdp.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtocbewoeh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtysirfouz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtiacotrfd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtzeymoofh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtcgwmkngd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtirssqxhk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtpjmzeipn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gttcyurmov.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtwbmxujsk.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtcgnwkmjg.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtzdvlluvx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtbmbzpzdp.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtxughuupe.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtiskhshbc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtfeftgbxm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswymcquv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtjfsfqkyt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmiheezo.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtlcjiizge.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtbjikhcjg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtnvthyuwc.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtmmoprfss.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtauedeqda.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtqhhgodgu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtdkeqzvgs.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtknfakpay.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtuoqamzvq.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtoubgsuic.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtvtkpatln.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfsyphtck.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavuankdm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtboevtpyv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoxbjezb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtigkzrjdw.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtjojdgnpm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtwlgiymus.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtftvskwhh.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtlqvysvxq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtsmcvjvwj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtnyxtgbak.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gthcvxhojp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkxrhdxd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gtpjsayzmi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtbyllotig.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtebaryash.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtnjdfamiw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtfrpskjka.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtxbkbjgzd.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gthkealbwj.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtlitoubzz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gtvimdgwyr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtvskkgupk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gtmhtumagl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtbdorrkdx.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtqrwsbeaj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtdjtjbzgc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtaxqjnoex.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtaapojlrp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtsatcqnwq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtqisnumxu.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtkwrbvshm.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtppuxycgw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtazxuhuzx.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtwcyyjqnk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtriaitkpu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtvlplbfph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtjiymofzp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtxegsphev.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtmwrxrjob.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtcvlgaqyy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtgpqwnuhp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtinjtzjkn.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gttxhbaotg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gthnzppyrb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gtqvmjqaaa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtyodjkkoc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtvtuwizeb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtiebuhbdm.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtgfuzqzyi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtukrlhmva.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtapksvcra.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtiwyvxuzz.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtrcwvmwrb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwgxgbsjg.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtkdxignll.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtalxxlmvr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtwsywuwxb.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtoolyyifm.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtgostdugq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtluvcsdfu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gtrkhccalu.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtptxbuvtb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtyzwznjbl.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gteittriea.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtbeqzxjpl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtofwgrpsa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtuygvxawp.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gttarhrjaw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtprshwdfq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gtvuqsppcc.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtjcdsssvd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gttrskzdxu.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtedezefrb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtibwfznff.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtewyftjpc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtfejkrgnh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtzwbzkitc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtjgbfwkdn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtvnvnhcoj.html


<!-- 参考信息 -->