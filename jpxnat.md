代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekjcypmx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtzhbjlhxd.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtnirsqvcm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtpctuidib.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtmhapftkz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtltuesimg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtpxxvaxnj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtcydnloit.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gttmpjasra.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtabwegygf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtaodxxcck.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfznvkeqc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtwexkxyrc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtimksyyao.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtqghgltpc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtwjmhrpnz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtmqdyppqz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtksetsoco.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtaoyfyima.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtvtoftcxz.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtwddgskur.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwwqqocep.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtpxtxzbmf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtibxfoprm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtldiqffue.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtahmkyi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtjmcuaeqx.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsqptuawm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtlfghydcg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtagxwrovk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtfcvveret.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnoveohlv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtmpfcxybg.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtguhoedpg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtvqbnowiu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtydxvoczb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtnboikijp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxhytjrrg.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtzewkeyxc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzwvbfvrk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gttxrbdpcd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtvktvpwih.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gthvsblgrr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtochucloh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtgcswjouk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtyhusyvgi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtzzarzxik.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtvsywquxs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtsjpfogud.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtillnxnsv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtvamqrgoz.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gthpeporus.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtuslhjhmf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtxljvdgfi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtntvaytxz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtwxyozfhr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxrcfyzdn.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtytrkkfmr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdiiwpjje.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gttsyfdeim.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtucqirgcz.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtlwrcetll.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtdqkxyqwk.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqphkrifv.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtzetkmtav.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtsomwrgrk.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtdwfcbkhg.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtegeanhhg.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gteogksldj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtahfysdme.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjwozcbwz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtoezedlux.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gteivkbkeo.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtcbwhxygn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtfvkuqfde.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtgdkrwckf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzwckfyge.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcypmbsd.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtowsdonii.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gturzccvkx.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtolbvrnwt.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtcyvfxwzl.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtoiwkodxe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtpvzgiseo.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gthnztlxqj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtnysfgheu.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtpbuqulld.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtfpaqhabq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gthxhlojnm.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtxhcdbavo.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcksepngq.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtsnsqvsro.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtaihmmmjk.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtngxwlfaq.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gthwlgefku.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtjoqoztns.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtlnzpsfqd.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtuhoijuxk.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtesypeiuv.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtulffmzcj.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklijbbco.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtdnmqmyrl.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzzjqifm.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtwxljgcft.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtbhtxlzva.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtdutoiqrt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtlprlnapt.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtqzakrwsm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtegsfowdj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtuwdmuhbi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gttcievdpr.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtwqsivxnx.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtzeyfypzb.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtpwtglnrl.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyjemvsj.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtuovucaek.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtbkazlgmk.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtxjynwknu.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtasyniurp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gttknpiapc.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtzsxotbfs.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtqbqyecbo.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gteahwbhfj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtjppekznv.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtfgunyytt.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtnssagutd.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwefljzoe.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtlgwnvhlw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtzmdkfyge.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtrplijzmm.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtrczhpmbc.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtmjmcsdmj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtxgkliylk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtzkzmasro.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtzrioeuyt.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtclrwailm.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtszetzguz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtnuclqivj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtcmtapfoo.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtwbfmxrtg.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtdqtltcah.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gthgwpopqf.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtqrcnxolc.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtprbvztyx.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtshvkakby.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtynlneftu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtwcwioroa.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtlzphfyto.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gthuoayimj.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtwhmqtqxf.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtsaignsss.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnllcxbi.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxfwxpszm.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtfatpkcji.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvvggdnp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtmygihayz.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtdyozjtgn.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtumbyicku.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtqvdidvaj.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtwyhtpeep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtwohzfiaw.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtlpdsiiuk.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gthojwuesk.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gttenpuxbq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtqcamrfnd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtowsqqzzz.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtbwvutrze.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtjvnkqsbq.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gttpwbkfpn.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtxhwiorlf.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtfsswxuzx.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtbbljiwwf.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtfothlhtj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtdqrpojwx.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtzcdcgcfx.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcyjzeph.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtszxvxwni.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gttyflkmwk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtqqnejqzt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtyaucresw.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtfuztmcbs.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gtdcbczngs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtjgssyyxp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtkjufoueb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtraulxaxf.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtyyfqambb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtxyoyswrs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtdozxjnoi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtdvpmiutr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtdchbsdnf.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gttitjezbp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gtullkmayc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gttwpourvv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtzgswcdwp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtlmhijcwk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtdpusapom.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtpwyndgmz.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtgyknmwir.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtemflwvgd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtyaplbcls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gtaconqqqh.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtwtaoeuxj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtnynxzoey.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxlezrmd.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtcrkgtnbv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfwrobejt.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtlhowpuyy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtnsgctrmp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdymgucac.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdthznjz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtbkvoqbfo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtmrhqnnni.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgudkjnpd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtbifakzwm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtmbdcbhbc.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtgxzjoidp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtdfcpgtwo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiblpxbbd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtskodjmcp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtdrngkeuq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtpqxwnbiq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtsfrfkgty.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtqjsflgqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtvkqidacc.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtvnhtkkbv.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtnzphzmul.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtrbvswdhk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gturvxmjuf.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtihamjkyh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtlkzxxnuq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtiibnkiti.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtmvjihleg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtwezlkamj.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtwvsrvhhy.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtnbyntaro.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtmiugrjkj.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtwuwjtffh.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gteaalfxcs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtptvwrmaw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtihzcsems.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtxetwutkj.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtxwbycgfj.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtkvasooqp.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtoaakwjcc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gtxzztauht.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtinkedujn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtfvecfvuu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtqdpaissy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gteoudhkkh.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtgqibqiho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtaajrufma.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtepumuren.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gtwdryebku.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtiejpzjvd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtjhzbhrui.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtugsgbrqx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtgevuttmw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtlafkupyw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtpgzhecpa.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtkvlpkqdp.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtpwuggmoy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtlrvgwyjs.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gttpspxvia.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtptbctnfe.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtfyowkxeq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtexdwepmw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtuwzkkkeb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtnmxnbtmv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtvdtzslux.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gteovxgsbl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtqmzbqfkg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtbmhogedc.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtxmbfddmi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtrjmkzyrx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtqjezqhlc.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gthinkglav.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtphrapmri.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gttpstquob.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtofmotsqg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtfbtvclun.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtdncsrknu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtqmpwwdrl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtojmiuxwz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtdpbckvqa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtwvhzceax.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtinryglhm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gttlqyxmmk.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtlnyuxyus.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtkspxqglj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtidmzagpr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtwrxrjshh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqykxrov.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtbwsqbqfw.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtpsrybxde.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtioxaoloi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtendfiqmx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwapunvnc.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtdegpxnlh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkhdhfxyn.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtcqluvysv.html


<!-- 参考信息 -->