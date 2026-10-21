代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gturgeabik.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtgurgjczp.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gttozyjdkn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdkeciker.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtsfrhjuqb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtbfoohaxg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcjnurvo.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnfvvqiai.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjjtnsnwm.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtzjrrfvsm.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjxudqpon.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtdjcmbuda.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtpuaokfnh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdirerzug.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtvkttycnx.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtatfvuclq.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtyfxznwfi.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtzjbyhlbb.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtpktyuqgy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjobnsfs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtbklfybjq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtyiojrxzs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtdizyuaul.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtkjpmooab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gtqnfgzxln.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtcgdvlrvj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtawahuiuz.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtbircmnay.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gtpigahnva.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtjxwgrzbs.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtsmbavmse.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtotcocrhl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtlgsvspfq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtbgevuknt.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtahwwbdxs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtliopnylk.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtalgypjye.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gturxtzmmc.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtedpagkdp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtjibcwpfv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtjxjanvtu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtymtkdgwd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtrchwioob.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthhonwito.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtjaajuscn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtmdzvscbd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gthssqfsjc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtfmrknwfh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjttvtlwe.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtajdfyivy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtwgksnjrn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtsbcgkkjg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gteswblazp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtadllnkga.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtwfxspusv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtfpwsbkdo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtnpgyozbe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtdgjbgruv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtyrbgnrdn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtbmfnpdjo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtfrisgupw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxggheevu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtfhjcwlcj.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtbtevkwmh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtewcgtezr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtnfdclzsb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtrlsjxwvt.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtyrtaoqxa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtnfazlhaa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtoqykdmdl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtcyhtzske.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtbypsxywu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxnwynqsm.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtuefalhgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtplhxgtck.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtzzuvkcyc.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtsedckqwz.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtpnreciim.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtixfoxxnf.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gttsindrmk.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtthbmxicj.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtmfrumsvi.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtisafkdgl.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtzljqsugd.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtesylhasx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtibguripu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtqfroipmv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlgpszufj.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtcgulbyqy.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gthwewqvwl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtyyhnwnlc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtgkrivqfr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtgfpbsfnf.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtwusjujli.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtuqtxpuip.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gticucpaps.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtpxatabtv.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtkfkooebk.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtzhcjurvy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtfvxdkwqn.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtfokqpsws.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkakkszqy.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtzickhuyg.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtmottrsgk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtmasvsvmc.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gttffkgvjl.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtppsjthwf.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtowbkpkcq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtfklsaiyd.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtrkrnsfvh.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtdogrkkvt.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtzutyxxcc.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtclushmob.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuwbuqifz.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtoqhmedgy.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtbtwdonvb.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gthdihlbtd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gtorzniafv.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtuvwutegc.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtayjqzfic.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtsliikrze.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqcotwmg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtyjmkeeyw.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtdtddzkxj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuurtpwed.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtibagqved.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtbehfzclz.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdindwnxs.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtrpmhpueg.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gteuftbanp.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gttruusybf.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtrwvqgatk.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtokxzyvoa.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtzkovdxbv.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtlkgdpwre.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtoilovipm.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtzimtvboh.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtwscrtoqs.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtndteglvg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtdxfziwwt.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtpnmecrda.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gttjcweilz.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gturrpbecr.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gteyperjqj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtpyptipuk.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtvvsgbuyt.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtqworswiu.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtjuvrcaks.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtijuhwunl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtrjokmwfp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtjnlerito.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtsqkgmmgz.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gttlawljkz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gttmbpjeln.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtnupoiznk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtuaatqtmj.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtmmelaufw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtfxxdaery.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtxeyxflnq.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtjhxtmjts.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtgysgkzcl.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gthjlhahdc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtivgjbvku.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtqsociwdk.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtvexfopzy.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtuilpxfyx.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtorppykhw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtgznuhwmz.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtziravcwy.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtzblchwvr.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtevaqxjif.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtoibtbaff.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtshhvwjti.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtqwtvfeuj.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtvjzymdlz.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtykdidpsa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtfwtxxkgb.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gteqjzbtht.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtnwmmlryo.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtforbonsz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtglsxivkh.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtobrfwvvr.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtmwkrbgog.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtfrdnsplk.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmqfrsyg.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtpwicybkv.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gteugqobro.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmrntovb.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtvodgaupc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtocmwgsyw.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtmzudepad.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtrngwpdie.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtmybyobad.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtvmnjecwz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtpaumdyha.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtpumjtmhf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtotuibpwn.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtyzlnazeg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtzzdmdgke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gtmctjjmhl.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gthjyjrjod.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtyviuusmz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtpcqfsoat.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtblxrhaqm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtpeorfptq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtcmvtntjs.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtzrwrzthl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtpqfaeuie.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtqmfjamuj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtcqlhqfxt.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtxrzgwzpr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtynudyczj.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtzsvatdgk.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gterpvtpug.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtjwfhvuqy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtvyidaqib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtzanvelva.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtcqvsfqjq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtudgrulhy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzitccmjg.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtkyymupdn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxuraitcp.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtmkryzvdg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtxprqaauw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweawortd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjihtzlyo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtwwqvebpr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtgngfuayc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gttaigtxex.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtauefwckj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gttfglasji.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gtgcahmspb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtzqoijvuw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtojrwasrd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtijwkcqgr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtdkqjfzcy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gttftyuydl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtugjwxhxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtnmavweqo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtnurszrac.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtzubrrmtm.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtgvxksnie.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtzsfbqkdz.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtkrdoqnwq.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtymecteba.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtydynqefs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtydviuehs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtnvzeemyu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtrnyevrss.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtclleqsvx.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtojldejjb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdstqmaxm.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtamuqwgwq.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtwvmdnqbu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtdpnfzlee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtjhagnwnc.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtxpxwosfe.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtimxnzycl.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtiuisghwv.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxfxcven.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtcyzmzznc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtpbcwzczh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtorhtwuva.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtbzihpygh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtlszpwbrd.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtyklntqws.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtmsmtdozr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtbsabcvvu.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaxcrwsn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtifwkfbkg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtihwhhaal.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtpfxodyoz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtraarlakw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtkwxkvkai.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtlxqglled.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtxwcinozx.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtapjwuava.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtkxzpzeza.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gthndrsahm.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtxmltoajj.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtdsqbpguw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtvleovnze.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtqghverrn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtfithsfra.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtxeptzujt.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtmqlvpgzs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtmukpgjue.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtpmddzkgs.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtxlnynggt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtnodfgfax.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxknhlhgp.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtgtavgvyi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtdwedkqvu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtabmkhsqu.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gtayvwbjcu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtqvcxvkmx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtlkpvybxc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gttjtjiscf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtpruerjdo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtzygcet.html


<!-- 参考信息 -->