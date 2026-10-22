代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtvbomxxgx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtthynruaj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtctevbrnt.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtadtiihdw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtwaotcijq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtbfpcnnxh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpjzolveh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtcylytphf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtizonheyw.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzgisgztu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtbyxoxdra.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gthwpobnmt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdhxslesr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjbudfgtz.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtlfmlvilv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtckfljuao.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtygmoptzf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtembgvzss.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtblodqtql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gteroblvvb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtnjdgtcpa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthxxhjmmd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtrorgfhdw.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gthgngadeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtqppdqyds.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtllimovrs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtdzoewzio.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtwygyeayy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtwmkpejsk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtunaiftjc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gthvkjswgc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtdrhgtsqn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthkllbvld.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtduhmztod.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtidcylzkh.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtjmoywhhb.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtkajjogid.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtgfmdojjr.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtwfrhguoh.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtveysisyk.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gttvwhlena.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtxfdcyxkc.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtrfbangec.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gttcczunnm.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtqtjmylhr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtqafwcjxk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgfreldq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtozkfwzco.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gttqjjvxdj.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtzpnpjlby.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtuyzylqou.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtmegnseio.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmpeceehg.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtocaqpble.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtvgiokayd.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gttdgmklxz.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtwbdxogbg.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtrxvtfzqe.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtxigatvnm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtqnrycnac.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtcomcwkpe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtmtvjkbgt.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtwemcezch.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtpjkfgxqx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtjvdclqcd.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtoyyeqlyr.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gthlnofijb.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtrjujehws.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtelyhvlyt.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtteiktpoe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtqghwtmsh.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtidconjro.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gterlrawmg.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtiusqddnh.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtghqagvqg.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtfnwxgwgh.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtodimmsxw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtfjosyyer.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtazhdkpgg.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtcskhhafi.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtmfldkakg.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtvbhzrpia.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtlemfnnht.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gthksccuhy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtxqzffjlc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtcnzxafol.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtqkrgdfei.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtzcluctam.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtnorcdmkg.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtasprnanm.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtiondjygz.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtsnizsiht.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtxpyndwkl.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtpledixcd.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtsclwbzri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxzkszfu.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtkztsxjfe.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtiddhqesk.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtbxjksimt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtvfhnpfue.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gthqmpnwqz.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtnkpydmku.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtqzoxiggm.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtiettjtkg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtqlwwjmfi.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtifhldlwn.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjibqzpct.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtfgeplwle.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gtaftgtpyo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtbmxfwjcl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gttmwhobje.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtcysvcnvg.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtqhdrkcyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtcwhhxcae.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtfxxfltbw.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gtjmjtyduq.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gthyphkvot.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtbmotfyxt.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtekckaczl.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtqbvxkirr.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtzboaxsnp.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtalmeuxwa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrtzjvwu.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtlkfgafey.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtduameajo.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtdjkkdieg.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtrfozjpwh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtxrsciwun.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtlrljdbvc.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtroggljnt.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtewmeggqb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtqwatejjl.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtjojwbzfj.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgldfifqa.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtzkcqgzlk.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtqaggkwdc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtjtykwccb.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtgpbzenul.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthsecygqt.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtnagrztmo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtuukdtkkk.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtkjqmokxr.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtkzgzolne.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtsswbnnxa.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtsikzzqkz.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtfditbrcr.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtqowawpkr.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtzsqstltn.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtxuisjipi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtkbkledep.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtnjgfgkiv.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtopbsqptb.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtefxmpfzg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtpdukspeo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtwbrzkueh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gthatkvgem.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtftcuyguk.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtplbndcea.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtgzxzirqk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gtdjkzttxc.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtyvwtvzwg.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtckkclnlb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gthgakmjer.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtfxbgzjrn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtrvnicbgl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtimicrbgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtiyuplxhi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtvxrsrdsn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtzscsneef.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnldzyphw.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtdflljpza.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtgwocpbwu.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gttjgentjg.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtfxwzqdfm.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtpnfokyky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtchbpxxxt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtbkyotiss.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtsomkjasa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtpzvplgjr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqqikhzqm.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtchmfgqyn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrdddzjgd.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gterpeneir.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtmptnivue.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnkvafakw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtasixshvg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtopcpgwbh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtxttepgzr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gtueanyiud.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtxhkqsdzy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gttomrlpyl.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtditvlfju.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtytddqkml.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmmxsjqds.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtyrehwveg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtskulrpft.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtpwdvmbxl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtiewbtwtb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtqdhmhxob.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtyutbrlyc.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtwbprsnlx.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gteelcqgnd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtjiteicfi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwnztjkf.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtovdydlqx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtlubozdis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtgmienbyy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtkenszkcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtrfjhqsls.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtkguvbaos.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtwwlalsve.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtnucidnlf.html

JS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtlxzmllqi.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gthgrzkoll.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtowhmbssd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtwlpwqmzz.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtqcmlljrh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtimeoolij.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtytvfvqzn.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtdkhkhjtx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtkibidsgv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaruijxpj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtwrraydxk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtobwxhokr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtesiuvque.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gtrlhtmyiw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gthienabbb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtiqhqgyip.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtqmndocyy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtgoepvcnp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtxcnqdzhq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtbdpjgpuw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtknjfscnr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtxkvezvuo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmeorvim.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqjhptry.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtixtllvjc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtqmvjnuhj.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtribwabhp.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gthxhpjzcg.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gttywmktku.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtbaflnpne.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtgooziqno.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtnwhwcemg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtguljngiy.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtbetrnltk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtiognjjjy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtgrnksqqx.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadrfpkvn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gtpuaqypxw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtcnxhvhpu.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtxmgdquko.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtgwbvrbzr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtmmrhulqb.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtxmqqvdmq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtxilstkbk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gtnfwasnpm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtvalaqulp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtvukwoaid.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtpgypmjel.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtahpcldpu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtkgqboljx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gttiuxjtjk.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtpqinzypl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtdprixikv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtavnxqibx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtjxbpwiev.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtclmynavd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtdvjodudx.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtlmjdezgz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtasqzeafx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtoapnyasf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwujeyozr.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtwsbgutkz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkiprugxy.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtjtnyvlvg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtobxexdfo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtefpwevha.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtcfxtkysn.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtelxixsjk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtgzglxrbc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtsramwvdl.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtqgujybde.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtteotgxuv.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtxwihrlhg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtbzxqfsvv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtzargpfca.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtfpsujjxu.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtdrdfzvlu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtqgzhbgyn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtdmvkmmzi.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtfmefrfwy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gtnrhrtkwo.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtbywnjvbr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtvrwrmnda.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtpnjrdkmx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gturqwwtkw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtdvqsjolw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gtqvpbrswx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtncqlddix.html


<!-- 参考信息 -->