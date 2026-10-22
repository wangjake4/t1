代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2onwbkjgo.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2tyrdnkai.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2jjktvkpv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aypuydxy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2oxdjscnr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2cgvgavrv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2qxsabuvx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocxihzkv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gt2ijknkeus.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2iikoolzd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2oygynplk.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gt2nziivgsi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iegiizcq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2excznvis.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2jzeickrq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oaetknpx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfaowxuo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2rperhqdg.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2hztsqcaw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gt2iikcojgt.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gt2kffqpjns.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2hhrceqok.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2xobvwilu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2qzmtwjzz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2lwofkybt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2ntjcxtqu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdopunwt.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2qdhcepks.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vajybhff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gt2yenjallt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2enkorzcb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ompqqbbi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2keiwjskj.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2nszyvzce.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2nkqltttw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ifzlvbie.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nahvuehx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2hzwujhof.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2evrzmrxx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwsywlqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkppqdpb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2hmofkmqq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2tacwwocy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2xgiqnbut.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gt2xvdxxwjq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2kgzecgyq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gt2tgzgkpis.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2rlaengip.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gt2pqhmjplx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gt2xvhohtwh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gt2wmkaznrq.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2mpvajycy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2yzhupddu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gt2abuiwckv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gt2jesmaxqa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gt2ggikdprm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngiyhbql.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llipezak.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2edmowmun.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2jkrccugt.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gt2nvaaaoqj.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gt2uxmntakt.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2wmyvbzcs.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ztrwqvoj.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2gjgaimfa.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2hadpdbcx.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2tymyfeqt.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2ptnnhytw.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2qstsfocw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gt2vtkaziyw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zxseefhn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yqsqtplz.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2ulsoussd.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2lrrkrqfg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcurhkbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2ymvvcfdw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2tcnedexu.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gt2pbctmikw.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohwrtgmb.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2ofbczpno.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2miosjrlp.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2hhrsmupx.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gt2hyqtkdrb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gt2qdenkicj.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztucsbfd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2yabtpyhl.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2zatbriqk.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2ndlqfbyh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2sufzkdwl.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2mjdncums.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2emkwhshl.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2nuvwgcud.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2yraqyfoc.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2saappoed.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gt2mnwtbfnu.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gt2jjhlyisb.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptfmtiqt.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2kvdkfyps.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2xyggeutz.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgyyaqgl.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2nuokdnao.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2psyvqymn.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2sktivyub.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gt2jgbmkobo.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxedalcz.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gt2iaanijbq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhvredj.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2vcavlbmc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2zjzlhpvt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2izxbffiv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2grdccaht.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gt2pzhjwxmc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gt2bitlwkvv.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2jpdccekx.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2bevfatts.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gt2nrqfbbwm.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2twrszvph.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2tambgkrz.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqnossay.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugvloxii.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2iyejbkjs.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gt2gdhmfjti.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2riftnjcj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2embzklaa.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2oyeudzul.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gt2kkqljfpg.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2vhtlanxg.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2youoqnqe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cacdiocg.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gt2myauqtks.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2txinzhax.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2anrcjgcp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gt2hfnhsxtb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gt2lzpybdbt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwawyqin.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2najqirnr.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gt2opekosni.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swadklta.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gt2qpwftwpk.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gt2zeajvcky.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gt2yfgbtgsv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfwhpggs.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2lxfuvtfz.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2wnwmwdlu.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2lbmansjx.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gt2yhphuryr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2faojzhlr.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2djohiycy.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gt2vskgvcpy.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2ivxqcslr.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gt2tlkslcgw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2rmrmobzg.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2obomenpr.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2haapxluj.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ixhevqjn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2vsjvniee.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijwmstmt.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gt2jodjvuak.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dawoptio.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2ahgzfexo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxzutfna.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbexftzo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lozvyrwu.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqsmleml.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2wnxpsxom.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2iudwcruj.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2uthlbsyl.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gt2gtkskott.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2axbmpjzx.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2yidommjr.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdyxuxpk.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2flezmflg.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2tnwfyxln.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gt2hsbslkfd.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2kkqaiybe.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gt2plvjryce.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2ulsgdbye.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2opkngqkp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2onjglogm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gt2vexgpxee.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2nomrvidv.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2yrpazaxd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gt2ondhpadx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gt2agkrrwnv.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gt2zjoyuerg.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2ckxdxlmi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gt2ikrmxbwv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diwiabfl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gt2gdisxwft.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2akriydwn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2zhyojeyx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2izcdsuzh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gt2cklkxvlz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2vqwwbbhn.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gt2mbrlejdz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2pakyilrd.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2oedynmnu.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2npvukafe.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2fchynqqa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gt2lvbltoim.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrtesrhp.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gt2byppcyod.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2barbcbjz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2sgpzytdw.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2lalrjssv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2efapknzi.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gt2lqicudeh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2xbnbpiql.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqiywksg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbswkzwh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2rzerdlmz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2eogzvzbq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2oavvpplo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gt2gbmrybrt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gt2fauuytpa.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gt2jmwbrnzc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gt2vljsdezf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2knstxnph.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2xqlliqlr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2szumdfkc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2kmjmchee.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gt2tzsfwqyl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2ahmprkdw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgzjibdp.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2qqtmzjqk.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ognwirlh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2djjkqhrv.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2gvdvfecs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaigtqrk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2arwuhpze.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gt2efsohowl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gt2swosrady.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2fqvofemp.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2ayittxxl.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gt2yizjoxrf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2dnrrztks.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2olivdkbk.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2mzxpassi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2gjfirqga.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gt2duaydssh.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gt2dwycycio.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gt2jsaryrqf.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2eejrjalz.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2tuqqsisf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gt2jjcfrxia.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2smohgmof.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2hszuzoeg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gt2okkujqea.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2mvhajush.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slnmhgdy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gt2neqfheja.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2wykgvvns.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gt2bphlqueo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2ovzdoioj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2zcugxqon.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2egaxaojd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gt2canrjoun.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2urzrlhgx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gt2sigyktvu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2thbopymz.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gt2iaducxkx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gt2fukdlxqy.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukxbplmk.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2demjcazj.html

TS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2jzlrpbsr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gt2ygmjodgy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktrnywxi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2pisgrybz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmjetihj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2vsqgwcpv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gt2djmucxvn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2etuhmzly.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2akovpisn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kylpraun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2xkkulfvt.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2mtsvnwgl.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gt2kugycrrr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2bottwsvi.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gt2lcgyoucq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2vljtkgxy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gt2dddjdttl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2jtppibeq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gt2ckxcyslb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2zlbkyncp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2lokhrspq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gt2tklbcnzp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gt2hsiteqdb.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2wrtmrgij.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2ntdalvcm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2bpaglyaq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2kbvifmri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2spdcyteb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gt2xibuvrgm.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywffhewm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gt2rbzocdyw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2coceqgir.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ejhpaklb.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdbtcotf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2sjjhwrqc.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2ldlwlocw.html


<!-- 参考信息 -->