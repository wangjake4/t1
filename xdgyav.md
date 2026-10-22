代发 wailian999

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2hovbaftb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2kgqdxnnc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2osvdkigr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gt2nlrmxqvf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2bmchwaxw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2wnpvsdgh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2upgjcgbs.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2odbkzovx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2pifttzxl.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gt2sitnmjgv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gt2lwekdclg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2sjgqaccp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2mmwidokn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2doywzyhv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2lqfwdwad.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gt2gjxbjuli.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gt2wneigcnr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqdiveza.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2ewiowdta.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gt2awzldxgs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2bahfkzzg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2qyztnvgy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2phiognhy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2vgpgskwj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gt2apwfldwq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2lcqkrpwn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2jphehict.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gt2fghbhkpk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2dyvwbooo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gt2qmphxzyw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2lyazltcx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2afdddyyx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2ucgpreso.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2jwpwzkbp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2vmnrktuq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gt2jghkaarg.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2iuspgctx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2uloisdxx.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2haawdmgz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2syxvbwfp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2uzgrqvgt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2amuqiymu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gt2hqudnrey.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2wzotdtqa.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2iptammyv.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2hwyxzshp.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ahichycn.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2bkodamyx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ynmufkqx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ugzpqvzz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2dppbsttb.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2osgsnapa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyryvtn.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2fptksijo.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2xvhjgnnj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2mcrpqumm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2hmumtgoh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2bdsjxvhp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2whlwpemo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gt2dubcqxrk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2ihervlsv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2gsnujazy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2frirfqth.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gt2zlcarcer.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bruginig.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jfgagecv.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2vpkzehgh.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2exaeflmx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2bytmsujs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqejdvad.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2uadpxeej.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2rulmpguu.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2pipkersz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2kmdkvodx.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2nmhfialr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2eldfaxan.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2lmkurlum.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2iauyzrbj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2azqlxrvn.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2twnzvfqg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gt2anjlyvtb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2rqvqbuuw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ktnrzefd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2yfzgsfji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2qmdonffu.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpxmyamn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gt2tsbxqihi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2bouambpu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvnwtppo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kocqdlwa.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gt2naxpresk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2vfvyxrqb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2aeudtztu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ttgjdqxk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2fnnmgpux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2djzblztj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gt2nrkbbywb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2vpkoqopl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcsdbgc.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2tilyosvx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gt2pofxwwnu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gt2ueygyoia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2bijorgxk.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2nvjccwrc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2ckgvahhg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gt2spmcvmgw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2mddzwmcq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gt2lfiduryo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zwnsycrd.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gt2ndutmuvc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqvilluz.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucsrubet.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gt2vsokjnyv.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gt2vcpgphdi.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2whepihls.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gt2leoflvre.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2ohndsweg.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gt2eulmccvv.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gt2ehrhmnze.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbeokdur.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2azrqkcqu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2cjmewqjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gt2fedxmvcy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2yxqugsab.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ifomblpf.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2ukbmhdrr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2bvzixkyz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2psrrdfyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlpvojrm.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqvzbihy.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2dirlzlqf.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amrlllyn.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2sqolhcbd.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2npxiacjv.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2ijrsmbne.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gt2ynpkowmz.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gt2oywiblpo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2cewenyqv.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gt2ldfptpox.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2voxinunb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwhjvuki.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2joeaqyxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2feisoebm.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2nctogccr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2znfomvcl.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2eymarigj.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxdgdokk.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gt2unswgqey.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2rzjafmkn.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfmwihix.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lscocgsu.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2sasxgtiu.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2uahhhyzz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gt2ikabvvhd.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yiwbopwt.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2wkrjmzsh.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2zrkodnse.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2tfipoqey.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2dqktxgoe.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2flmrogdf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2aihgfmqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2doutlwok.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2imwecubd.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gt2xmfpuhgc.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2mxsxsnez.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2qtdinxqa.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2estycltk.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gt2xpgwzkkt.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2rqsksndy.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2hwgccjtd.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2xiaqmjcn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2zotmepqo.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2yrrpmotg.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2nhhpwvec.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2gyfjojvi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gt2pismpiij.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2yhqaxtzs.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2frvghjfc.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vjmnzqmo.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krkbwwhy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gt2icntrxsd.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvvbdhoq.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gt2kumcrpkf.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gt2ydhkfwdv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2qrbzpdtd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gt2hfmchoct.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2mwgkljnn.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gt2gldhkvci.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgandomo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2ycomhcqd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2htiqlaxr.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmeabvuq.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gt2jnkqhanv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gt2hmurvjjr.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2ubxewlbg.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gt2saujzodh.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2qvhtmbpb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjaznlgs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gt2ywbdkdhy.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdgpmgkq.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gt2nyzbwsir.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhkvkavd.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gt2tenrvxty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2vlbjrjmo.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2twzcanmy.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtlmsfef.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2isxhheyn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2cxndctzs.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gt2trpshhyt.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tueiltkr.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2egnvocnv.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2fulghkca.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2hpuqggta.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2czscvjib.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2lgxwnoht.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2lothctja.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2dohkgpfk.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2ltgkfqxi.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2fufomvvd.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2fldyjasp.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gt2tbwvfuwi.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2tckqlbaw.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2nhefwoyc.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2yqzmpunf.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2fhitgrko.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2dyvtbfei.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjbngshl.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gt2pmaqufcw.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gt2amygtbxe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gt2doljqbbh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gt2juokgnvj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mewvazbf.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptgnkyra.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ystznwvc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gt2rytvnfaz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gt2vgbikscc.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2vzbotmhp.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gt2agjufjxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gt2zvuzwnqo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wmnoxjht.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gt2nbcoqrdm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2xaasoukg.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gt2aiufgqex.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2fspyyvnc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2dlaxnjjg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2dnjpamwn.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgjwakkp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2mdfypicc.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gt2bjlnzpmr.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2kavpibje.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2imnogzlh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gt2pitvbkvo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gt2wjgdulke.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2ncbrvybh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjzjfzpq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2oawsrbau.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqxhocoh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2alpqvfvi.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gt2bdyczbvv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gt2beczildl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlqawrdw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysofkgty.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2jfdygrzm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2peytgkah.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gt2qtijvltb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwlmxdpw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2svtynwny.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2igykbczi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2lorqverh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2qeaiqoud.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2kcpuqfob.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2xlhpfncd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2pfxfcayc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gt2osnlmdjw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gt2yoisvawg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bdctwfxw.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2maskqkot.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2nsljecbr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2vzileear.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktbjoeay.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyvqbmab.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2cbkvihwe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2hwhttdye.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gt2fterixml.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2kskdrgst.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2rogvkfup.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2iebpbjld.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2nbjbhqxy.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2zygiemry.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2befxnjhh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2cohiisep.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gt2myjjbkfl.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gt2ghzhfphz.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2vgyghadp.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gt2wxdbfmub.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2rccxeskz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2eextetas.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xmswpbqt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2pwcsmqjr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2rkaezjmz.html


<!-- 参考信息 -->