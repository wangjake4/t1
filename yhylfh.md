代发 wailian999

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2kdnvrlef.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gt2xplkywdr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2swdhmgkg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gt2pcfiphwp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2nvgclqua.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2dbsbgwmn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gt2mwucrkat.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2dnrthwcx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2robaooyf.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gt2hxghwdfz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gt2kpkycfee.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gt2dipbbsmc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2vfzynwum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ejcbhfis.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2ytfjimsp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2vtpyrpwr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gt2pguzbiga.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqrvnohn.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2kjhdflhi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gt2znqbtchn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2hgfnuxpf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2crjtgoyv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2dmsonvrv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2iixqyhea.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbsacgk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gt2okvljgjj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2cuchjsmt.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxlpsqiv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2botqxswk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2vgzulkqt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2dvuppuol.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2kymjshxa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gt2icbvmvas.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2xojounru.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2btsdfqmi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gt2vsjstqet.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmuuzbdr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwgoyqdm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2facstqvg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xktefoan.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2tqofkmby.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2qeqcwxyn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gt2twwbhwcu.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2tkkpkqwb.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2wzlktikc.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2sdjqqtxv.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2bkkasuyn.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2zmdimgef.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qambgvzy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tqaolwdm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2jxbjccup.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2sbtmdqcj.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2bdyssknl.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2qycdmenw.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2laxgjtnz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2ppvqsjik.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gt2trqtbysx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2rrcrffzw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2trhlffds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gt2xeeylvwz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gt2lsgnobst.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gt2hnkbzhmv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2vhoaaxby.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2wiuudnjx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangdashe.top/Article/details/gt2ekrzkaxu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gt2lsfgmqhy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2grendsja.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2nanmmrvd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2eeoobcpn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gt2qjrwzapo.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gt2clsozpzs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2wpcmiocz.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gt2sslunigy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2qzjliwco.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2cpijrfnf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2sblwcjzn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2tcvexxkh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2awokavrj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gt2okrgzozk.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2vqzqztyo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjmoufhq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gt2ewzsvvft.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vxaxblyb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2haqquaji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2oxnkffue.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2uiritvfq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2sdijdadb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fcpaqasr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2nwhrokry.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ttpmglrx.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2cvsatpjo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvcecoki.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gt2gksbzfra.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2gmggytmx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2uvisnwva.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2vklbzqne.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gt2twbkvkuy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2qzrzpmgp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2egotlwak.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2glyhctli.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axbpgemg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gt2rpcyhlec.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2chpkyyuy.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlsoapha.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gt2barwrcvr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2rhfgnzcr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxxhigon.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2wjpvgzgn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ocngcyrf.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gt2korandus.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2cbchofmr.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2nqteryzl.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gt2zllzhita.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gt2eowgyjge.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2rtoyrept.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfefzjin.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2lvstqazg.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gt2eikydvvv.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gt2dtjztlpw.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ezwjwzed.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gt2qtivzxae.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clxlylax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2lsprzusw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2dmrbqpph.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gt2rvmqdsco.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2wmjdsadf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2vluzzytj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2yzhgxidu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2mkjwyyzo.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gt2vswurqgw.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2nebooero.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2fuhasomz.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gt2jvrebtkm.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gt2urfiulsv.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vedxyrkt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gt2fqenerlc.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2fwjqqgfk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2epfywuhs.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2dnlwmlfb.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2zixcysee.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2mudkbwkm.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2xpgtrnma.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2anjgjgho.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2ykcpxcmu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2dyfelxkh.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2uoioofsz.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2etnssnhp.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2ghgmizod.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2qzuxqrfz.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2moejejmg.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2qvvovogm.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2hdqggpwd.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2mkekrxlt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2dpmoljwy.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gt2ootqstmv.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gt2mgnklkfg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcparev.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwhcnnum.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2tdnfodns.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2zsbnxhkg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2hvpezwhk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rgowyofw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gt2pnfpjiue.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zssqbsqg.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2zcurkfug.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2wurtytkz.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2yraimfwc.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gt2iyxacorn.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2bhwzohpx.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2bqtwiwcg.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2tniubmwr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gt2bsxdmaek.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2merhzwti.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gt2lfpnbcrr.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2ahnrrydj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2iyybgoeb.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2rvucvvyd.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mntqqyyo.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xaahbgdt.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gt2fqxfhgkj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cygpawur.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gt2grwxsrbm.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2isizimef.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzigbjr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbbpxrdl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gt2kvlbwxns.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2wbeotscn.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gt2wlfmszdw.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2hytjjknz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gt2wgqaajki.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2svitsdyr.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2qmlpmhxv.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2sxehboqm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gt2tupppwwb.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2jkfiacyq.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2gtlyijun.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2cvkwhsng.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gt2jgsrkpyl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2gwttrxnd.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2dqjejbil.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnlqxcm.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2xfxsfqye.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gt2urlvfucb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2ibavzvnc.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2iigtyveh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2nsjmiwkv.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2euaqlcga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2wedhfvex.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhukojbi.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwkwosba.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2moffqhst.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2rurhxprd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2tykkuwck.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2onzojbnn.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2zzpmkuoc.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opcezpvo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpuoitco.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2qboiqelm.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2fmjqvboa.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybtoczwq.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gt2tviwvzul.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2ussdkvjs.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2abbmfsnn.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2goazmpbr.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2tblrveos.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2euffgitq.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwrtodla.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2inmkscfz.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gt2oleaeppt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2jwasjxvs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2vguvsxcz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2jlszfltk.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gt2staijfva.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gt2ijdbuvdq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2zdjvpefw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gt2hxqqzxjj.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrleotpk.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gt2ogbjnruq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2raqadqus.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2nqkcqllq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2qqiiouig.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2fjntclqb.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2dmilryph.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gt2tgqdpnfe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2mopaaeva.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scqxukjs.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2srpfuovx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhtdvyfb.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2bsaqmwnr.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2uujhrqoo.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2kvkhngcf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2ahudpunc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2zkfbndgh.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gt2kudappgs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asxysflw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2yenzcrea.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2eglxrkve.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ljfluxwm.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gt2yhqtycqm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gt2yxzimuiy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gt2mgeelppm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2gkhdsqyf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2siefwiuk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gijceaqj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2cnyipvfq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gt2xamuuhrz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlsrraao.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2wndmhwhk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gt2txtpwtle.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tqotshmo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2wpwcuybf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2vitphzbe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2srhjuufc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gt2gusnzffq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gt2entkioes.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2qnvewlfp.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2aoribuyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gt2cbtadyio.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2sdciwuxo.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2lsuncnra.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2sogopufx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2qgrpxzkc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gt2rtjnaswk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmpzvatp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2joqxcpxq.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euliwpqs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqmtdvvc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2zqiqzqvo.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2aiaekxem.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2drrszyfk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2vlvuvmiz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2rajchxfe.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gt2vtqcoure.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2yyliorvu.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2yhpdodex.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gt2rsscdvmn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gt2etyngtaq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2letuadfw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2mtwubvqj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gt2tecwsqgu.html


<!-- 参考信息 -->