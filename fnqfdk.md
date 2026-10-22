代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2aojergpo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2syocrbck.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2mpxmzcdh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gt2jpkvaoss.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gt2pszgomlv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtjxyoru.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gt2shbnlsxl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gt2voegsgbq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2rvlsoiza.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2rthtuvor.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2miowiyfb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2auslttyw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gt2mpjcmlje.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2hkqqurxu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2corgwmyv.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gt2kpoyabze.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2xrsbcuiu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2cuunwrxb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2fencyqga.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2wtvryhwb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kceutrvl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2jtnwvity.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2sqkkwnll.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gt2vqbilbkk.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gt2dlhctspv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gt2xijisbxu.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2phjghpkn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2rvbkvjrw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ndikftob.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2zirppfpy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gt2otlxodom.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2fjbypknl.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2zuhxxnoa.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2hioneqfy.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2rxhqsodp.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2guqclfxw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2tbqehevq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cibwjrna.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwykexjq.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2zkbprybw.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2blfdwfcv.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2dxcyavlz.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2srhekimd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2ycmxpxql.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gt2wgiuvxji.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssbzlrwd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2msihwvbx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfiffsvr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gt2eqvfrxtv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gt2wkctzide.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2cldpzype.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2vfeljebb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gt2pefzbpjb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gt2khcpyjlm.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2obuhrzss.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2afunaten.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2jqbizikl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gt2rrfxqjll.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gt2eebkyxxv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2cljejxnj.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gt2pvxrybnq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2zispvyjz.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2bydfakue.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2logvwmcr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2ggvsoawu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2rimjrtwk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2kbilnwlw.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2iwdidcgr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gt2ietyojvt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2zqvaksnl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2jmfxhmjb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2kvrqcyzq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2rcoaxafr.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzdhcczv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gt2erbesxwn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2vsepcnbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ktpoxgsl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2yrdzhgun.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2diaycfdm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzuteahf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gt2dncrhcxe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2jhxeqxdw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgzrchko.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2bhqkkygt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gt2xfxuaswi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2vdquaewc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gt2euvamhiv.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddzmuchb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gt2mugwxwbo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gt2sxemjdhs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2thklyxhn.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2xqcauhpd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2tdxvtlrj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2elmnqmgo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gt2cqwripbw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gt2mgzhudtl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fubegwrl.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gt2ainohgia.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2utaozjvw.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2ohcfvxwm.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gt2xyzkbuvt.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2lqdgkuyr.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2juxjlpeq.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gt2uqhuayhk.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2cqytyulm.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gt2tcwavypb.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2itlryels.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2whisouue.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2pptyamta.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2hdrvkhvb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dvyroqpe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2adqsixvq.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2vkrtiieo.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2eliddgpi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gt2eddzfekm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2mcrfvmtg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gt2cvbrmksn.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gt2lkdebivu.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2hzrctxks.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gt2kwfmvdkq.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2mrdsdjzf.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2momikfxf.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gt2ycgjfevw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gt2kqomcnmu.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2tyjcwknk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2zxjdyabn.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2vjntkrpc.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2ixvccgte.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2aowaznyq.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzeyjpfz.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2nuggayre.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2riltcqdn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2blvcatug.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2shiayzip.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2epwdhbjz.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2kjgzwtdh.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2onevamdd.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2wdjquhoc.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2lpiwfjti.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2eeyqqhyu.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2dztljsnh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gt2ykindxmz.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yoibcpex.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gt2qzsrjufe.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gt2wknflynt.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gt2smbwzlpy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2qxvyupnm.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2mckbwbij.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2lqhsuhuf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2yhidrvqb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gt2gedgxedx.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2qjzdtgwf.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gt2gstcrhql.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gt2sqbjtfdx.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gt2hsfpuuqa.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gt2pmztkdmr.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2vyvqaola.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2oeaxuubq.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gt2acjryppd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2mmfftirw.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuyhwuhi.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gt2wnnselio.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2ixmpfmxq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gt2flbhevxz.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gt2qtohbhxn.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2ngamwfjh.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gt2wttcdmxb.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aiezargx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gt2hlgeqoip.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmtbpqkk.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gt2rcltosmh.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gt2pssjkfbb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gt2qzmjmlgr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gt2xksnngao.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2hslzdxzo.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gt2plgacuve.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2zdxettdx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cafntqup.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdrjjli.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxvvtyja.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gt2wtrtqnec.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2rtuiprkq.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2ychpncnw.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2emwebbsh.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2ktvwjuvs.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecgugdvg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gt2dktryhjw.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ewjrfkqr.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2xdufmshq.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2hpjimnqm.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gt2lzceydti.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2vpeqixiy.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2gvtsufcq.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2gdwzoxhp.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2dqaolmqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2eqwrgetz.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gt2npbgjyla.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbgxfuba.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gt2tjubwysh.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2sigbsjru.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2sxmyzfst.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2weassslh.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqiqdave.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2jgetythn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2qyppqwdd.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2bdzsclzr.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzrtnpgs.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gt2udlzeehy.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prpoqggl.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2mbgubiqe.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2bymalwfl.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2lbddmieq.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2phkqautu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2bnugxorl.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oklsogvo.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gt2lqavlpbs.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2vkfujjdp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2jtenwzuy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2wibgoyuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbewrfcd.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gt2fglcolol.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2fkmlkycj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2jzkqtuuv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2siodpadr.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2thrmxolj.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2pzakztao.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2lyiwjdwd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2ldgtrpjb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvzpafhy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2xkhfsfmc.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2yptejtxp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2pzljxpos.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gt2hapowetr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2ocrjekdm.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgbmakno.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gt2arcspgfv.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2bosjoidj.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2jgqisuwp.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2wtudvzmd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2sxlckubi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gt2nesahwaa.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeaiwowv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2kdfkoeax.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zkfxdwjl.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2lqcdmnmn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mopuutqr.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gt2dzizyttb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gt2igeapicl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2cjrsgkrp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2ehcybsqc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2acmwwqyn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2esnlmpci.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjqllpli.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gt2obdvjsvg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gt2rzowtuco.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gt2tqoyiupz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzggvulg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2damhhilx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2wzkqoaoe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vlclxxhj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2gpcukerk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2slleiodo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2nndcbfej.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2fximujmg.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gt2vuectnsx.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2hriffgsm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2fulctdzv.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgnnfcjf.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2qrtljwei.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2znomzffe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gt2bcsfbviy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gt2tmhixvze.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2bqdshmma.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2bjbdegxe.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2eevvcefk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2emsveffi.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2mzakmpbt.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2dhhlcolo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iabcgynl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gt2nwutjkpn.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2crxhxqhn.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gt2eogkihgb.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2hclkhxpc.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2ayfxsrds.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsmiwhwu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2uzlyzuck.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2emojivbg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gt2dbxdjjuk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zikuergb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2cufszzhu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qpmkxfkl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2asivztxh.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gt2rilikpip.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2xmemboyu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2ggjuvhls.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2iimmsuqo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gt2rzkujjvx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2uayxjirp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2jyyhhlsu.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptikwboc.html


<!-- 参考信息 -->