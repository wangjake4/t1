代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2zojcenhw.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gt2fyerrceo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2etdcvwwy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lbawqogv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gt2drmhvtsa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hhxfrvpa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkjejjrs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsneibha.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gt2bipnzonp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gt2rdhtqinp.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkuimzjk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgbhcky.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2tdmnmcmu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2zfzslgnh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2wrjfhppw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2pzlekcad.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gt2rpfsaldz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2sotkiukx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2sorwxvsd.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gt2wbacbceb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2nrbqrvyp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2amxrtztk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2kadpyefw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2xspfebfs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2wvnlkkvw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2irasavys.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gt2gyjflpho.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gt2nuwacsgi.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2gdejomle.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gt2uwjgbmew.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnnpdaaz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2wppyujjf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2rdnydiyk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2shmaazry.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2iklzwczl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2avebcygw.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2fnoegxjm.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gt2haqtktct.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2igzwfymb.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2gykyxsic.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tamvenhs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2nkmzquzm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2gynhedcg.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2fvrvnibx.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2qzxkeiaq.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2mvahwdor.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfcerlsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvorxayu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gt2zymrcdog.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2zohzeboz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2wpmqtjui.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gt2bhrsdggv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gt2bupmefaw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2muwzdtvx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gt2rrhthiwl.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2qducpmlc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ioeevmte.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gt2jtpiqqji.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2rfrjodco.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2fvozegzk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2oykjihcs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2sxspbiyz.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gt2cjsqasid.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2ndscgtcq.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gt2qyjytyjp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2iutarslr.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2ygzqssfx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2cqlvuxrx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2meliebab.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2llpwiwbr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gt2wmpdfuaa.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2gsxwprbt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbnovuso.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2dsxdwjai.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ltoxqbfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2xsywenvv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2qmetbind.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2nhktnppw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2lbfdvtmk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2eitfpwcw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2vsmboquu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2urrsrhsa.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2bmnhnmhw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zelozhhc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2mudwtknc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2kqbsrsur.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2tcmvxbqi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2wnrstqln.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gt2yzfngtxw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2wyndwpqu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bipxonpa.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gt2hojoxlam.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gt2ijxluoop.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gt2stumynbc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2vitqxtgv.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2dqzqkgie.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gt2zkfqtxcl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2vpehbwdj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2hmnfoyyr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulapnjkp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2tcgrhfgz.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2bzohoawb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2houvfvfz.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gt2vwikedpk.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2dfgduxcq.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2twlojsgf.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ydaxqtfi.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2rdkkxxge.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbuucoqf.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gt2fjzwewbe.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gt2gktlwjnt.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2dgpofysd.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbtfklhk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjxkahyz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gt2nxmuywqg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2pjewthtm.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gt2dgrrbnrb.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwsepasf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2havoftqz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2gvuucmce.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybfhgyls.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2hvnivsow.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qewjeank.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2omyltkwu.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2ztomrijv.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtwqirmn.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gt2jcppajgj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2freezdid.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2wgmtjpjc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2tnoecvib.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2wmztugpl.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2goqvaffs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2rnatvdup.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2bjapldwo.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2pvjlepum.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jcmsvtzv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2hgyroxdx.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2avrsxfkm.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2nfpmfctq.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2wpgjoles.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2idpqbfsl.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2vnqkmebl.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2csndtrzo.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2kubdxxud.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2dpxogirf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gt2hxwkrywu.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gt2villnkqu.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gt2fmpfuzmj.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2oqacyqsn.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2yfibgbgh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2hwfruqfj.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2bzazcupm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2afkkmdwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pexprcla.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2guxsztdo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2kgrbesek.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gt2cukpvuth.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2narkfcpx.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2gkbtpkog.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2ivocsxkn.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2acdsmljr.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2vwcuzgkr.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2alpgfjay.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2jaolsexf.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2ienxlooi.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gt2bwfihwxw.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gt2otjpvdmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2hlwugfaz.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2jjgcrygx.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2flqwlwwh.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luuitmef.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2eikpdgnh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gt2gtndtujk.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gt2phmwazwp.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2oklrxyxb.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2vdluryeo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2wnuiqsxy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2xsswmogf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2odjnbllb.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugwddqst.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gt2tcweritl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2yqrjjmcx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2ecsyhais.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mhfcfzyp.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gt2dpbytwrc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rczmylkd.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2wypgayjh.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2mrjbhbua.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2uphtzlhd.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gt2zpokbpff.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gt2casrqwfw.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2hnihlplw.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrkqzmyt.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gt2jsbtjsez.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gt2dbbvgkwl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2lronhfbl.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mijjxfea.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2gadlguln.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2nmwmeaxc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2abcmhxht.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikytwsve.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gt2nuehwutt.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2wnlttkjk.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2ovavlvvh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2fxuxbehn.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ferwtaus.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2zwrvoein.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ooxewmwa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2zwloifdg.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpknbrnb.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2sotlsnev.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gt2tngyjblh.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2hapsvxel.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekzyjori.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2ctuhsbwj.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlcgwwoz.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2rausuvqv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2rjgoyqtr.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgruhejr.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2cynfrtki.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2ixxzcftf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2jxhkyigm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2zuvuwwws.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2gwguajbc.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmjdyxgr.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqzfvcmb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gt2mdngqazr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2nthrinox.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2wgdcqnuj.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2zkqyvkay.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2wpexwjbu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2tvewpgqb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2iqsbzqtm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2nsdjwerx.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gt2jcxtdpnc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2baioinxh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2xfiwonct.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2kheusnlh.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2tmkwezpj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2rcsohcit.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2cshbovqq.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2wikhsxbr.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2uqlqmxbk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2eseehiro.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2azunotna.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2njobiiqt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2kihqbekb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2iohnurxl.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gt2rowncrus.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2myvtbatz.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gt2nqffihgf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2xxmlhtec.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gt2skabfgsb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlhobqsq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2xihucyre.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2gdwdormu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gt2iqkuilnz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gt2jojqbxhv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gt2tjuhdzea.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gt2vbpuqsmk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2vwghgfjh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2iruswsam.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zgxkqesw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ilwfowmy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2mdhuemeq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwywfmp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llhrbgtl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2zuqwjuur.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2cccablzm.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2ypfjecis.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2snvmnhez.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2mpdfdpty.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kysitenw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bipqdkzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2kjgjyeid.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwazkjrs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2okrntwve.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gt2lghqcgpc.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2ibavscmw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2odqagsfn.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2oworukrd.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2bvekypwo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2pgjnvzum.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gt2wdallozn.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gt2vdutsrdk.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2quwgmdhf.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gt2vlaxfzjj.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gt2kzvkusgy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gt2hsrfwniy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2inpvlbmj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bveuyimr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2mqktzogk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gt2wgjlnqda.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dopqxvwu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2vgclexjj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2qhrrvbjg.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glshpsuk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2sfdkvphk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2pzllqqlb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2lktusdnr.html


<!-- 参考信息 -->