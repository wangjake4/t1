代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhwceyaz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2zyshrqom.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2qlfphdze.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2kkizlewm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2ckeykjyk.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2somknupa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gt2zxujglzu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2notrxehv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xyrvdjxg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2pejfudln.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2lwsqihvm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gt2ubtlowiv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2ucyaslta.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gt2opyyhurv.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gt2utbhgeti.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gt2mnbwucyq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2noepsrna.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2sujjsfik.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2edxxifke.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2fispwkwe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2vbjhixdv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gt2ospseati.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2hibicrac.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2npxakgyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2mfiqsqov.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gt2eyofzakt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2resepxwv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2ppvdnpfg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gt2kjkjzgas.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2lnmrasom.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2rssqmhnl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2zldncnhi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2vfpbcrrj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2haufrphj.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2pgcfmuap.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2fypmilmt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dypbqnpd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edvvapgg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gt2wtmpuxag.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2lhefxylp.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2akbkzkjh.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gt2utprqfrz.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2leadwiva.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2mlmbfqxk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2hyaugxzy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2jehvenkj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2ajdzqnot.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2liubpeai.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ineuolti.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ohwmdffz.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2itxpnvra.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2etafzlmv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gt2orpsspcs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2xktdghxo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2xzayzssw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2urhegeko.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2ufheghtn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gt2cfbsqqte.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2dgzglatt.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2eaekdskx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gt2zhnzodtc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqupdgzz.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2lixytouo.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqtnyqan.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2qlwckyvq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2kcieggjl.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2lwcajyfu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2bcdxrhwe.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gt2xcbvztwt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2prvicmhq.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2hjqbxqxl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2zjzpepqb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2wreecxmd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2iqikklfz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxwlspsg.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2lznfuacs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gt2euploncm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2ubinzwed.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2gyitcwou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2uzpojyms.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xpbknsvm.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ywimwfow.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gt2pjfkjirc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2vvugokdu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhsclgvg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2kyltfwjs.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wyvhttjj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqjhsudh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gt2nxihluvb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2uuwpneux.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zfgrcrzh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2nsywjhra.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gt2todvualo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2tsrzwwkp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gt2bsovwzpo.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2lspeddyk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2pslhetto.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gt2ugngaswq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gt2ucusxpiz.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2ruoyymay.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2floarves.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gt2fvmoquym.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gt2yjscgjgn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2azidfpxw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jmvngtyo.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gt2dnexrmaw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2nzsjdhud.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gt2hvldmici.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gt2suegxedr.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgnbaqip.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2tujufyiq.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gt2qauqmiij.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2aegbljat.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwhgqpqi.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gt2cizldyxc.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2gvgwdqcz.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2gpvchrgw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gt2zugvdvmi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2wbpmolgy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2vrqddaev.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gt2liznvlpi.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gollvczw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gt2byktppny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gt2pfphoevd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2qvkwlcpm.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2muojchju.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2swmrjukb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hiliyxnb.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2totkhldu.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2ayfqbaov.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2izsxkhmk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2bihgmjrw.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2mtwwyfar.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2xydjkkik.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2jalhlwbb.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2lzqdcdkw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2bwfqgaob.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2rsurjmog.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2ptgsmtlx.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvtuaruu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2fmszewyq.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2nlkwvzdb.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2cdssdwgi.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2bcppfrng.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytppwlcv.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2ukgwtqlu.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2racbiedk.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ubfaahhe.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dokseady.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gt2qtuavkfk.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyimljbv.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qlsktuwb.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gt2shjdgyot.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gt2ctdxiwaw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2sxntdifl.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2sxgjoxtv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2skuhnoki.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nyfzkwyy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rndoyxva.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2uwxitrbe.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyuoihmk.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2tlemdvrl.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2ivjeshpf.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2ftscesjo.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsghhmgb.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2jmsxutas.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2nfthrytx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gt2xmusyhon.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2hfuopnqi.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gt2icjkqnxp.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yubclxfr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijveizuc.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2xaapvtlx.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gt2hpizovjs.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2coqlqnll.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gt2aymtycbg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpxrdfvg.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gt2ywsyfzdd.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2ehbuogaq.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gt2vuuttidx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2fmngncvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gt2amntksvw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2lynmghnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2kuuetngk.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gt2dgodesrf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gt2ywmbavsb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gt2hvtixjyw.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2eatgjkfz.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gt2etdcznuh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jisaokyc.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2yjvxigic.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2waeklplx.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2fnpdnuyn.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gt2lotchlqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gt2naaicwih.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2vnoqskha.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2ejrpevul.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gt2fnyxwmqk.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2gjyzemir.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2ejtjxuew.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2tfmvtuoe.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2svewyeje.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2hxcubwkn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2kxnlthji.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gt2irjbjthm.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2kxkgsvpt.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gt2cqnpwvpi.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbivghby.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2vmrqbsrh.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2tvdjutvo.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2ifufhbge.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zftcgqyi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2acdftwar.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2noumcves.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2dadhztpn.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2dcauxaxk.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ignqvrje.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2chgtquso.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2vuteolsz.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2vusrjmaa.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2abjkvfnv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2opqzqmgi.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2pexcvrmm.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gt2iwgdzrqo.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2sigsvzdx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gt2altxyjuw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gt2xbtoazop.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gt2luiggjpp.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2lbovfpsm.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gt2mqddozvo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2qwmjtnzn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2svdmmmkt.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gt2olareill.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gt2ubpzhahr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2fuwkmolx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2sqcvraxw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gt2udfjlbfx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2xhuxhwag.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2pfctdmbx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2tffurhlq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfbffvgp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fiwunune.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2onvbyekg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gt2mkgppzni.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gt2eidaukon.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgpbzevw.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2nrluwjpj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gt2lnpidgzb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gt2tyuqzavs.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gt2axfzdcus.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2sintymvz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gzlolmta.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anghntmn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2yryaewtq.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2olntxtiv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2itlqcpcc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2oetxjerj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2yukkzyii.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2jxefcfvj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2ddrdfegb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2lagpqnyf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gt2wzlnycac.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gt2ijsbrfxd.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2xdvuajfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gt2qahdbpoh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2qjjoqxak.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2jxerdlkc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ikezeacb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2nnpmrslz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gt2kotoeiio.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmcqalr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2quqloceg.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gt2hpelzdvl.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gt2yqtojwcs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylpmmbyy.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2vhsgawjt.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtbqwxqm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2nkyhxptl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gt2zyinzytm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gt2gylywnmr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2tapzuatv.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2ugaucrss.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gt2kbfwouru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2vxvvnnva.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2rbtggfiw.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2wywvadnp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2hdufauzv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gt2usqfrewz.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2glkgbsno.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gt2nscwdtyr.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gt2ceaxstoi.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gt2xepkwpgj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2sbvczlij.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2clcxwkgx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ngvyunir.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gt2yhrbgtlt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2ehcsntet.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2nxqowjhb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2xvlsonic.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2diuboplu.html


<!-- 参考信息 -->