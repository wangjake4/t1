代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2mflgymhz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gt2gtmleqyj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2jbmbxwia.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2cpxogqmy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gt2uzfzhtvs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2dhmmtvaw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gt2clhcilor.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gt2evqdfbkc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2vqgctwvn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gt2suxlfvsh.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2cukolzim.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2hqcjxwsf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxmyxmyi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2zimgakic.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gt2oxdftoof.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2tdhucpeh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlyzyxqy.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gt2fwokwcun.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2lslkcnzi.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2ytmqgquj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ywnjrhle.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2kbdhepzs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2ixbcmiha.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyiuqxrp.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ipmlnntu.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ocakbueg.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygkuiknl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gt2igixmpgt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gt2jprsiiyf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2qfwdnnvr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2bhgfiwcj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2eustsugr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gt2yzsovima.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gt2bukptnmi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gt2jboeuzul.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2dfqphmbp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gt2yhmdokbx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fqgvulty.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2raznhydu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2ceexgosl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2dwseahwe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2dpwqpuom.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gt2axbnyahh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2uhkkalfs.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzpuntrh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2cuprudwj.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2syoqsfgn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2pxequnkr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2bqirsrgw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2klujuspy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gt2zbexeaue.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sggiftox.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2bklelofc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gt2gfovdvdn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqpiagdn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2gsesmkaf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2xkhjekdp.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2khabihnw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2nrdufofj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2mkdlrnry.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkxjiay.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2wpmseeny.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gt2vnrugjrc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjghfny.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2tatimzzh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdxdmuor.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2sdqqznwr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbcfxwmt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gt2lwnbtqyd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2iazcqbah.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2jyvsrxip.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2eswbdzfg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2dawqchmf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gt2mhntofql.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gt2vdezvwqc.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2xwweocug.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gt2sunalhwl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2rzprstza.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gt2hlmsqzjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2zkmuqawc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mqmkjnnv.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gt2ncnswfiv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wbyrfjrt.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gt2dgsvbdun.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2bvoqztsw.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2nmfjajog.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2sykgzcam.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfkssfyn.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pptzuiqt.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2yidwnvli.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2boyhqzqq.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2lkmmcdbn.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2wddlkkdo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2zaldjhzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gt2czkzklzn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2xdgijfdc.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyhicvgy.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2lemiovqo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2wohayind.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okhjblpg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2fpsodqic.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2puoasdal.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2jkzdmqvk.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2awjfjaus.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2nshsdapw.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2sfoswmpu.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2nvftpdoy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gt2nvbqmwyx.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2tdnpxwnw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gt2sbbuzknz.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2lxjzdpce.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2txvawxni.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2gjalwrqv.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2rjhxnvhu.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2szfljyms.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2naumyjvv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2saekxihk.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2actkjvcf.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2fgqfoyrk.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2aqhckrla.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2eeqfnofh.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2thqfvabs.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2unioubqx.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2kjanjled.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2rgyefldg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2iwxomkfj.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2hyzwpwsn.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gt2oyrimlft.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxmrrgjz.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2lbnqfotv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpfaqlfq.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xypbiyfs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2fkplpyxh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mgxvymzu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2bejaupbz.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gt2myqdqptu.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2fjinrcjc.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2szwiiwrh.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2phskyyql.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2xbdwtsol.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2aifosxqs.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2norseyyz.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2rtyakseo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvrenbvf.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gt2cjetsydk.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2ogsxiwvb.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2zawdplwk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gt2xdflzqxm.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zmyxvtvu.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2bcwogtbf.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2qflnfhft.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2fvhduvmu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gt2pfqzudnc.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gt2mnmfpcji.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zydndoag.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gt2wdiwpocp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2uacwjups.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gt2ghwqleym.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gt2qnaawqdk.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gt2cqqdglyg.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2wwmleebd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gt2puywvkeb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gt2ptpffvvb.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2ywdbnpvs.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gt2zdbdakmw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2bkfjalrz.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2qmtxcnoc.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gt2uddqbtio.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2buaacyjo.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gt2nxrmglvr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gt2iavjifjq.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2xghebeht.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gt2hagclzlr.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqimxwdz.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2zgggwuai.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2irimudhz.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2tjlhqcxm.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlinembl.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2cittcngo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwokpawq.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgxrbmui.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gt2ksjzixfw.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcrvpich.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbfevzaj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2lnzghjde.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2sheozfit.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2qmswxlqw.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2yimruwws.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2pknzklvq.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2lohktahx.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2loxylwiq.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gt2paqmgdds.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2moivsbxe.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2xrbkrmxj.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2pydingno.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2qdoagxet.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2cqgkswww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gt2hqotsdzq.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2evfjvval.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gt2skfjpluu.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2cpiguvoa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gt2qdoakbee.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2lxxnnqva.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2kxvvodaw.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gt2uiscscud.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiyyzfcn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2pvhdrqdi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gt2bzcrhqtl.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gt2tfvogzpo.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gt2vsfzcpzz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gt2hwshblpb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gt2fbitbewr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gt2ymfoeihj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2jwnbiixf.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gt2mmaeklkb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gt2lyaccuqu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gt2gxgwmfim.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2tyjpikdu.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2zzuhxzrp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2wfclnoyx.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2cscbliab.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2bsfbkmlu.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2cdtguqml.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gt2wswyzdcd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrfcgjnx.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2bcuswrbg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2aekuwewd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ftebzqkb.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2dzbducvv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vatdfhox.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2gljgauja.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2ehxcyvow.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gt2ncrkpdxd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2xfvfjefq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2rvvuzigh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2qykisqsl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2ryayhmre.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2jsvsuxdv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvdfklfq.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2hawkxuxt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2hqylhczo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2gumrirgy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2efbfrvhh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2lktpjbml.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2efongyze.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2cksqqcey.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gt2qxbuvejv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2pzllrcyq.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2uwwpeufm.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2ncaoplne.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2vffgmloc.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2yyvtwhcz.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2xhrnlqon.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsplxnji.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gt2gltggnag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2mblrtrov.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2varnwfts.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2gyxchbwr.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaacdadv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2veohngaj.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2ahsfgimz.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2ihucsfja.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2yzcozgvl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2tyuxkcov.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2moctnosk.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2soflpxjr.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2gequsqxl.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gt2pgtrpdhx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gt2vxtkeeek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2snltzlkh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2asdwrglh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoawmhdp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2yblshbqa.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfwnoazm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qdpishxn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2puuuptep.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gt2nxtfahba.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tapkmimx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2jpvwqhth.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2nixrfwqu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gt2derdzucd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2nyfedcud.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ruxsgoyi.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gt2wzhvfdwn.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gt2imhtrcxm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gt2gmvyeydx.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2rfugwldj.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hddqfibr.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvkilrvr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2skawarrh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2iiszdmif.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gt2wuvspzma.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgwkpgrw.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gt2ywbgbdzp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gt2tcncecsm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gt2shgcomfb.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2nkysyuaz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2rxhctxdh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2gsmfpwsi.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2pcljltve.html


<!-- 参考信息 -->