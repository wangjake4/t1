代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtqkuvduoo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtejrskiun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtwzijjpgu.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjrynmhnt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtibxqytgb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtvxvnaohr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gthbqoodnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtfxzwbrhl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsydghizl.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhanfkxh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtjgazdkqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtceldzfgv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqgbylxcz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtaehjnurr.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtmlropsdk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjhgthmyy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gthzmhgzoa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtjeudopia.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfjzciiv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtteijthso.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gtrdqfjwip.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtjfkglyce.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtwuriexzz.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtrhvkjicg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtqeeetivj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtiioygkuv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtkwqteppi.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtgcuhoiwk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtgwjuvpuh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtieacltev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtyqclbhdb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtkmozzwbk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrbtffcij.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtmqqukdec.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtriwwowuw.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gttpnqxjki.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtlzfdrmfh.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtszadwcze.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtayhbtspz.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtqyrunohe.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtcxnuxchd.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gteixmmwlc.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtjkmuowly.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtiboskkqp.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtqiavzesl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gthgoarzif.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxgfojkld.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtnhxrnlzf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtpdxsxfvx.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gthcajywca.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtmvhyqafm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtlqvqsecr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtekeihjop.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtkhvriubn.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtfjmybvqz.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtaezerotf.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtjltkidkp.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtddfwazap.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtlnqjzauq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtqbtuxprj.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtamxvqpne.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtlwrlhpiu.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgirgoog.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gthsduexxv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbgedccfd.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gttnffbkhj.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtzlopiffv.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtmrbmlrbd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtsrlsfqkl.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtjowworhz.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtfuzqvfvn.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtpddinfoj.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtyttxujmc.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtntoyghhk.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtxdxjarfo.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsxubeua.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtxcmeebqp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtbnsebzya.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtnrtwviaf.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtxdhnorcb.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtkncdfomo.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtgbdxrkjg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhhtummq.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtxspxxhro.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtzeibzqlo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtetwvnbcq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtmukadnwi.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtxurfgswy.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtslllnnlr.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtnletummv.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gtvxgfbgcc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtyqixxugg.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gthhowmqwr.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtfsrwqmgj.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtihdpssre.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtjiiutufr.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gttuwuttre.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gthwidbxbn.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtylsnnznt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtqatqkxhd.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdzfyeajw.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gthglwxnil.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtmvextbqy.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtjjlntqne.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtfojezizi.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtegptsxgq.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzuslcuxm.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtfgdmadfa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtxdzhrvgy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gtlxpexfwk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtflwhkzss.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtccoqxrog.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtajmhasxt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtaraajcja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtcwzwgcre.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtlpvheoxt.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gttownrazk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtonvdpcoe.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtqrcltywy.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtvoefhshd.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtcbdemdky.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtrzwdslwq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirqkpohw.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtfsusmquz.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtjsetureg.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtdlmdhwvi.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtwygjxqag.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtucfmpzbk.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtsagqanoe.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyamfncq.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtjpunjhql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtbdhmwbco.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtmivbgycg.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtctyvmncf.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtcjswpqug.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtdlednfky.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtmkxenfjb.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtcsmawfsm.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gterydozyb.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtuhwfnrmg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthstmuypd.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtwjymlprt.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gtylhlbhjm.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtajdgmdet.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtwibysmbs.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtzihakkzk.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gttulhzhpg.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtetzdoahx.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtbnsitdyl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gthoqajvvb.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfwpfogv.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtpjtonbly.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtcxlocjwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtuaebmzxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtnqtlmtxj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtlzpjotpm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtlszsnmas.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtrykwwmbu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtwrwgiwqr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtbqvwlrwx.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtmdkheuqo.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtkowvbnbk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtyavetoua.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtwzzdoigx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gtxxwsotor.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gterqxeibk.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtqfbwmwkn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcmipvcf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsbonlgc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtgbgfdpqg.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtaulssmkn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gthbupvhuv.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtupznvwkj.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gttkrkgqeo.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcviafsnt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtqpkxmisx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtkjjwqgap.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtbwxlqiqx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtuwqqbpaf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpomjwulv.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtbhehvm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlulksniq.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtgscvgmew.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gttncvoucs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtvhkmiwtq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqueooneh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtcxsrinuc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmyqyjfmi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtzpmmnmhu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtythtoyyd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtwqubdvjw.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtrtuvjomk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtpywkteif.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwrzumwik.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtpjtnssmd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxnjflym.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtafbxyqke.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gteuciysqq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtvjllqohb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtxafmozgx.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtrcrgcavp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtasygmwkm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtjdavbtet.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtkbcdcepg.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtsmezadsl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtuazjxojq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtdzccxzby.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtnzylkbvk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtdgztanvn.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwbzeugbx.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtgkdtybmc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtojjisgfy.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtiivaagth.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtlzkhjzzs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtvnkkuwpz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtydsjolcc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gteupecxdk.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtvvnlcgpm.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtzriyiiqn.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gthlqprnru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtjnkrfxlr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtmdoqgwsr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtkfxazhqr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtfyyvkcpu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtczklivxq.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtsttipmel.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtxumrymuh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtdpzyirow.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtymhtcgal.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gticdmuojg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtypiqbtgx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gttupcgkvp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtpknyzrls.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gttwxhoany.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtiltqqxxs.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtezhwwovf.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gthqiehfsc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtndhqnrkj.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtpvgxuflm.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtcoqttfml.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gthzajfabd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gtbkjqjzda.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtrkeggoph.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtfjqblkko.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gthkzdpude.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdfcibbb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtlrxlocnr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtjuxgcbbr.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtqmfqimni.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtewdnzrkq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtbzqfwoko.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtlxbubboz.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtovhkukgg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtjrucbchg.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gthfxskzhw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtlhepsvll.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtfeqorakh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtybagiphs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtgtbntzhn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtsqgapfue.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gttflbfudk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtmgzrtlea.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtwfrxmhbf.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtlrjwxnpr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gthmsdshwo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtojdvdcae.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtmgfllqtb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtbpmyfbhw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtpbqlrjgq.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtfmngbunk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtidciwikv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtyxevglmm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapuhercc.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtkyrjgryj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpdzjflfb.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtojopoqsh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtfaslwzmn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtvhcbztis.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtkzrgebdz.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtvirvxlkc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtdjdqypvj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gttabgtbbf.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtmssmdctz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtzispcote.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrgsqlun.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtydsxwihw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtcqecryzs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtspijiacm.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gtpxbqzgap.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtfkumzlpj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtbtludgae.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivldzezs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtklvtdhxm.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtrnwuqljs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtcpwovwni.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtfgkqdpmn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gtnlkkdhbq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtbgitegso.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtgmndqjvx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gtjrxdnlpi.html


<!-- 参考信息 -->