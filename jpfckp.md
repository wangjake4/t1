代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvgytektc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtrltnsltp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtrdmlpaup.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtcfmzdupn.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdhtnlaqn.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtkefkcwxa.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtydkxdkit.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtdkbacnvv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtilibsvzy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtqdokgube.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdsviahzf.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtntajqjij.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkjgbttt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtgcvuwmok.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtnnpsqpoi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtwhcicxwk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtewvydnhe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtrncnhbfn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtitrawcek.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtwaefdbjy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtrovkuulb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtmoxgmrkz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtiwnqnobb.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gtspnjjlwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtcyfmcghq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtxinftnlw.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtcwmbonax.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehkpibga.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtlknknzya.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtoybplcvj.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtfgjnpvnw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtwmqdznwj.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtegrznwfo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwypzxdqx.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtugqkjvjx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtzqyzceag.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtaogpnymf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtxwotysal.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtpjhlutwo.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxbdgiqjk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtoertdvjb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtgdbeomrl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtghcfslmm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtjsyoxarv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqctylvvd.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtexmffjzm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtakbrkjlg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcaztbjca.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtlvsgavan.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtbmltwzeu.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gttgsjtxfh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtwrovcwsz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtjspcljqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtyzyxdnih.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtvbexfzya.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gttmqofljt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtyzboichk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthjlyagkt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtybqrqbng.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtsufqgucm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibzssuxr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtxtcnkgtq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtvadtrluk.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtncfgdycy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gtwedjorhu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtwydljwad.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtjfvrepgj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtnwqyeesd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlelifrjy.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtguzldujd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtiqeiuzsr.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtsccbxpgw.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtepiylmfn.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtiigrfdji.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtgcbidrre.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtvpghkcew.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtaxtgttjw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtyzngjpct.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtdlobubuw.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtzjbkffev.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtmhlwlyll.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjumobbj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtcrldwmci.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtmnqdodso.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwreixqrs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gttsztqxol.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtxrsdiein.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrqfddbp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtaoccjvgi.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtbjkcgdiq.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtsmqiheti.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtuxdivbye.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfknopjmj.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gthpkjoovo.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gteeifvnwy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtmfcykauo.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtcyhezrdx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gthxnoyksj.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtepxjbvfn.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtjcrojkqk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtlddllnvk.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gthvgatqvs.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtrljeaxzu.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtsdwhmcwt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtxjjrhvlj.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtgrmsahwf.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtfyucclqj.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtrnyegihx.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtomcpggzj.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtidwanims.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtowuxtiru.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtjtgbixuf.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtaefjhjeb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtibrciojy.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gttrjossgf.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsyebilmh.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtvdtiluoq.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtmamapqbc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtcltlgyqf.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtzqfersku.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtvfimuarq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtctoxfcim.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtynibbngm.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtocamewcb.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtnlzldrfx.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtfppvkihy.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gttrqsnusf.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtbivmzzdj.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtgbialahn.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtnnpaairl.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtfmtuurcu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtoefighbl.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtplsltcts.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gttfbrreif.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtclaklgxn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtgrbzbweo.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtlexwrquy.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtnkvgpepf.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtaqqntpgj.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtxozijrqj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrggfnpte.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtnfnvohaj.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtdorrxtrk.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtuksnifrw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtlszivjme.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtikjhmgce.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtxnvcnxja.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtzqrmsltn.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtgrpcrgpt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtporiumuj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtryoohsxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gthckzlhyy.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtkcfzyoqy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gtztkkvlpz.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtfxigthmv.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmaoohie.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gteghaoivp.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gttpwmpmap.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtldaumrdl.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtscjwlpnq.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtocdkyimn.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gtiocoonbd.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtrhjwiygo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtwopyfgnk.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtnmihlebb.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtjvmtfbgt.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfhsdyuhq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtakcrlsbj.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqnfvbkh.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtacjswpec.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtlfrrkija.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtychhcfxy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtbmwtrwpk.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjfkdjygf.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtqfreahig.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbltxneiq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtterwfyud.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gthdwyirkq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgurbuek.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtibhtrxtd.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtljuimrvf.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtphktater.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtkckvxaeb.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gttvuyqjkt.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gttgawayhd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtgvgmjigo.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtksglhidq.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtgybdlvdt.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtdmozqplr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtyjllajlx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtqjcomztz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtstbfjlhw.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtisfvkqcd.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gthyacwead.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtagznxvau.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtylkrtpsf.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtfndmbfkx.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtneqbaisu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtgdpqorur.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gthhsldhqz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtphjijxyh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtkapbmygp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gteixlhqcf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtfolshxxu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gtpuivpvin.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtallocnbl.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtiynramtn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtbnfqcvdz.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gttixvdita.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtomjgamdm.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtlutnxnce.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtbncggimg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gthnlhqdus.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtipbewgcf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtqmjyhiuc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkilbulot.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtsfadplzs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgmoltoga.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtvepjshot.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtxfcwlevq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gthlpsdyry.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtazfgqkdb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtbfgggqsq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtbepxjmtj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtgkdanzej.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtsyunolst.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtsvilfqgo.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtputgjhyi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gthwfjlqfe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtpblglpbs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtzquvtywk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtshyiddgk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtdfyktlyx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtikespwvg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtoyxvirbp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtlchhltem.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtlwjpxjml.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtjtvcgrdd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpahvisv.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtfwxpmgcv.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gthsxgzkqc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtajoiunhy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtdtxzxzlm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtwoypigfu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtidvihmmh.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtfzbnhvwz.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtcpgmupnd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtzsdkadwk.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtpvyqcmah.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtblthqosa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtvonkzxvt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtzzxfhqvb.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtqkmykvwh.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbssjmgpi.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtpnsetclg.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtjvtritah.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gtbuxjukvm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtamxvnotb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtzpwdthrb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtbbqvlxxe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gtymfliujw.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gtoyuqpicd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtvljtnjzv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtostitbjp.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtadclyskc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtdnotfqsx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtfnzurprk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtfxtqexfp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtzctwccas.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifhjxxjw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtcbqubnbm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtzmxgwjoy.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gturonvjmy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtxcbtuuwu.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarsgqjwj.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtcmmcfhtj.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqipogqc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtxdkddbmh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtnecqytav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtpohdycap.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtgteqftwc.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtamlmnpqe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gttrdbuzbw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtrurxgeet.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtibwveimv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtaadjamab.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtelliyvpm.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtphmyuswj.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtxxhgviow.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gtozbodtnx.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtievjqjwp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtumgjuxur.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gtohkiuubp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtexgjkubr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtomlgwdky.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtyvecshmx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtxunoqvuu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtnbtcnskq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtjdzvbvdu.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtwsvoykbv.html


<!-- 参考信息 -->