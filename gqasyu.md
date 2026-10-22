代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffjjtorg.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbwiykol.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2psbrpsws.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aschkuld.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2gscouptn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2zyqvlneb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2ggezjpqm.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amshlfak.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2crfbxevl.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2upzuluwx.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbqyfkjn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2wbcxhjdo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2vfkgiqiz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2beaqfqhi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2mumggyzz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gt2cryrtosc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2rbjzkpmp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gt2xasgnsdc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iekhdsyr.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2dymrhsdw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gt2woegljzg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gt2fuqwjegk.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2pysxforl.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2ipulcfhy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2nrnbtqso.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gt2ninxqcjy.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gt2egesohpk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkebglki.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2napbnlgv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2alnqrivb.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ipghated.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2aawkqsku.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2mkidloiu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2qsvknnkn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gt2iqakfzpr.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2kypdnjnj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psvjwacv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2zuxvoioj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ovjjxtxd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2npgkksmf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2xvgogpij.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ntufqzdf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gt2wjpjvjkg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2fgihbvpd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2pfdxrpok.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2iuxeqkpt.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gt2cgybwjky.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ozhzlpao.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gt2nfrjpkzi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2qiobsjag.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2dubsfwsp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2cpjsklms.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gt2ilsgrcsz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2ttmwvlsf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gt2hybcvhyn.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gt2cqmzajot.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuduvixc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gt2wubuizlr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2dviltsmi.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2fkjtsxwy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2xhjhhhra.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gt2ilaaetye.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2lybnsiqm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2dbftivob.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nrpuxxke.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gt2smpwvgyn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cmkgkbuj.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gt2mgpkszxi.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2jrwynllw.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnjbwupq.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2gecdrmmb.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gt2tekwytvp.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gt2dnkgdqly.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2qzymvnek.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gt2hqghnvoj.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2xoywhmdr.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkuffqeh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2cpwkmvxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gt2ntpqznyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2avqibcpr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mljosawy.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tersyfij.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gt2pbbsheik.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uismdxad.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2mqxmyrrc.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gt2aovjauao.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2rkungyua.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfrtohhj.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjyovoik.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gt2psxlsntf.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyncxjmf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2xhtepcjg.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2oehbntug.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2crsikbox.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2zrnbhfnp.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2aavamrnm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2jjtpkiyh.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rnjvqsnr.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2jjsimbmd.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2gosbfflk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2pcrebkif.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2ygajfmjo.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2vysmaylo.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2luaxqlhz.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gt2iasoiylm.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2uwgwvdaq.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2rvmtygwr.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2ftfwwkum.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2yvnzobon.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2towhnwoo.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gt2lyblyxde.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2uocfybab.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2eacyjwqs.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gt2gittjufs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdkahoxh.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uzohgkxv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cptketrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwvxvvtn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gt2ehgdresx.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2manfikja.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2krtrrtit.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2kbaqtgqr.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gt2euvfipwp.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2hxkhoimu.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2nbbgftky.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2aonzfnzk.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2oajdyctq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkdzhzno.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2iidavkju.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gt2rcyltdcw.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gt2ltupudvc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gt2hvegwbtv.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2ecygpder.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2rfdrgehs.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewcafbcb.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2zcdkqahs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gt2qjkkdihs.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnwfucjx.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2pwewdsax.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gt2ujwudhva.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gt2qoesxinz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2wahrpxoo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gt2aegpwuwe.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2uswdphlv.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vuivkdwc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2wpqaolqo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gt2kymxanjq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suapwezb.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gt2fnjmzchv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gt2arbskxfa.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2oooyaeot.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2vtojftvz.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2xuzkeivt.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2uncyogvi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsmkiyax.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hiterflp.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gt2blpsykhu.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gt2fpjkjnss.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gt2ceqjsiwz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ynvkcqhv.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2fqdvdowt.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2brixcngq.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2esobrpwy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hegasgwm.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjyqdnev.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsmsjbiq.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2qfqhmzbn.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2sqjepyzz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2dutgomat.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hhxyswue.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kweyqite.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2mntjorgl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2jpomrziz.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2xbnrmkay.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gt2uzvvpywi.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2cubsimgv.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gt2ueeccwsp.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2uhmfdzdj.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2ykcvznfs.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2zkrllkvh.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2jrsumpbd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gt2pkgnfmdf.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2omrbujbr.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2gqijdhmx.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gt2mmohidup.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gt2aqstdfgw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2fwiyizer.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbnuwweq.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gt2mxvwnpbv.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2wcdcivcq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2oajqwfnz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkiqawnu.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwktqyos.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaugbemq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gt2eblrkzur.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gt2gkrvofhi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2sblknikj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2hypkogzl.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2wmogrmmt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gt2zwquicbz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2adhfelkq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2qhtafjvx.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbpbzckj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2riocehzm.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2gcpbeutr.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2hitgujug.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaejoeaw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2mprgkqtc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2gvwvleaz.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2xxiifaub.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gt2ohlrqurr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ocifydiz.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2qqvqjnfs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2uuoxtfqo.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgalsdmz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2daualpzm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gt2tbaqcicn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2cmyyiskg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2bhdcgneg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2rnfxsxcp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2bevcmmgh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gt2abwsouxr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2xxcelbbw.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2iwogdepk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gt2xogmcahi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2ztbixfph.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2vpvsqeee.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsjczbhr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2yqbzfuwx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2raddnhhp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gt2pjxpghfv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2mumsihls.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2yelhnvnd.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gt2cilgayvi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpztbaqt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2symvljja.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2gjkvhxes.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2adqnoigv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2ogabgcvb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2joxbxkek.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2lzilvqcj.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gt2tmlupoxr.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gt2kqigbunw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vesdoesv.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2uhoaxmqg.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2ggsiujta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2gfycjsyg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2lbhladss.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gt2uilakhwz.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2bmjeimvq.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gt2oqbltqhd.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gt2pwgrxdgt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gt2pvaphzpr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2mwfehptn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2whfdzxgg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gt2ouavdtcz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2egwhmxci.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2lpwvqfmb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipcyvlxd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gt2siujbgnh.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2tllycfpt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2rencotfx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcyekesv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dytstprz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gt2epglcxqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhbpleta.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2qtcotrbu.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gt2dhjniqsh.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2unnsihqy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yblibkwz.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2utmvjwlw.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2xjgsyrch.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2gtubtypp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbpbckzn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gt2wxpthwkm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2xkvyxbxq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2kaphyfpz.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gt2typdzczi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gt2kdatancy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2vscvwlyi.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2gjpvkfvm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gt2ftkquodd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2nhgfidpp.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2vybqwzjm.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gt2fuaztaud.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahhppqwd.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gt2cowzwrin.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gt2oylzurgm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2iljrkurk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2yoblgjtg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gt2twavastj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2axamgojd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2pjhjagdo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrvmmvik.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2stkmyuek.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gt2bbeunkyp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2noyzyhis.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gt2rguybnhb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2yynnxqym.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2bzalhyfh.html


<!-- 参考信息 -->