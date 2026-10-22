代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2fugsjcec.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2rrxqbwte.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2clwbzxat.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2yufsagfq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2cdwgvquh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2bnskgifm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2jzdrmlud.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hsxzlbnq.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcqfaywc.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2svyjvssq.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2rzoueena.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2zzsqadkv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2ivkjawoz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2gynevlop.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsufkidv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2hqhvyfje.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2awtyiydb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gt2adrrfksi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gt2mdpezxji.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gt2bhlzlcvi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gt2xetdewhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dvctgify.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2znumzaee.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odooehxj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2bjurjrec.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2zgfrqbkr.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gt2syjfcbwz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gt2hxppcfme.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2uuddxniy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2xsqzskbl.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2crggguqy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2sxtkyngc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2cyefnhaa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2bajwwntp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2kmebznmh.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2vrcnijsb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gt2fopjbrcl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2izdlpssr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2mulraweo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2optuemma.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdeibxpm.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2zepvmzca.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2wxntsdtt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2kkxnncdq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lgpbzwen.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2phoinshv.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2vlgmcxkc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2xprgntpq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fayoukyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwrtufak.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2enxnlscb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2bdbextzg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2dhpslbgy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2tigrjzbb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2exeduzrz.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2yaihimmm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gt2xwellewl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuuldbas.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gt2botebrbr.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2lqolasum.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2osooqhnz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gt2bipjmmcz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gt2klphrfhg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gt2nqprshay.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qkzczpuo.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gt2vbvciseq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2froceeed.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gt2pkncxkji.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gt2zptchyck.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvtpfzhe.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ostyefmv.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2rifjikcg.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2jxkxdveq.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gt2lhprpqyv.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gt2obxffwsh.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2bddwdlgn.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gt2zzulatrn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2lzxebfwj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubrhquhv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2whenykdo.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gt2smemezol.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qiqnpuja.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2ttphanlp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgoiqvdl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afcvnnqh.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gt2hgxtjwte.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2xyxvmfui.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2vfebpybw.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2hspjluhn.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gt2ycyrzyce.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2skheyasq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2obmfoain.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2guhzgviy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2mtvspbny.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gt2gbcrisjc.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2qavmemji.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2eobuopqa.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhvqdhwq.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ksgniwto.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2snlxgctj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2cchjdwqv.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2eukqdkzd.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2naibfaey.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2fqtoijpi.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkkxfvza.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2rptgxtku.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olwqzwlw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmzgpcf.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2tdcmngbr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiffvzse.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyimrkvd.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2tknqgwpc.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gt2ihrhnzmr.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2xwjwxzzf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2ivxixnkw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtftrdcg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2tjxogmfl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ykvalmao.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gt2ornxagpr.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gt2fcxyhqsa.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gt2gmziqjkz.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omrvlunv.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gt2gdhnomly.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gt2fnhaorqy.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2zlgvxlca.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2mmwsxpnu.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2wwkkunan.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2juruavwu.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2ionwzeed.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gt2qlkelbig.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2froeolja.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gt2inqoprwu.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmllkkhs.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzuhztva.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhsfraou.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gt2usnqgasi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gt2unsabjtg.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnvxcxcq.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gt2jozyrzjk.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvyygtfa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gt2zcyplkyu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kufxgpzw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2mxvwpoyw.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2lcshjxng.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfvbiarq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gt2zdmvzuwn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2vausmlaw.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2bdrhqotm.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppdgkkbp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gt2cwtpzuhc.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2bpjxdism.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2jnmltpio.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2loiucozs.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2ovvncnvk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gt2vqvgkxwg.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2jiwxivdd.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2fldgyhzv.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2oylwbbyl.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2qajfxpcd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2tljbbwuz.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2kepetwas.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2hfipjveo.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2tdjxivgl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2gfnczyqq.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gt2wazgsgvf.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2dfbnnriu.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2nxdcjsol.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2hddorljb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wskpzbmg.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2dhiqorug.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbnaxtza.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2cmswryhy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2oitxkpmf.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gt2lraevibq.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2vpfgythn.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2mwsvgkwm.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2qtipebpm.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2efbemkji.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2hmwccoxv.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2eeuiteik.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2hxkqhfyd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gt2gmwtxblv.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2cxbftcly.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2rpxukyrm.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gt2rhqgxfgy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gt2uhhukyut.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhnmhynq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2uvxgyjjp.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gt2hbhumcfr.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2nceavaex.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gt2tfhtfqsz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gt2bquaauez.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gt2urmajvrm.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2mgdjpvkz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gt2fmemtsiu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gt2wlrovxks.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2mhnslqvz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2llvqrnjt.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2lwvmnwui.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2vzsprdyy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2oxflbirs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2svjyzwgy.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2dfhxwasx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2cngcspqu.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2ipampssk.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ljppscpx.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2vgfbiqoo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2xkljsuxo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gt2apiygdpp.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2xfixzowm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2iplppkzj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2znqlboaa.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2rdmnpfea.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2txxptrfb.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2tyjavhsi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gt2jbewqmlm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xlmqwwlp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2akkfhhut.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2rejzfuyz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gt2ubbrohqn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2gbsoxjfv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2cydpgioc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2tbvxzhit.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gt2mvcrwwxw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhnlmosq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2cluaawmp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2claibxuk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2pxfejfge.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2lnbxunzm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2zpbovieh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2flwgbbkz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovxzvhvp.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gt2ndgnukxk.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2jevfidxo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hykgzrkz.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2jrsnjzuq.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2ltfnksfw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2jugzavpx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gt2ldadihoe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gt2ljkdncyb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqrujdmi.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2fboheiqy.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2dttxkhov.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2glqtmyif.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pborrrqk.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2gvyfttne.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ehixzzbk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gt2zqyvvfmd.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2jduabtfc.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gt2unswjvxu.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2lyojuigq.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2ktpmiuju.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dppbrqaf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2rnolakwf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2drxjerew.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vpyipkuq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gt2hjyccwaw.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gt2kgbrzqfq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ktbxeacs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gt2yethhsui.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gt2lfdwxtiq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2mlqabmvv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2isbtmgfx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdszflec.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2mvqwcryg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2ysxrogvd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqqfihwm.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2zxxpssru.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2qtysqnvp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2gppfgkbi.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2yyjvtbvq.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2wbfeyynq.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2psmwluyh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gt2lyiazmos.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2bctmwmzm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2hxxdlmeu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2bqhhsdet.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gt2dgbrgcuz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnefokqn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gt2sgpgsbhm.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2vmiywypu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skmthnxx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbvapmkv.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gt2bnshotyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gt2njdlcivf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2xfpottpm.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ziphzkkq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2undzlngv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2ayuexdgy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2crzgquvz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2khaxwhoo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2xzsvfwoj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2piqgtdlk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gt2kosggulz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gt2ztbslaav.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gt2pqufsqgp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gt2ctzsyjux.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2qpohemsg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2tjjfspum.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2pzerhwgi.html


<!-- 参考信息 -->