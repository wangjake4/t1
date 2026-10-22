代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2qzevkols.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2olgqwlrp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeywfrza.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2gjgjhjfq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtgnfxkj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxzldexl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2aogswtot.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2hobnynlo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2eidsvcyo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gt2djqqibpv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2dueoccvj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2gczpzbns.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cppiwtxd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2wuiyvhkj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gt2dljjbsrl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gt2yyznnebz.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2accdudhe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gt2xggkgyya.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2kzgjjmtz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2kejmhnrk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2gsfrvvor.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2vjjypfra.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gt2jdaupydo.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2mpglnsds.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ckpktkna.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hinfagny.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2kmzcdkmy.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gt2vzwxghxv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2rsxcdwti.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2qopcoiod.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2vpsfvukt.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ppfksljn.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2srsicvmt.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ntcubzxb.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2onclzwuo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2taewanjd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2mdyirirf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndayvorr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2swaohtbx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2mwndftpg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2gtelordv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gt2ajmzcude.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gt2nduypsyw.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2ppcecnki.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gt2sswnqoja.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gt2doobaxui.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2ugngigul.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2wwlmgabd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2kjlrhesp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhdzdec.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gt2fzrmkzkr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gt2qkdgzzks.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gt2fwxindhy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2qmgsrbsd.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2xwmbeynd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhyfvygz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2rmybvrbf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpixgpes.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twrxvbrt.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2cozfhyxs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2hujymaci.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2nhsfytad.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2derdcqle.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2laumphvi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jswjspcg.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2vplqpryg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gt2ghjtluuy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2iziokpdv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2ltwbdhub.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2mwlwzdtk.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2nmvzwdkj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2hlgfrvut.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2vmrggkys.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2zbdyoedn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ackfzzpw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2gjntunwv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2ktfmacjq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2qzzznjng.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwpvbqaf.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zedaiikv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2itjvoric.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gt2dctjqgwq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2uecljemv.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2hxoymdsm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gt2ysflhsyh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gt2snwlowob.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2clitzpgr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gt2iskzzfxt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2dobnbtjy.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2zpudkddd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2sxvntntc.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gt2ybvgjhbs.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gt2alguwwaf.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2bqealvax.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2dvfbipfv.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gt2lhgrjkqp.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2wsfhfxpv.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2tfhijexu.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gt2eeihqaax.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqqvmnfj.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2pdcbhfty.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2fxvncche.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmjtcidh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2cyrepusc.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gt2fkqmwnhv.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2eoasuetz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2epcqghvl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2jvynjrvr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2yfibjzhb.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2yaphjvls.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2grczotxu.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2hylvivxj.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2mjwxmcql.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2ybiguvbn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuibmyn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2fnuqlqiy.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2haulmwhg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2qkdlkvmp.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2twqkqbna.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2nxouwkmv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2cwuhpzxl.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iszqwonv.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2ukrbhdkk.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2jpntuxlk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzojtpgy.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2dsqnixts.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2lptrszwy.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2zganlbit.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gt2lstoevkn.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2sueihzrh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlejyctl.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcmdmtlr.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2pelqvmeq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gt2wrgseuid.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gt2gafmouij.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gt2jjtxyrcz.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2qqczwnea.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2hpqukzzi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2qhswwzlk.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2wqwvzzyc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2ucbxdhch.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2ecbhthtb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2xxlxdxlb.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gt2kajxonrh.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2wzgntubv.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gt2ywiimahv.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gt2qligmvln.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2ybcxchiy.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2mzouocxr.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2dkxiiqwv.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2axffzwys.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkabayxs.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2roazzula.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2oeskbxeh.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gt2dqgtghra.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvexnqut.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2mavvtapw.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2huzylzlj.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gt2qmneqacx.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gt2ixaerqmr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gt2pkglwidr.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2zvlzmjcf.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2quubopyv.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2lpjkzbcd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2ncssdhcw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2huxwwujm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2fuqkgjtu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gt2gmbqstgc.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gt2esqrodvs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hugvisit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2qktyleib.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2fjfghrjm.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gt2zmwhiute.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2rsbfutjh.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2jnaehrbq.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gt2loaaxzuf.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2ihigelfk.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2wdqoewra.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gt2okmnzzhf.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2xtabnseq.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgayxkpk.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2mwympgec.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2fihesvdh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2toelbnhs.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2bpnjyexf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jtlibdgz.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2peyxmeej.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2wbrljppf.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sassbrex.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2coqsxxou.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2zkknijlt.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2tyxsxbbi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2kdehftod.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2cnurzwes.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2ckmgjblc.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2eqpavyjr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2nmukzgeb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uiusrorh.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2doetrqpn.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2zsaeyxaj.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2bjtirhtq.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqzfwhhk.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2bwzdshan.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2izeswhwz.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2fcuubsow.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gt2eflkmwlq.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gt2hwafwlxm.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2itfeakhw.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gt2iwztytgu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gt2ihdbbiey.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2hsumuhsr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2frcnjivi.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyekhpka.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zncwfyev.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gt2fydzybmj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gt2hjagczbd.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gt2cwhdmqun.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2jhwiwxff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2uitzydnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2lotwyyes.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2chrsmkee.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2blpowjgg.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gt2lxkvlwgx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2ugzalyrc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gt2lwbtcpol.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2nvwjzxai.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gt2sljhtqou.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gt2ebxjgxpq.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2hzxzqmtp.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2latzbyuf.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2lhaaiyuz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gt2lifudeio.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gt2uqzmkebx.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2ynyhiimp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2yzwddnxt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2lywycurq.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2pjhlaong.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jucorvgf.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2zaisqtcp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysuvzgjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gt2zzzkxemy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2mtavurio.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2wwrpwnfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2ifzqzjgm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gt2yafnqapg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2fvebxheb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2hfladzhj.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2anngendk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jirdhbjy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2gxovklig.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2rfxdwedf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2zvrplgab.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2nwymrlrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gt2pvghydmh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gt2nfkealgn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2ukatxhhi.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2izzumlqs.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gt2hhoulhfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2dlyjcgve.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2wiwomebp.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2auwhwmma.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2iwhyerpw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2survrkvq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2thfahaep.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2qsjqupem.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gt2xhigpqwf.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2ugpcwnrx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2moabwref.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2othduama.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxyhesmq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2hrkarnjd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2qpawiinw.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gt2ukxjityf.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2itkjjeul.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2sttutodi.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzvnwqfu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfrxgiho.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oblnmxyh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2oozxktrk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2bnjavqql.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnoilwl.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2clpnfvzz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2proooifz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqnyzplm.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gt2zwtokpyr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2ceytvqyo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2cqqjwfjd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2baifduhw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gt2fqxxkjzb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gt2hmnrppkl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2pjbbmtpm.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2lmxufcny.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gt2xehlqvyu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2tngxtmsf.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2theiciin.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2pcwmfixx.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2fqmrnqjd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2vpxeqidg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gt2imwgzjpd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gt2cwewelmq.html


<!-- 参考信息 -->