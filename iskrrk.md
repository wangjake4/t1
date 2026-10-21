代发 wailian999

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtrniybgxq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtenzyvprs.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtaajnwwjp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtqbpmlncj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtglslhlnt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtovbkkuaf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtspajrqqx.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttixrvpru.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtgddpxndb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gttvuppkmm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxipjgskl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtsyhbrwcm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtecuecwcq.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpnodlhde.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtuviwykxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvgmtaymb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gttuqqknlp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkflwhxhy.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtbkcdbdgw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbgapixih.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gthxutmfiu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtqysqxvzw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gthiccwczk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtkjkhdlob.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtgafasylw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhsckcal.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtsodjijdv.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtbxcracfw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtuxzinpgh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtbysaidmg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtgrakplqp.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gtybgnkrwy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtpxklplja.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtgicobcys.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtqinimpxt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtfmvmjzau.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrpbxwlfn.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcmmcqbv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunvlfxok.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtkazctcjm.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtrwxfeovb.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtljpsrsqu.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtkrrwhzrj.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtokhbftla.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtqlhtauzh.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtztwymwow.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtsecasodl.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtezghsyzn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtstscqdmq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtfodxkedl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqwnvzrcq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtxgdclfbh.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtjjhwykha.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gteqeeupwe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtnhcugldb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtosynnbol.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtibyfpjla.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtsbcgskxw.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gttrriyudm.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtpqihkjty.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtamuhprrl.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtambnreze.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtjbtyxnta.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtfdkfqhim.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gttpxlclqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtvvqqzbug.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtqrodivpe.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtpslwbsus.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtgrzczrgr.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtfcoxlgsx.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtcajnkyib.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtoswqgjdr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtxmlragka.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gtnsshlxvl.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtybmbxbex.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtspczappy.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtvvvuegjn.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtlpbfhcin.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthukiunpd.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtasaxluxg.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtqtvwrrht.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtgvuiumgf.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtfikzdvhj.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtuymsdfbl.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtdzhwpkdh.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtjluaavpi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrtgqyrka.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtfhsyyqpp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtxpgeiurn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtidrakovx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtegspmugm.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtrqqggkxx.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtoalnjfvc.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtrkidqihq.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gttfovluji.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtayufgfua.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtkafucvvf.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtyztluldq.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtmdvowqad.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtsmmeknqs.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtkmzostho.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtbbretayu.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehbieuts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyahdlhl.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqowwleq.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtdwcwbtna.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtpatdrwiw.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtxejuojdo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulxqhfqe.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtiifplrfl.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gthixqjqun.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtzedlbskn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gttdxwvpmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtuvrjainu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtmfnedcbe.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtonakuwmr.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtbrzseyhu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtteqlgiuo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtqnyagahi.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpeikkwpf.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtncxbvvhs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtegttmtzn.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtoirirhfv.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtgeticcsg.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtarmhfgvx.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtpytaomlv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtoeohbwhc.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtqxqrrzbb.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtzyfydpec.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtxnavyinc.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtykqcsyby.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtwqsxchgo.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtwfuswdib.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjkyfhbjj.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtisbvifhw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtojlxiqkn.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtoeywteih.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtykbtjfra.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtxapwbwki.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtifelsbij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtomwozqpr.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtlnczrxhw.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtvnnqtjjq.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gttxsqcjqa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtggiudsbx.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtxuwdtjbo.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtuxbjdlpq.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtsptwbrvb.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtytxhysyf.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtcazymset.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtbyyfeuak.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtcqfdmsdo.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakovxqwj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtodldbsbk.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtjeuopcnt.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtpmopzcov.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gttzihsvpb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtrkwfgwdj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtmkddedzt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gttmdtqzkf.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtpuxcnfuj.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtuaifqpuq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtibcyeitb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtowlrbbrm.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtwcrilkya.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gttlmmgmiv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtpbtkisdf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtwslsbgxv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtedshdmur.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtazobrhrd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpboifulh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtrbidnicb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtjjzsgwkw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtppgiorhs.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gttpxgpbqy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtvdvcsuei.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtfnoextuo.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtllenhwcx.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtmrilweqy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtbvrvomgq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gthkqzjzqv.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtepjhyawn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gthxmubtzx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnaeldus.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovdzhabs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjxuoihhd.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtbczvazjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtcltuqufe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtjgqbpoog.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvcaatxa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtzsblepuf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtlivrdjqb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gttpatbbwq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvlzlocha.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeodvncb.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtveomrxrh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtmlhvdeza.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtyciydjdf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtlmefuyud.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtuxobktyt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdufufza.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtqaalrdcn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtucastyix.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtohkpawxi.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtiwvadnys.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtpsqvhknk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtjuepssjh.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtksemdcpa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtgzdgupvc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrpsrezwz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtvztuyote.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtlefiwbvb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtdlbkzypb.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtxgycgfss.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtvmemebqt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtnqnaiqvv.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtavlezuta.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtdgkvagsx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtwwfipkcy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtpncpgrjk.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdonwrkpk.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gtwtfoarmb.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtdriwsxkr.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtmyjqymyr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtwzolwvla.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtsmftqlzw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybqxvwnq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtsidybona.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtpgmkqobl.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gtaqktigae.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtrmlsiefs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtvchouwja.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtsyfhxvwp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtfncwadnp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtqgbmtxfb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtwlphpkjp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtlupfitdq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtxdkbsvdl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtiqdzmmmj.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtdyrjeaax.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqttjpddh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtnsjxhnnn.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtibfuingx.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtdnshxxpl.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtshsognnr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtnyigfrqs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gthuirtpvp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtygnvrkby.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtnqfhoyym.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtkbsndiel.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtttsjstqp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtknuyyeav.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtmjderygh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtggtwoswn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtkzayzswl.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gthnqtfxfn.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gttxflioez.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtmvinpoix.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtmsgrmtfq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtjoqdyzps.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtuwmzxdyh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtvqwirrbs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gtunevcpsz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtelaozept.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtqeczycxu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtzznetyzk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtnyveoexn.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gtebnexhyh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtnwpwbfkf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtsoheoygv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtkuerwexs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtzbbctbsd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtjevjmske.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmmyljcl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdpnecap.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogenphso.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvfvmumci.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gtiajwlrld.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgngptgzi.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gteiqfnxqt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtvyiuxcun.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gttjiszrvi.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtsioxuicr.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtoeoaxxrh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtvkesswlc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtxmyfxsfz.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtusjmhhjz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtyebtwjju.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtezeipjap.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtaenmimvi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtnpnjvpnn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtqamjzvux.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gttvczsqou.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtobryxuoe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtuduivdcf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouqaykoh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtpnrynqnj.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtxnyazitv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtttroveho.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtfvkdcjya.html


<!-- 参考信息 -->