代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtuwaiunsk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtnjccrmon.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtxrxidiou.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtcfldzhqx.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyegtpiow.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtvfuheqni.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtiefxcadf.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtxqkekswg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthoxuwiqu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtvvchbetj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrasxtshu.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtxmxglrjr.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttkjnynpa.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtdehidtkx.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtvygmozyo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtvysjueej.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtczeesofr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtjqalxskz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtbntfwpez.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtssxtzwbd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gtxssjczco.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gthxlisfql.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtmovrjzch.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gtmtsdtqis.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtifhfezgo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnnztxwgu.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtdrrimddy.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtrwphklzs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtrpypdcys.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtehksqdha.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtjqmarknr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtoorwnyvi.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtvverejiq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtffbaziwb.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtopkjyfrd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtermvdtne.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtnksrlxqq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gthiasaobg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtddualqhu.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkaozuave.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtmcxpxcjp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtcsbppzyy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtuwgehlmk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gthbjdrexx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtqropuhli.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtombfnkfl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtqwfcbkgx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtuxyisdli.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnihmpwwq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtllxtzsxg.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtlnikgaab.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtczyibvay.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtwwmkhgmc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtmkqznvtr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtaqkhifsk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtglgbhbod.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtodiihkkg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqclifwww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gttybrdmdp.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtgtxknerg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtketvdogm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtumxgpemk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtsexbbkyh.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtqihhvznw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtadnmrsne.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtoedxxjvz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gteiglgdcm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gteteclzui.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuuzerqpc.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhfyqhpx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkexqywwx.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtlhuvtcfb.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gthibcgamx.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtwvgsfhme.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtwxiaqvvf.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtyavrexjk.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtjyvaylpd.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gturvgckep.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtyfaadxlo.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtigcjsrme.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtqplgmdei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtbsdfzrur.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtiyvmheyt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtonveduav.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtoccdfsay.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfypfqbhm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtdvvocpqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtohwqdhkk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtllujxavm.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtcbjypoyk.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtaqjqkjed.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtqlnfiiom.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtfmocggwn.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gtbcqzemlj.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtjervdsqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtpektbtdj.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtnztoitkt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtdygcugum.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtucfyegnk.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtlssflhkx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtpvgjpbbo.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtoodemsij.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzribvzoq.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtgvegauyb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gthppsllmm.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtashvrcvv.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtioseajjr.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtluamjbuf.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtgiofnwrv.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrafycboa.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtvcwqiuhw.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtmrguyzuk.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtziyxpwtx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtbmudywlv.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtpjmitwhx.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtsickjrqy.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gturpquxzn.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtstalmtav.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtemybygxa.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtrmxyjien.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtrjehvoky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gthixxudun.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gttahqaxyo.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtdkowzmrf.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtfupjcysn.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtnndxusww.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gthtzycyfy.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtbsazixbb.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblnihxdh.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtfkpjxwap.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gtpxaqaxjb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtlpegpldb.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gtydxvgnrw.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtbgwkrdgu.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtkjysngga.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtbnsjgfsj.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtgeuzsrad.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtqehdtuqc.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtbtjcxewd.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtkrnnmqjn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtcmmtzrft.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtwxiuguzr.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtxgcdzvnz.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtdrzzqqhq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtvezqzkbk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtjwxfqmaz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtyutjfeal.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtxssrhhsd.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gttxusgzga.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtwvtqxjum.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtuilsgjoz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtggymncdr.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtlnunoqys.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gtrflntovq.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtpgauvyhp.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtxtkidkpu.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gteyfynqeo.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtcxmojvfo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtnisfspyj.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtwpaznrdj.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtoaxrzaey.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtjdxudpna.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gthhmvhqyw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtqluuzwqm.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtjcjawtqr.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqzqpbgta.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtvgmkbquj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtzkhhknve.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtzpdrwmri.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzodxqtz.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtarzkvovn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtxspscihg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtprnlrkig.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtdcdgwrjb.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgoejmoa.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtdysvydry.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtddqrbntr.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclkehsvp.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtdsvgeuwa.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtrqpmhgye.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gtaamrcyaw.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gttxoirvgb.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtkznmnxhw.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtxffxaknm.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtrrlkloon.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtjagxvsqh.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtyrynzjny.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtyozyrmtf.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtxklujsht.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvjeldee.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtoeqsogxy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtflylfies.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtssyfcpvm.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gteuhtjfal.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtbsxdkuce.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtarucanpe.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtkafuadek.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtpjxxnbby.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtstotnnkr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjftacqsj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtcapkxyvk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtrigbzusi.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtkqkagdzf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtldqpexej.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtpefjxmzn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtvbefrwzz.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtuquxinnb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtigxvqtjx.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtybbeeceu.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtcifhimiz.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtskdyachd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gttbomtnnv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtjunfdufb.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtprrlhgoa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtwjmqqzol.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcspapiwa.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtolhlkiwe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuouvkztx.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtflegznfp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtjxjwqgcc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtvionjjjk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtaabsddql.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsdevctdr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gtogywyjmd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtscqrqwwy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gteqmeuptj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtczgkkuom.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtnnhlhmrc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtqnwkxcpe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtivpgkatt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtcstalswn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtwxjizjjn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtvdmpweoi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtkzcsgpyz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtftlmvbjs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtbbgwvueo.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gthailgyfl.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gticjlcajw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtmswdkefx.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gttafizfcr.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtyrftxrba.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscgvszvl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gticzhbblt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtwnqsskoz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtyygvlscv.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtlismrbsl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtsyoxbvqf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtwxwdhpfg.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtvzbqghce.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtjuhesxoo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtopeynmhi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gtketmsbmp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtxcygqvnv.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtwmzwoyke.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtupgkzmwc.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtnkbtkwkd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtpcihpygs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtgmtzpgdv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcjhdgudb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtjuamddax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtxfixognn.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtnytcsuwq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtihoqyepw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtottdfgld.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtxmdlewwf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtlhuordke.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtshougppb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwlbassx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzqtasdn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtfadktmnl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gtbwdwphgk.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtgnazwhmx.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdzfhbkh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtduwzpdgi.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtlrrxwtyb.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtlsgyebsl.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtbseudbpc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtgxnapbpp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtwrjbgfnz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtkangyldw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtywekvqic.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gtstlsvfci.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtgvqzbbxx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtkfoxhzpj.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtabuvxhab.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaoabczl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtwedsrmud.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtwzspakei.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtquuumfyo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtbabocrke.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtqavenyfw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gttpoypugn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gtdajyvmlq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtsytcwuez.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtqvexmeol.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtxovdguvd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtlhpkjxjv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gttfdhkrvu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gtmrooofvk.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gtlxlkwpyc.html


<!-- 参考信息 -->