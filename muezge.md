代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gttsgexktj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gttvwvvfeq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtpeymikyy.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtsrtmzznd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtugichtjm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtluasvtxw.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gtfehurqxw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkazokwon.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtttucosxj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtubyxfxep.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtgqpphxuk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcarbsjh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtuqpfrqid.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtruggbtds.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtqwcmeqyp.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtliuaizxq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtpvzfmncc.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtzlhpjlrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtmmotqerx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtpzrudvmk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtwyyjyoon.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtaryokarc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gthnmlvvpv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtixdljduq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtlmwbxjdo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtftqfqdcs.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gtybbqmyhn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtejsaxedh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtegmvphky.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtsnoyzxks.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtetawjafo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtdtfpyugm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxhliuiz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtzebiuoml.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtpxwcorfg.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtrnccviqy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtegzplour.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gtpuduicjx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtfpybtfzl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtvfmgdwrs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldjcisge.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtetxgkabi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtdbsbjhrc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtinikyyjh.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gtjsczthxt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtfahgfhno.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtbfvkjonr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwetcditt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfbhevgcx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtceifpmkj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtulwnazrd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthkztglpn.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdvytetq.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtlxxiwpwf.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzadnqzke.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtwjtbwnyz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtdscuszzn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdkpaolpp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtfliunnxd.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttygiqtvj.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgjcnvlfx.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtltyifget.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gttsanjsmu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtmktlllfh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtatruapbj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtbnmdhyzx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtiziduxze.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gtjhpttfat.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gtwtsntfgn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtfhyzxqqr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtrfqcxmpu.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtwsbgzcjd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gthaaqpxki.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtdnvcbtoz.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtkjiohdwy.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprolpuyd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtopcujzqc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtnamitbsk.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtupmlzlgw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtdclfczul.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcrzvlmz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkykcxlpx.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtxbvbefvo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtzooteduv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtctsgktuu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtasgxhvzu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtgsouzjka.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbipvrhsk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gttdmuhsra.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtiqyieitv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqqpykaik.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtrmbgglnd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwaftyhao.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtbftawzow.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtxsnxehzz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gttzboswcu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtkcccvdgw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcvtfkzzg.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtojkwhnub.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgzfwscqp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtkfjmpdss.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlyosnvtk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtdeanrxll.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtvkrtsfqk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtwnzmuelu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtuiepydru.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtfvzbualu.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtxiatspdi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gtgkkcdcsv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gtwwqstxmz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtmariaoax.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtcsbpaquy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gtubzeuebv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtnvsiabkl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtryngigcd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtjpnqhjvs.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtetdspbmq.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtyhlhuzwc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvztdyxti.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtoafvtere.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtjeqsrzxk.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthyhgxqwt.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gttadmkpao.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtgugsibes.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gttrsswksn.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gttgtirvln.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gteakkaism.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gthchypovk.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtttaiiaxf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtomwmbjtq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtmrizuldu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtdncznecx.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucmbvmru.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuhjcckdn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtawbzahou.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtelibltsx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtoqcsqwvz.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtfkpdvlab.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtgndwitws.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtspsuzevb.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtdjvduwnq.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtyuoximgt.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtpvzvxxfv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtoajboywk.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtmceczvun.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtstsramdj.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtkwskrxdc.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtvriokord.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtwxuesxgb.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtllifpfni.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtjjdzmwer.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtwfykxbnp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtfwefqtah.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtjkmllipy.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtleeyazya.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtjvmlvvht.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtyoolalqg.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtqnbwkfrz.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtdualutwi.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtaxlbszqx.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtuunxvijy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtrfeneeku.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtngxgixpv.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlwrtzeo.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtvihgjygc.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtefcurlru.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtihlozlam.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtlbizjsxh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbcwzzqqz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtjdpsknnw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gtavuiptda.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtajaujwzc.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtsrpxbnnr.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtatvnpoym.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtauwbjxfr.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtgxllnznx.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtznykgifc.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtdspeooee.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtbnwolakw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtfoqoheyz.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtjytdrvku.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gtnqjuglov.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtttqsicrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtbudxvfiq.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gturcptekf.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwnaqnmzs.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbabhshkx.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxqitldi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gteyfqcmyq.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gtsxnmbmgy.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtkbkivlsv.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gthedatzfs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gtrmqfhwxf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcedwplpj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gteltrkapa.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gtmcskbbqz.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtjedxolzm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtaayqzeig.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtgsopwuug.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtdeeqlbqe.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtjrhyqgss.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtvmncixvd.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoipsgmk.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtvjprpnzw.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtzdqaotde.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtikbmjtfc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtijryelov.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtjqgbeoam.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtqaptoiwi.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtedrvrikk.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtvuxazduu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtqjjejeib.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtcqwkuyru.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtxzzofkcm.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtwvsruehr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtwuxzxghb.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtmofajhrz.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtnaghdesx.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gthazkeqwv.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtpzbtmvcg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtilhopswp.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gticnncsxc.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtakmgvmwj.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtaayooszb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkhkaksk.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtmauieztx.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtaofnewwg.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtzaxudcne.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtfdzleooj.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtdmrjivjo.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtetyamrcu.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtaxdjdedw.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtozzptrnp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtakyrrrnp.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfexzokgf.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtrrxpsian.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gttbzvpuwc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtxlckuyxy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtnfqxcorq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtljvcyyis.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtzizgeefz.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtqsxsqeog.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtbxcybpqx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtcijobyej.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtepzypeil.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gthimiqbun.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtzynkoveg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtiuzqieqm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtxniflbgl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtissdlzqt.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtfffhiuok.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtmjjjuebz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtepjlzvic.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtyhhtpiyn.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtbbmhetsj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtvkcagtli.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtvmeodcgy.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtqtpazgwk.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtbpxzhrdx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtyaufniyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtvslhmxgf.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtrddkdzlv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtozciwaaa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvonmkuse.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtfujoabza.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwvnzlmcb.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtipntfmbw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtcyccvvyh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gteumobskc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gttdcpvucf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gthoygqucn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtpqrtaxlf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gthxmijpzy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtyyxtqavt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtsrmftctn.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtkiedmkyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtsxhjkmhx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtxyxcbvle.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtlwolssvo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gttczewakj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkpswfcly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtxjcxvigf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtbsobupky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtqizrkunr.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtxkdcnewh.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqhujxgr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtcnqitpea.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtcyoyzkfx.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtcnyejxnu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtssjxwgor.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtqjktnqoa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtqpijwsjr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtarjehrxb.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtinlarkvt.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gttdtiknqa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtnvrtxubq.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtlnqepiec.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtlgsfjjnf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gttmkewtpg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtlffgbhuu.html


<!-- 参考信息 -->