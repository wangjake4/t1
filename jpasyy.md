代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtafgqyyvk.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmdweevuz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtackzvrre.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrcjuzeel.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvodgoaoo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdghjzubz.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtfhbzogfl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtnnscamqg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtfkvstedn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpnxisgql.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gttfelihin.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gttvnbpiac.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtjohpvden.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtbaoqigcz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtfwksqayq.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtnznvnxob.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtortezxei.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gttcdeesce.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtzzvkalim.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhumvrzk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtoihjdwlw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtgzfycvsq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtirquqgsv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtgaadchzr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkpiyquyr.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtyafvkmmh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkzlyiase.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtzomhjwdd.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtrzyigzyh.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gttzdlybhp.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhjbphor.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtiysqcres.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpbwonqao.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtmekimkem.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtgsqxfrjn.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtexohgisp.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtiqeaktuy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtxzvkiltj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gttalqwpax.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaquzroxc.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtbmhwncfu.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtvqasourp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtjhxihhgg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtjakromdp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtrbalkpkz.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtvyrzhigp.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtmkjbbrnn.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtnmalvffy.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtphxybsmg.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtzkxczbfq.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtuumjrnwl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtrkomnkrv.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzndopuwd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtsptlckzf.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtnsgjniad.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gteudgyjiy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtdmcscqwh.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtpwsyazay.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtrvsetgvr.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfamgeffn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gttlxuhnel.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtsireqyjj.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtwqmseafi.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtbtjoqdal.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtwjxfvwhf.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwabmvqx.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqrawismo.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtvbgjakli.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtapyfvxzp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gttvntfkgf.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtandcjmdu.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtkugsfvzz.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtvlkkmyfm.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtxyetmuel.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjylxfxvm.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkhaxztbz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtbuiouuxn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtckyvzvsw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtdfmgdxwr.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtmxixngmt.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtezjfblnj.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtqqemkzfb.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtzaohcgcb.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gthxjcayhx.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtxbjtwcao.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtxcjysvue.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtotavttya.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtuqsskzkj.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtedvehifh.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtobwkdnmr.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtyjxczdpd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtxxqxbept.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtdaazlaoo.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtwtxyygno.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtqhkdgkbx.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtqffwwcvn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtzvnipxme.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtdmjxvhvn.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtxvbvparh.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtyhzfgxcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtkxpnsgqq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtfdnmnxha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtzimsipce.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtulsccksq.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtgmiuhfgz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gthbrvhwfl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtbwxubskx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtghuhlvon.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtupmldzea.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcxkvxkf.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtoezsnodz.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtjyixmawc.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqykdleds.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtqhjfnmby.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtzpzbfvnn.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtlwyzjftq.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtbjispxap.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtxeezbxbe.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtfbxdjytq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtkugstfrs.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtckqhwhjh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtmjwwdnki.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlhpjfvfi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtbfbitjxw.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gttvowbuxo.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodjauscz.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtrrtjqmvx.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtmdgmrxfm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtcomqmohd.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtkephcjie.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtxfmgbbty.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtvmgszkft.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtmgauplhj.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtyslknkfp.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtejpsfcmo.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtzpnzwmsz.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtbjvdwoqc.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtxwdctxiu.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtboaxldvb.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtloyhstkk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gthqmnbcmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtbsxncrsw.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtkykdpuos.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gtkkohznkx.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtcvxpxamv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtdbxrnlpx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtxfvewfmp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gtqmwerwov.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtbbjvfhmz.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gthoiswpyy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtgtcugere.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtsxtchubw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtiniyerng.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtnzryyqrj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtpfuleqxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtknpftuzq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtcqqhcail.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtsgkomjtd.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gttxgdgpak.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkhtctgt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtecdzpeun.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtssdcgbfq.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtphizzuvn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtsqwbhssp.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtyrswgltq.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtbaceopfw.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtcioasjvq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtwkxtspuy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtdjqkdvdv.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqebygets.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtccpaxasb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnvivttjv.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtkpcpgppb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkljllypc.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtkdqlgidp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtpltgvbks.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtsftnwaiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtghzqlfba.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtuzsgvvui.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtkqdlrspu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxswwdxa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtcrkgrmzj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzhnvzym.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtsdphhzge.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtkepxqdog.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuzdjgmtx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtpshlukih.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtloicjyit.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtgqppmxvk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaozazil.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gthwqntvtv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtmunrsgyw.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtyusixyfs.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtsyfhibfq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gttqprboak.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtujpicthr.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtxmtjdhll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gthadptrwi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtajfxmmah.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtfvkcilpc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtqqkleeve.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwkthhgs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtpwngaqzw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtiikauvby.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtmtzjgywg.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtjhieupep.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtosruzzfr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtodeexeaw.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtawdcjhro.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gttvwisbcg.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtjlbmvvpv.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtnmjvorwq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtrmqlafaq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtvvfbotpq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtikcdhxla.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtpzkahcbg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqizbfzh.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtiemojcwf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtacdainiv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtqpssogyq.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtxhgshtkw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtozzswunu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtiilkakzs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtzginygbp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtdsvryhna.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtjtelsodk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gterkzwdaq.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtgjlgxlzj.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtqxotrngz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtxciilszp.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtwbuxvoay.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtlijpltyl.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtxacaqfpo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gtosfdqovj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtmkkmonnq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtdcisafza.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtgbiidhtt.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtqguerwbo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtoaiymrje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtmuygicrt.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtmqjjmrhc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtwubqvnut.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtpvmrwddr.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtvrxdskkp.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtgctdmmxd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gturffdewy.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtvjofshsf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gthfysvnfg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtzmpxzsbw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtpjjswzxk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtldsrcltv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gtfmxkkegy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gttkndvbml.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtbtuubqxb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtlvlickuh.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtpwtekxky.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gteptomjaa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgfcfgck.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtpafffkcd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtkrxjxuzw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtjrqinwzt.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtocpsehca.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtnwarhvum.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtqjlvmeet.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthijlyrgv.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtmhnunqhc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgczdiwve.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtseveqzum.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtprmbnzjj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtxdibuuiq.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqiixuvpz.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtaeuqlaml.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtjnfrpblb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtbvrayfsh.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtvztmlnul.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtemyxdhiy.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtbuydgseh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnymjqenn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtjufukzwr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtyaqeefac.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gtjollptkk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtgtbduids.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnltaffti.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtlogcpchh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtnhamnmtx.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehuiaohg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gtcsbkhekk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwhujkvv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtnjzgdnnx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtiihnicon.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtmugazygk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gtuzegsjsl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtizmhdazo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtwrbdhhvq.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtwlhjqoaf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtuwopykce.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtmwwhvlak.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtsebnczrd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtscwemvxa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtfahyuagb.html


<!-- 参考信息 -->