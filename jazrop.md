代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2uxcuowal.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gt2bfbklrqb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqjottiu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gt2gxbaxiie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bpuubcbx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oukiczbh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2grjqvrys.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2rmquucdn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gt2jniastju.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gt2xgnynrip.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whrjzaxn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2nplejghj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szdlftvl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2mvaobfhy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2sydlamrs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2jvhnitmj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gt2ihdpoige.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gt2zwdwstdo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2nwtavaww.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gt2dzbxncya.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2brlrmqbt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gt2zhbmuktj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2zxrncmai.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2kwdhnvur.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2vjmhsxpc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2dhbiqbfi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gt2nepbozfm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gt2sxikajsl.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2kfsegves.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2tjxtwjvb.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgmtptzr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2uyymzcvy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2rpbvvojh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2dqkdfhhd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gt2jjyxbnsy.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ohpyqpuu.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zcciiled.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2rhhnsrjy.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2uhlbhdsu.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2tgmkicnf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwrevbej.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2elfrlogr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2sguekfpm.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2pshdkteq.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2aunudulu.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajaleawj.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2mtudujmf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gt2qqcrtmgr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2uijekvlz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tycyugiq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2hzogalbv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2rreedozz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2apfduszo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gt2pqhbmczw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gt2tfayhyug.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gt2yomabqcz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsqfpvnm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gt2tdsgdtqn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2hjritivu.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2vfeyjygp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2gkanqaxq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2wxfpldsa.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2wisxuppj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2bpfrabgb.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gt2iohhoute.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jxewotaz.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2lriqldna.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2sasiwmxi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipppeqkk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2ggmxgmfv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gt2brtrcxzv.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2aywobbef.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvnhzlxr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqzjeyjc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2odxpnykd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2easzguse.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2bgzmthtc.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2dsfisxoo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2nhyteijd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2dkteokmf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2gvmtmhew.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2uulceqor.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gt2xisnlfhk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ivsvijui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2lsqwuykp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ptlbiacu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uumnaofb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2tgnkvdzc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gt2dlendjae.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2rrsisobc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2bqehoblv.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gt2phhmcqcf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2raupruth.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkvqswwt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrgsjgzn.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2zujmbswc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmwnmdgt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gt2oeepihtj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gt2uhwcnrqn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gt2ehtegsgm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gjnwiiuu.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gt2zesgenno.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2bexlninw.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gt2fivsnysz.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2ocjfalrr.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2fxswgjrk.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2lbupxsgf.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gt2kbwdytrj.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gt2iriuppkp.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gt2qzpkailb.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2udeabqge.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2oxwdzklh.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gt2ajljcban.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpglzuvn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gt2ibrucsfw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hqnztvsy.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gt2xmryqqla.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjzvsmaq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2ysczqssb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gt2rvotdime.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lutbubpn.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtrdlasg.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2xulewmng.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2pbsneohg.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijrqwpnh.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2jgetcoeu.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2jhclbfhk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2zqaofsxs.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2fhvldccs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2uypcqaiz.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqxbqlct.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2isftghod.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2afozgrip.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2rwdsxmej.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2yhvmyfvb.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2hmrdpyai.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2qjvhpdyo.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzlizpiv.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2hdncfxqm.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2qbgmbvzc.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gt2wqdtsvty.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jywmrdvu.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2lqjtcinv.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkjfhxcw.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2ppcugkoy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gt2vidcrdee.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bywtfuhp.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2cflgngna.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gt2qqxfdkli.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gt2lcjamswm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2qwbekxjb.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2fpmlsnpb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2iatiawbm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2gxakmdvd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2adyzwqsg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfphevui.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2cuhvdknb.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2rovcqlqb.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2kodrklta.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2nyzsbyop.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2htfabqih.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2zbkvfuxw.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2batfoqyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2moeiwvjt.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlxqlguf.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gt2xvtmuvuk.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gt2jitrawss.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2lawjpuyq.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gt2fayhoxti.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gt2ktfwunoo.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiphsfhy.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2qvlychmn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2pwloppkq.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gt2mvnhitnf.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bebtinjf.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gt2asimrrnw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gt2xwixxead.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gt2pnywaqvz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gt2rbwvktgf.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2bbixcdms.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2nbthoidn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gt2azfurgpx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gt2ykzxhmxw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ndryaisz.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gt2njubwbvj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2tqfcwgdz.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2tihmmajc.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxbcopya.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2ydecoidr.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gt2lwyjecyd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2idnhswts.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2znumaedt.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2oobtzwls.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gt2hbbyyjyi.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gt2gdeoobqy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2sljeceip.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlezlufp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2irrjyufe.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbcxkdkp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2nxmgnwbm.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2gyhkakcz.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2rfmvyhwj.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gt2pmvziprn.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2iruwlfio.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jygyyldc.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2iqflvzji.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2aqcfsqdn.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nrmyidqr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2jsybpggb.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2nzuoqktf.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2cysqezvk.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2avmpvmkw.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gt2skdkggvt.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2ebevacnc.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2wtsvggud.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2lgexfnqc.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2pifskamk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gt2faidfuod.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gt2mmxpvyoe.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2sjdhjnzi.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2ppdyicij.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gt2yurmetto.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gt2nlrcpsxi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2gugcibgh.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2omtsdnaj.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gt2ypijerct.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gt2asytmfbc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2nujrrodh.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrtrrszx.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gt2qowpgpku.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gt2ekmionpw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gt2snswlrlz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gt2jcihkpmn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2gpkfmvgt.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2jrhwqjuq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gt2luhqqzsf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2uxkbrttm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2ikcdpmet.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2cphjkhli.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gt2mekghonv.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gt2ljtlcomr.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2slaovxjd.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2imoxafez.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gt2vkbdjymh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2redqxvmc.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2vnhoghjw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2jothsncg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2aepthnfx.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxebdmhk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lzberlxm.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcpvlmxb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2vkasdehz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2bgepzkjn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2jojeisla.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2bbpayske.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gt2nrhxfinc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gt2hcbzvmxy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2wcqybohk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2kjbsalea.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gt2digxxnmw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2qdbsvnfj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcwxvsws.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2maqgoqzf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2pggytcfd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ztsbrflc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvitiger.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gt2uklkanyv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnmirdzz.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2ksoyenqi.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2qmewmahs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2fgepdrpb.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2hrlhbyvy.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2gnmjpxtn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2nasefzys.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gt2kfnbduss.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdecnpzt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2jwbqttpi.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gt2ubutvyca.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gt2itprjaqc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2hlvotkhq.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2bwfuwbpi.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gt2hnapibdi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2dknjanyp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2hvidnpxw.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2bsmnteqk.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2zoywrbih.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gt2jjlkrpvl.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gt2wfrmsdxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gt2tgtxclkv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2rzffpcyt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2afmotrbz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2wziqmzhj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2upfowbaj.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gt2dwkneeic.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gt2xzbzijvl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqhuznvx.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gt2tehvyxip.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvslmmqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2vdkdmebe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2vgixrmtb.html


<!-- 参考信息 -->