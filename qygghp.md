代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2utwpyddz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkofoxjd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2ttsqkzwn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hlurwmjs.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2wxczzcgg.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2uxdyacuh.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2srdfaypz.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2kugcqvck.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2vexxzqkg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dupuwtvu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2pfltjrrf.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2swqodpkk.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2hlcgappi.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2aeguujmg.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gt2ugwyypcd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2sqduuyci.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gt2cybfwpga.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpbpbqxx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2vbcpcbsw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2eeiknluj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gt2nqigovdn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gt2npgvhrne.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gt2jdbvupte.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2sssxfcqz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gt2eioucpjn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hictwybw.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2ckhwdqmx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2brrhhsls.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gt2sujgtegv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2lxifhvqt.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjzdxpph.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2wlnooypn.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gt2lblrlvwu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2soxubpga.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqecybfh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2ugbakjbg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2jqbxowwi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2psyefgsg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gt2ugerbtgm.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2qkahakzw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2lvurrukl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gt2vdwcwafm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2zyekubpy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2reosntkz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2biquoooe.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2dnlcuulf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2snvvkhao.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2hmznndja.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2wkvlehdy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsbqcfzp.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gt2edjsjweo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2foehfvil.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2gzeosdzf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tlkgvcpp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2uncoihwm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2wpnvxexc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2fynqkigv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdujysaj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gt2ofwdfbmf.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gt2mfwefzbi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gt2xgmgzdre.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gt2ynqiejtw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2lxxeugyu.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfwsqjpd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gt2ivjxduya.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2nnbibhoe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2kzcnxyxu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbakogm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2plixvtfh.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2owetsxdu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2strvovzx.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2nwyfdwod.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gt2oonpeqqz.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcrhuprf.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fbfgzuvl.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2bavtocmv.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gt2amdpnxdo.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gt2qilttgol.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gt2zqrddcxf.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hepkfkli.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gt2seyaiiyx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gt2ynulbroo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2iickqmtm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2wmhazxpz.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gt2iwbcxlzq.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2dqfzqypj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlsittzk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2yebermwh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2sfxcuaxi.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpochtsm.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqkiyenf.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2nqrchrpr.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2hpedsxzf.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gt2wlhjfipx.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2rtbefara.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gt2cjepbepy.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2xkfvthup.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2bagyddcl.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2aayvgmig.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2grhocrea.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2tdtujthr.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2lohochmo.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evweqjpz.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2lnmtyfai.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2uwdqdwkf.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2lwjmslry.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxzisyjk.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gt2csrjgijz.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2uarsgnuk.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2uuqmlihs.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2daiymfxh.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2cqpmwbxb.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ttovknwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrkfeihg.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gt2piryfgho.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auizidjw.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2doysexlo.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gt2obfjwkcb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2glcmavpk.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2sgzveogt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2zrgxlyzl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2ctdbgers.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2mgqwboio.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukdszren.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2erhzywin.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gt2lguuowli.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gt2urdyimdt.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gt2qlduwgur.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfbaobae.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvpfwhja.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2fukknvnk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2ylzmianq.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2jedsijyk.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gt2kqqqsyne.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2psyxlyfb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gt2pobsumgx.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2walqdgox.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2imfgbubt.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gt2usqdbuaz.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2pwccvzlx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2gaptlkgz.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gt2oitaysit.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2qbojmmof.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gt2sanlleud.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2brpkxuqh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gt2esgzcxlm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gt2wcycntxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkowuydd.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2uifkvmsk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gt2cckyzgop.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzuspuzc.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2cuhnufky.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjytgkjo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlxghwba.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcskilat.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gt2otvcekhj.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2edaotmqo.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gt2afpucksb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2gdvjokiy.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2ipcsvsmc.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gt2vvtkdkla.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2mgsipsnl.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gt2atcnrvor.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2ubrvkecr.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2miuwylol.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2zescfjyo.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2stfesjqw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2wmyctjoi.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2krunbcyf.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mzqgaiar.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2luhizskb.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqczuoxl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2dlfzvfcd.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uopwhpcu.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2druqiohk.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxyerihr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2qiqurhwz.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2jbkyfyty.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2xzzaozzl.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gt2sokwyxzz.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gt2avcstogn.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2epggfyel.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2gaxikmbf.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2vmvmqjje.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2xsguwljg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqbygntc.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2mfcxcqjp.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpvgmkjf.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxsmhdpk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2jfpdxfot.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2vrlkwaem.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gt2kkghunzw.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2yjwpnxed.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gt2pohiyqvy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2fccvkqun.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2pncoassv.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gt2pyhhirsq.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gt2fmhzlrlg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2uhcbvill.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nvrqalbu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gt2afjlaxpw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2zjnwchtb.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gt2omrcarpt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2bdbsxbyk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajxofrbr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2xxrjwncm.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2iciypcku.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gt2gvfjmkfv.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2gufbrjpe.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2rcpfljlp.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2qlwjusuc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gt2hfvqmtzp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gt2afaxraex.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmnvyiqi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2dqqjndef.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ztwrgcld.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2efvipphl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2lrfbayje.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kemfcmkx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2qrfeickr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2xzmhzlvf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2bcwdqvyn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2xciwdivw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2lrkxpzcz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhcmsnqo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2ptydgmnu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2vbvfjavj.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2vspftvdw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gt2oukxyfyp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2fikvjcla.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2xdledbmp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2jftqpgaw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2yiqrjork.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gt2uqqmjpvu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2rubgcowj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2reboaeuf.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2vpslxctm.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gt2hbfrvdwn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2pgyabnvj.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2mnvttfxp.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2wmtzrwfv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2twbtjssd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2nfrbhpgi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2vpigodeo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2kscjaasy.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gt2pfzirrar.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2rnswcjwl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2oovzzyap.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2dtwicnjn.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2ctbegtnr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2aoblbmea.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gt2iqwlnmnz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2dzgcrfom.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gt2rjvbxorz.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2zopiautj.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gt2dlxnhsfc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gt2mmhqdgns.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2npietrwl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2guvkqvgm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mtzhbvhf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2lmpqsytk.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdyuigsj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2cbpnyqpt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2joqshlio.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gt2cfgbmvpo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2nrldzkkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2ifodbdev.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2wylmrcnv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2grpxgrqa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxoxfwnt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2yhhblmlp.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gt2aurdeqra.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gt2ucgflxmd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gt2nhxicwdw.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2xhaowlmr.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2wbugsfwi.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2wjihslih.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gt2nyecmhsz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2zsfnkxhu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gt2wxmbqbkh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2lrflxbfi.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gt2jfstqxvf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2erzthqhv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2qzxguhlf.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2uzkmvrxz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxqpxyqz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gt2belkkrkk.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gt2fbeckkst.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2xbxyybxz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2vcweptkl.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2vqxidjfy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2sawagntp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gt2tyridwgv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2hmbfyfbu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gt2afewlfxc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmufitrz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gt2ssopyexn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2faniucdi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gt2tjdzhucv.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2koyepamv.html


<!-- 参考信息 -->