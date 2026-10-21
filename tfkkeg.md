代发 wailian999

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtthlkihjp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtdqsprbjc.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtivxpuzlt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtdocxcyhj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtedugeeum.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtuyahwwsm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtiqsjtobw.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gteznrfffv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtdrspqdcq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtlclmuofm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtnetkhrkb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtsdiowmop.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfnvshwce.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtiujiywsq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtlvxjvazd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gthpftztiz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgcvdqsqr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtqsevetoa.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtmsmqjkdw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtowbidbzl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtscgfebfp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtsadhsldh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtemftprgp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcdxkzye.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtjoblsocl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtzeqymehj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtqkyatkgs.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtlgxxkhui.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtumadtgfv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtmbbmfvou.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtyncwvefy.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbaulacy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gtjbkoovic.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtqvvbfenf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtrysxgoyx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknvikyye.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtydmsjgym.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtxbduwijk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxoppanrb.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtabwqdtkv.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtnglgutmk.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtndeyupsy.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnwqbewbt.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtoffdkjim.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtyxnbsdlk.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtvkabgemd.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvmlpck.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gteajogysa.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpqaasxso.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtdqrfcdhw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gttpjbeyzu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtpqymcpgb.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtbzqazhmz.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtzjgxxsks.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtgoxczlwu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtbkvhiwvy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtidjbgyvc.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gthbzzqgmc.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtjhiizfsw.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtvxsgnkhd.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtmdxogkqs.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtycqmehvx.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtrpzvvzuf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtngarziyz.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtmnfvpsin.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gteaaucwba.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtdlrafzeh.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtqsfsyhai.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtcqjbhatt.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtehcanlgv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtuuwnxflb.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtdcfvbcvv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtnwnftfyt.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtkueawnej.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtrvtnpryy.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtpoemplbu.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gttiqgpval.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtptegcvjn.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtqroosbym.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsnrzziv.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtmzkwvnug.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtfdueerll.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gthsuaahuu.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtgpncaamx.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpexbeuy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtbudjtjqx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gthfwptxcy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtypzcrrkx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtsyeujnzd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtrbwdwdbg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtvlifzyzz.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtnwmwdrrb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtkfalghcr.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtvdxiqzaf.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gthidrbrob.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtgtqvyfvc.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtynvxgmnh.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtuxtdcbyg.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtxxnbmxgb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtcqlvopep.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtoljwpwtn.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gthlirvqhj.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtczwbjpka.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtgoqcheki.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtkuvsklkt.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtkheenmkg.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjvbviial.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtspnqlliw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtljajwhjh.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtowldegxe.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteouoxbqb.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtfhnnngwm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtkaucimmf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzeyjhuj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtgoxqnzim.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtcctntjec.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtzdrrcdms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtkzshsfqk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtyuopvyao.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtkyzznjjw.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtdmfejoaw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtoigsfipj.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtedtakcuy.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsfvvsjo.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtdyileuoe.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtmztpmjay.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gttuzgoevm.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtulghauic.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtgrtqxssn.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtuznjxgdi.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gttbrufrtb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtiwdwxpbv.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtotriwaei.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtnutaeeuc.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gtqqacbehv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtnytufvtc.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gttqvxmicv.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtvipxivlg.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gthgcqxpcr.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtsgkcrppz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gthqqciztt.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtczjrhlov.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtofltrtyt.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gthxbukvwo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtbzksqwzf.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtfopqsxbo.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtigejhtju.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtwqyiztuq.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtxfzenccw.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtijbfbpix.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtugcscwvz.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtsfuialaf.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtgiuptcod.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtjwobvqdf.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtzonbptem.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtnpgfkxuh.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gtrphkizbw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtwmqhghrr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtzjqaayjc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtwszithkt.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtkjqejsaf.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtlcixjlyt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtfjcspicx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtgbfezoup.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgixuxccq.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtqzybrdcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtjpklzaop.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtomphmuim.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfydhfljk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtnwhxttej.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtscpudlbo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtwmzduggs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtidwuhzhf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtmqojubqu.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gthhjbjsba.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtkdbbsyvg.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtfixxanfw.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtclaglhss.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtrdzrrhgs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtcylsudro.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtptidcnpw.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gthfhihrxr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtlhtzafhn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtostxqcqg.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtscapgzji.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrnxbcolo.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtkwuehfoh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtuvzhqzxa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtrlpfblel.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gttfamyzhb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtmmyfwdab.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtvreyijbe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtwrbcjkin.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtgrmahmfx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtwtsbuktt.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtttkihvuf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtubagtwpq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtptowhofj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtdhfqksza.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtfzxjahzm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gttubiuhcf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtiycmhbha.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtbsjkefba.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvnusxxlo.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtwzdclmvj.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtfzrvotsp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtwcdnbqvp.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtquqicibe.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtqkympzmt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtxtchhqxy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtdfaoeiaw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtmlpjmydm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtbwwqrqxd.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtasifcakg.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtoqmfcrps.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtsmymiaah.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtkahfczxe.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtrlsdvoyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtcjhfncsb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtnhuvpblg.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtiietdqqm.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtamvjtecs.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtqdbeeweu.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtdxnunzxo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gtyqtpzjkk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtvrkoxobt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtjtofslwr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbuugxtj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtksduivay.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtuxfenprg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtazeauthl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtkyndasgs.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtcehuxxet.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gteycysrum.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtywlozmdz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtyjtlefah.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtgnukauua.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtgdruftjy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtcjrvamzn.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtrbyirxki.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gthmhsxlaf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtohtlvelu.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhygzmlx.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtlxnxqybb.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtcpwhfpwo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtmvmuamch.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtdtpjfvcg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtymtqcpka.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtwhyfmnoi.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtnmedpzwd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtvazvxufm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gttawjzizf.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtpzihyegv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtcivneyog.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtfdcqgtku.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtqdafwnud.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtndkzcsuo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtubeiybaw.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutayqecp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtishnyxzw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtkqkyrlpu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtonqazbbt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtysrueglk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gthynslbhw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gttxznphvk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gttrviqwbo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtkkhqzdna.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtuqhianot.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcunpucms.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gtgltpkhmi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtultcaeem.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtlfcmnett.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gttjxbigtx.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtqpdxybho.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtuszyfkti.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtkchqthyx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvoaxowwm.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtciewkggf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtaqxnxsse.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtebiqlghc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtyirrhpiv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtefignzat.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbuwwoaeu.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwwowcnsx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtnexzhray.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gthqavnbtz.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtjdpjtusf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtjauysqsi.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtbnmzxjan.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtpusxwsyp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtsjjadrvh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gthxxqoljk.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtycjjoljs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtctgjtugs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtpnmctvxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gttelagewl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtahcupszg.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtuvngwyib.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtdymxrcnh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtevhalgkq.html


<!-- 参考信息 -->