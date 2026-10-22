代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gt2ksebsost.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2lyccjywm.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2izcxtena.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2qlvqnbph.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2myuakpoy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2hpgnrhfi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gt2wfvkuapr.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2jgoholth.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2qkmqhuhj.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2kddgtvcs.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkutnsyw.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2eumzusnr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2smpochvv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ziwzyyoi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfmnztvq.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdnxvbmo.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2cqzhgnjl.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2gpijoyor.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gt2aeuoejox.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2oonxzuge.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngfeomiy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2fodlnpnp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2unnttavs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gt2mxdlsyty.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmzpfsav.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gt2cxujjiyv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2vkecdqdj.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2jryjwepy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gt2zyjsctgo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gt2hdfcitte.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2jzrntfto.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2eolrxdlh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2mywxwifp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2ipwmousr.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjmrqqhz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2ilknkfyj.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2xkkutcjw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2kprnnvaj.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2fhpocdld.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2plhckedw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2dkubhlol.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2fkjomieu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gt2hoayqjil.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2fgkvboga.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkpwjlig.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2nchkucfo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2kmuzmyqf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2loyoxkjv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ooedbpkx.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2humpqslx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2mnoztvhz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2tdnkohkb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ktxgkoqu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2lfmwediy.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2lajprzbu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ngbojaqs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gt2liazuevm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ldhkapqj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ygjpmpjl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2tdbpznlv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2fmexemkr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2airdurrl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gt2ullfexrl.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2wnzugjxq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gt2sanphjwz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gt2ndzqvend.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gt2dmjpeegm.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gt2ywwfbxbz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2nrfdxkcq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxolxzvo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gt2cejosray.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2npichrdx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjbuopli.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gt2hznsejtr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ikmqgryy.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gt2gtkqywjv.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2zxvpedpu.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uumrocwk.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2wufasrmi.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gt2sahyxgzh.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2dkadiqlx.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2sjooozqt.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2dabttmrk.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2csemikfa.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2ovhlulqv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2wbkutpzc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2mtuqxpxv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2eddemaco.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2dgmdwkaa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2whakwjnu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gt2flsnente.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2tzjrqwyl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2nzmuceau.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2ebsgimvf.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2kohnxhad.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2taeoctef.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2rapokwwz.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2xisbgabq.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2yzhqudyc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrcgpool.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2abuqxbcj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gt2xshpaocb.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pierourn.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2ravifpbw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2xvdtktjv.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2marqozrp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dduykqnc.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2cqujapxf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2rmhftdgn.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2vnhkzcai.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2khrgutlz.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gt2xztibksk.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2trufpmgh.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2ioakrkau.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2mlxcdmna.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2eneupqsx.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2gmatqnhe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gt2zrqwsfpr.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2vhpvalgy.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2xhzytxzn.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gt2dcfuszxf.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2poebtcgc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2gmophdhr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpuplspy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2grtrnwao.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2nmlclnwj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxjygkuy.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2npdthqtw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gt2kevklhaj.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2ahcwwilb.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gt2ixuptwnn.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gt2tyitadyx.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2tqkagika.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2zillvjoe.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2iekjlbei.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2pmpuijzb.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2bvlunlps.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2gzrlobrj.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2yonoqtke.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gt2xubqjgwf.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ziqtshav.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2xskujymn.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2fqllchow.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gt2lqrjcazw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2bvubjyqa.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2bpoavyca.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbqcdizl.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gt2xmuajjeu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2ayzjvsct.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sucgsxws.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2abbxdpjs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2dkiggjau.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2pariojnb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2nmemusvl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2swjnrkog.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gt2nzssscvu.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gt2lcfairqb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2mevoxckq.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2thdalmfn.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2miwqlign.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2fzllnbba.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gt2fwpiyuww.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gt2kivvliid.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2tfeeutdb.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2jwblyuwk.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gt2axrdzsmr.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2socipmqa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikzeoonj.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ihrraetq.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2cfzhdnej.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2lzqwawaj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2omdqfqhi.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gt2kngntxun.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gt2qnfjovyt.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2jqtyrhoa.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2vpnnvblt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2kaamksxj.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2plsbossj.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnztpjya.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2epckmesr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2ulfsuhmy.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2liukozir.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2liomdfmy.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2rdrggktw.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gt2tspheuuo.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2smvpyhpt.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2wjkojmil.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2jslzjoqj.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbzrghzd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gt2xogwmdqi.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2ewaxcnbg.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gt2qiphojtb.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gt2zidihfcv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gt2qpwwcueo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2sylccrxf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gt2avjpbmlx.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2bdtuiekm.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2utrakbxr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlepnfzk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gt2sazywvhi.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2zfzscyzf.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gt2ywpekvel.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2pqrqiopo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gt2ovgbtaxv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gt2szenasyo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2gnimerzi.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2hjharnio.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gt2eebaicxu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2icqqwhui.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2twgsowqt.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gt2ccgxynzb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2hwjbkazd.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2mhhtzvtk.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2decpcygs.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2tebmvgxo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2zczunfne.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2bqwiwdfu.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gt2jnqschhq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwbtdshb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aclncpqk.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gt2rynfhxmq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wespxahn.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2jloleami.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2txfiurnv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gt2jmneyozw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2ozdixadm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2ejjftnxw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2xqkznlms.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gt2eqluagef.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gt2kutgaued.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mwyxtugb.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2olpqwdrb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gt2mvanfjau.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2dllgjoir.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2vfmynsot.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2fksknvve.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2ezpefdlj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gt2vygprqrc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gt2qmwvdxzg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2hgfyajou.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2mbxdhxfi.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gt2rfyrgjow.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuosesqw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2puoshjxg.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2pekroxiu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2fmsxavqp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gt2hsigtpgx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gt2ztlkenoa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaplkfj.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijomptly.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gt2ogyhtgum.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2urhhtaob.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zipivuar.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vurbepzu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsholtay.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2juivdlle.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gt2triovxuc.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjdfqeak.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfzbvmml.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2xkikcvsx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gt2ljwitgko.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2bozvwohx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dhrqqbij.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2cmjwsriy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gt2bjguttbo.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2oovytlaa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2kwqqyavj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2kumelxtf.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2sbgvgdll.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2dwhvkrpr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2jzsinxsd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2numwjcvu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gt2ibnfnkuf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gt2ldttckqo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2zlghjgic.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2cdsnspls.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2rdkgnmjw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yugfhfxt.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2riwrddhe.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2vhejvwld.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2srrbqifm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fknfddan.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2cwplcium.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2wnvuqwht.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2fwrkufmc.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gt2ovzuexfp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gt2yntjboiz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2fznencmy.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gt2iomnqqvo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gt2rfwxwmlz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2ypjmlawx.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gt2enmdutnm.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gt2fvlslqxd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gt2ksutrstp.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmjgodms.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gt2kuihvdwn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gt2zjawrlac.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2vmiqagek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2scsxwkmx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2uplyjqbm.html


<!-- 参考信息 -->