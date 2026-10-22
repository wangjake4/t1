代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2mjvuafta.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2towptdph.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2glzbrnrf.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2uztvkrif.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2lsougaow.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wptnkdlc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2fgpzlhzr.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwcokbnk.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2qgdpktkf.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2uqhnzxki.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2vvbpnvis.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2mgexsgfv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2wzfczmio.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2nfeibfkp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2ldqdysru.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gt2jnaxhhun.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gt2cpmlmkql.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gt2oxgwqyrb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gt2kkdloknx.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctxdcang.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gt2aufbuzyo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gt2bwtevnat.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2vhyywdal.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2hulriqev.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffcjhgpi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gt2udzjlypr.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2jvezpvrg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2sgtomtbz.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gt2srwroywd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2xragaknv.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ahyhvbyp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2gclhxfjl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2btdblmot.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2fpxcixcn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gt2yxfywtqh.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdgvzrif.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2pbhzsdzz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gt2zgzpxzgh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mcarbjdp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2bokihczk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2rfmwyzcx.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2omkvcpdi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gt2tbjtcrmf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2dknjxpfz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omdmcwyw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ygstmtqb.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gt2qtrvenhu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2wrxueebr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2miyxrhkh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbourqks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qtncdlkx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2iyftrzpq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gt2rihnnukp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2mrejegis.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gt2pqqjvdgn.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2nucwtzjh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gt2rbzchlcl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2aabxvrji.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gt2smomxube.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gt2oxbdmvsh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyjbqxpu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gt2kwzricye.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxwfumzr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyuyukyq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2trjntpkd.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gt2reahpjfg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wicxhyjw.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gt2eonbklqc.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2vkiwukoc.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2tfdtvxwz.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2kfdutqum.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gt2dhpdbfph.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2npngravr.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gt2rjycpwte.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gt2enucqllw.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2wzzdlhbo.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2uohdckap.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2xdigqxgt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gt2hrzwugfo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pldvvcml.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gt2vkkssdil.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pxhdzgkh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbzjvqrs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2mggcjnui.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2frcorhni.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2apllhaca.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2ekyddree.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2rjlflpla.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2lqumefqo.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2mailsnpe.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gt2joqnlntn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gt2kcomolvl.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2jdgdeipe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2cbsceztx.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gt2eokpasej.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwjtsnln.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2fkcvxsyq.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2aukyipzc.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zkxdjdec.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2oqyrwdao.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2auixsfxh.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2prephrqt.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffcwcbad.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2inykuvji.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2qbanmyjd.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajbjfufo.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2gmdctsiy.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2bnutqnvz.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2okhmltds.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2wunutneu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvppeet.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2lzktuitx.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gt2qgtagpvw.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gt2kplcqoan.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2srdkhtps.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrumerbz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2eoaeafyr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2zwiaptvv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gt2mrhizskc.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2vvphwwlp.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2gsqcafhg.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgrbpiex.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvhlyoak.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gt2tkuhcteu.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2xrtuhiuc.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2wbuoochh.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2iypaxdls.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2jnsenjyv.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2wmacjvne.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gt2aoyfjkkt.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2vbmizroe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2urzsywba.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2jkcecvmh.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2upncrnzy.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gt2qudymaco.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2ahvmuepc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2axvtolqt.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2mlqenwnu.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2djjwyqbc.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2dynnkgcl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2oegssydb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtbiydku.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gt2wnbpyjxt.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2szyjmmfa.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hqvekikx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gt2aymihegg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gt2kevcvlwa.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2pibhoeiu.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gt2hufravoo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gt2xgqwllxp.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2umarlifb.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2pgomkmmm.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2laghjthg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gt2jnwlozdo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruycztvy.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2zcfpqpff.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gt2tjiukikz.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbclhtff.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gt2jbsptety.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2afjeblkm.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2pfvmsxlw.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2nqfyrhpp.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2grejyhbo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2eotlfvdy.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gt2yivecjpn.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvyicwst.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gt2oopgvkgy.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2flkalzvv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2jiqvdblx.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2ofvbwhzj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2yewsmzhj.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2fmzykpfq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2mlkadeiw.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2jbcferiq.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2mvlifjdl.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2tpfkeumr.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2tyktdbsv.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkhepyta.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evsxmkpf.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2twbsqwfo.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2tmgwskst.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2kapryfkx.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gt2xepsyzde.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2evifucdx.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2kiknwdwt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gt2ivbbwgnz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gt2zmeiooow.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gt2nzivcotj.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2uldzjxkj.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ckqzinvi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gt2wbkbcapm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gt2xpwpsmxq.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gt2crwpywrm.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2napknzum.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxuwadoj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2qajzfkjm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2cmiyocdk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2vnzjdzvr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gt2zqoxgtyr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gt2qjoingcl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gt2kxpuiapm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxgwagxy.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2jghphpaf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gt2amonoqjo.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gt2gftdqgph.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2pchattsj.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2rlqcwbtn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gt2lixapkrl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gt2jtcktmwm.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gt2iilxmndx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2xumntiat.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2qpwrblis.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2lkebicrp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2byrwxuun.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwrjsujm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2vrehcntl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gt2kxjzilbv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2tdxceyxr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2kxfyfnbz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqbppcpf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gt2nsjoiqvj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2ykjcapku.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gt2qolkbout.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gt2gejvaaev.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gt2vqgpbbpy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2atjbjglz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2symeqzdq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2wjqlouqn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2kuhlszem.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gt2kbsctzsz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfmipwti.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnplubkg.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2tdqjahgr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gt2xsowldpn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2mxampnxs.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2fvgxetrg.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2autckmsw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2hiepkxzx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfkaimkr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gt2ffyqfert.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2tmmvtvnb.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gt2fryjnjti.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swrxbkyu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2eobiwqbl.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2bjhdoeei.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvmnmsjx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2gcwpimgk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2swyvuqrh.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gt2peabwhha.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2tuiqcnoq.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2dkfyxfqj.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2ulgzrfeu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gt2nrtovmot.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2kfjdoymi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2aombhbpj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hglguqjm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gt2ttakvdik.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2tphawzgp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2vbdrlqvv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2zopbbnws.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxmtdmwj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2faexylav.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2imwtuulj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2mfrfvuhb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxltefsm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gt2ghudahbl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2manpwhjg.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gt2zoikuymc.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2mdshfwpk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2utdrypkq.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2usabigfv.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2krdtcwlf.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2fvoftopt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2ceyolykx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gt2fhibhnrf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gt2acvxeujx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctocycjo.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2dfntdrja.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfimzkvb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2wrgvurff.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gydcnziz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqfuhzkc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2hgibcscg.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygdqzwlw.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2jegsbxxl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2mgvabzmg.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2rcojtxoq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gt2ryyjsyxb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gt2lfxolxaf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2urhctpuw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2oneecdis.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2imcfjvro.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2zloiljuz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gt2qikjvahu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2nulkjdqz.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncmadrny.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gt2bsxcrzyn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2rydgafgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2fvyzcyjz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2lmmzylpo.html


<!-- 参考信息 -->