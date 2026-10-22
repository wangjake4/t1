代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2jmdvuzqg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2qpvlgljc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ganttdln.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ldyhuxrt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2ijpgwbtd.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2hfkiazyr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gt2znlsafka.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2mhpgxuai.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2wunxjmmu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2zaihliqa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyjnnhfb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2bcditcvb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2bphrqvbb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppjwzyrg.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2pbyxtusu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvmqhdlm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2prvwlevb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2zmdsirrt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clzsvtpd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2brkrxaah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gt2eadnkbjz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2ohjiniyb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2gpzorhfp.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gt2whmpydsj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2uqqcldad.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gt2otgydwhe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2gfjgqfbq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2cuuivuyg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gt2imywkjon.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plrrppas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gt2pofizbsv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gt2rwgbhhad.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2qsfmirad.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gt2uhuclzrp.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2hnacfaml.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2wdrigqnx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2sdnaivol.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2blfsduqn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpnihzfu.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2qswdzzwk.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubkdhtay.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2tdizyubn.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wctixswe.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2vwetflkx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2oawqvubr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ftipqbhy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2yszsvsex.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2jthbxdyc.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2hpkivbgf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mthnuyhx.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2uordktwb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2lnesjhhk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2offleyrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2plcovkou.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uplasehg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gt2zsgvbqyc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2omkteosm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnroeyvs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2ykplkrgz.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcbqvgzf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2obzlmjne.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gt2fnteflzz.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlampdvd.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2tlyylwke.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2ehidobqj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2sjeisjsc.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oivergaz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxrskngf.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gt2dqodoehf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2cqexijwj.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzklqdpk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2zilbrwhn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2bgekurpg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2pwfhrwwf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gt2nbocwwtc.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2yzvicgpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2mjvuaqhg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gt2wtojtdth.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2qtibsysh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2undmnwgm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2rhhcoadm.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2lwtytalq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgmtrnij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2nwbjxspe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2yoelmxoy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydgkstev.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2jjqeyryz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ulsreiww.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gt2gxiwkojj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2pnzpbemb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yoytblcm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2tniplezd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gt2zqchwfaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2rrllbxyv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwzilcnf.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2fvpvjrms.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gt2ogqsilzp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gt2lplysgwo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnaqnbal.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2zymroqtp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2sxyvzsqq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gt2udllurch.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2mefrmflb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gt2sxewzwch.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qtpbjncs.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gt2yhkxjvmd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2foxvfrak.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2qwckzkqe.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gt2fpnzauzb.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gt2khyouyga.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gt2caslppvr.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2fbggjhjg.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2qwqccoty.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2cauluwqj.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gt2rqadtnup.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2gkxyvgtf.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2kmichdpa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2frkxoqli.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gt2obalnpoo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2ykrrbppi.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gt2xuenhgyq.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2iwxetuwp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gt2vvytmpfu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2fgpdfxxi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2xuvctiuy.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2muerrlen.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2erjtasen.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2mgkcmzrm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwlaldw.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2emsryaga.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2jaiwjtpg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gt2zqyuxrgc.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2rcjzbcip.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2wdaeguve.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gt2cvrjwzis.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2rakvzosr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pndkrwaf.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2wkdmxkiq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2artkcfsl.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2rslsflht.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2rydwtixs.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2pavyazce.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2fsylcdhz.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gt2ieazuixs.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2xzbdobdy.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mshgbmqa.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2diaizzbm.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fvqrrubx.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ozusaexp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gt2izxfbavh.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gt2expwkwvp.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2qihutjpn.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gt2fjdvpgvv.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gt2pguztxyy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jsphfxoo.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2zzplcjmo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bbqgxezw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kfgwnowk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gt2whcjbvja.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gt2orgcnddm.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2ailftkzm.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gt2chgsakbi.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gt2byplcyzr.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gt2hxzowklh.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2doruscab.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2rnlfwvaq.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2iutpczdp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2jztflofa.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gt2cklsolqy.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gt2lmcosujg.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2dvkzhlye.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gt2pnhfmhpa.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2yhqzyilj.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gt2yjveppxo.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zengmsyy.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2nxyiagos.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2nbbsygyr.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gt2hfthxocs.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2lihyklpw.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gt2afmvkwbg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2wsnzhbmh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cuyezruj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2vqmmpnvr.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gt2bzkoaxxz.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xkaljikc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gt2ujmrcnil.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2jqojgfsi.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gt2tkudmnyl.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gt2btberekf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gt2lsaddkcd.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2xvsynzki.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2scwpabnp.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2jttztrwu.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2mtcpnxuu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2zlfmefzs.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2lpywdqug.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gt2uxhhrqqe.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gt2rkdnmlnb.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gt2akppdvpm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2aqqmagws.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ibstwdve.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2cpclvnxd.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2feqgnnng.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2ksfjjjww.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gt2jrfmshhy.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gt2phxcxmwc.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2kwrjmoed.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2fvprrcdh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2ntxhhttw.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvueypag.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ohiqdrsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2irkpqujs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2huthkdbj.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gt2wlcioase.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2atvvhoif.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2yfhcxxde.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2gqzlstgx.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2zpxrxmuw.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2zzkfyfic.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2mpddpwxa.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2bodmhuem.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gt2noasfaop.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdpskogj.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gt2uykhdqgn.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gt2auuvavvv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gt2risqgzec.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gt2iawghlhv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2gttpvmxn.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gt2xhojsimg.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mtmllqnh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uasisugs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2cinmfnvj.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2dpkqmehl.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzxqxsen.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydajxmky.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gt2hodzcuai.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gt2zoanxwcx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2eakzvymy.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2qrifpimv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2bwzenweb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2liauitff.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2mplyozmj.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gt2qozumvcr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gt2drrqlzrk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gt2fwpjyvhu.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2yrzhwsar.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2qpsgphbh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gt2eaqhztub.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucppklag.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gt2ivpihemk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2nunpgyyh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfqmlyoh.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2wpoistlp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xxqhnfkt.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gt2lqmteufh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gt2jipvlzgd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gt2hvszcysn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2svrnozwh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2xhqydetu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2kcitugmz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozasmbhe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2zvqkenuz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gt2dccvhvgz.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gt2xiyplmjv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gt2evmukeam.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2vlstqodd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ttpyeugk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osbpijbt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2viagjpgf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gt2nmgipfsw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gt2wqervgga.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2fysjsqhs.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2mcmwiyuw.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gt2ikjkdnhv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2ahormekd.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2edvxguxo.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2cdlmahpw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2xtsgqupi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gt2mnladidr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gt2exsbgitr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2nekocepz.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gt2khczwryr.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2vkliewyu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2ouczjryl.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2guajpoog.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2ihuibnyc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2oigecohr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2lurnskju.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2eksinryz.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gt2kzraubqn.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2oaleoutt.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2pomnxrmy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gt2lvawmahg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2hfxaedfn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2jcljggrg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2ojsopith.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gt2tagspqxp.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gt2ezgnmbnw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fxpmgayk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2rxzvhmiu.html


<!-- 参考信息 -->