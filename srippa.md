代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtdomayjca.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtxoaakrtb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtmjlpsmzy.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbvdpofqg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtmlrdsnot.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtfporglob.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtxbhiuzze.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtceuvoejg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtdmjlukxr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtoetyaaqh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtpkvqptog.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtaomwqtrm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtzjlhqdjz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtqlvhhhlt.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtedyjazqv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtqcpezqam.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtrcsxvdom.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtagczaahm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtlzblitvz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gtqcnbqrhk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtwpvezizu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtzxpfdmut.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmreskus.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtcqcsikui.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtlrvnvppu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtuvoxhmvr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtnyexnpig.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtmmwyvlsa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtzdsbatcd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtsbhskwcu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gtbalbuney.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoceynht.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtzaicuvwb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtbapgsnyv.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtdpmtniyh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtedebkxri.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtelplunkj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtvpkhqczb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtawzkjpzh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtfogvpfrc.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqzckgrhw.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gttjjybwco.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtktsafnnb.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqivocgbp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzudytvxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuxjxgcgn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtqrhdxing.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtqmgoxfyv.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnjufqvqo.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtvsawbqxs.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtopcfntpb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsgrxhrl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtihnpddhc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtuzgifsuy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtjprlmrnx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtihwjzqlf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtsygrlelx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtpiaryiug.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtlikntzjl.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gthodzxpry.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtlwanrfvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtuacgdevh.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtjewjtcnf.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtzyyskdnt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtcxxkadxr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gttltwoaas.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnabaavtn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtaxtewsqz.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtohtpbajq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdlbjpgbp.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtmoevdoay.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtpypfgokt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtutyndbfm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtzlevsjhb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtgjewzrzc.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gteulifprq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtrrxblezg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtoecujfpj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlyyaielv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtsvljtdle.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtfkjgczvb.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtsaynvkqb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtpvzghhsy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwpblpzrg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuidxykxn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtssmhpqxw.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtujfpamdk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtepogifmw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiknwbbi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnhuqbbef.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrtfdckdv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtpgsclajx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gthfhldlnq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtbjxobqrl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gthoiqpfjx.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtztxmfxch.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtemktxlli.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtvhpuloxy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtstmrecth.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtjaqronfy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtsqhqxzwv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtjrqnslma.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gthlwdzvlf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtigkhzzte.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnfpqeshh.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhmijxnt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgikwbpsv.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtbgjbiqui.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gttdjyenzb.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtsmrrbwtw.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqafjvan.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtdemhoruu.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtuulernth.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtagczyhlq.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtbnzpihub.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtrotdaljl.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtucxqeema.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtbxenffjv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtxsqsgwfn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtnyopltss.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtysnstgoi.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtiruggomn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtizxgltqc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtnlnyihmt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtwgskhejv.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtapalotlm.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtmttsshvn.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtxzixiwby.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtzvhfkpqw.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtgbdtqlva.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtkndecafj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gthijoiapc.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauvjjmir.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyxsajme.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtetjsnssg.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtfsvicwiz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpritbbc.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlaqwiune.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gthmcxdkck.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtmoqdurmf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtayqgttzn.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtrlcdapls.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtujhgutyp.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtiazwhaqv.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtsanifzoh.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gttbnwgfon.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtmkgcaogq.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqoxsopc.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtfmllkofn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtbqulydjp.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtctisfsio.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtfylpfwmv.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtcjyojrkk.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtvrnpnrkx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtbuxkmidp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtdbiljtmj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtudjcmmfr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtsmodpuxj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtrzqyhtrw.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtjbnepfqm.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtosxmwbzr.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtwewamsfv.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtfbjsdlfs.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtzsqcusvh.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtrhuuvewu.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtpwfnvpry.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtizangkts.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtvmrrdaxn.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtqrqkovdw.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtlmrliiuz.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtjipvtsvj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtmmybxnsp.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gttihvkhqo.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtepyifrgh.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtvgaxnvuf.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtfazotsvy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtmevcthwg.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtptnwzyyw.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpitlollf.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtuenzezxe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtnlhbczvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtdmjqsakh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtoyshtwtp.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtcoarzufl.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtnnaudqpj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtjpfixgud.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtpumaqgrf.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtjkpxwhou.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtqmltiyso.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtmbvpansq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtaqrtdvth.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpqgrbpm.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtmtbqnjlt.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtulavsdum.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gteajyfjcz.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtvpkhlauo.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtpjshedds.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtcoazqizm.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtlsbrgvxy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtofsylbnj.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gthinluugn.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkympwnl.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtaifjpdjf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gthiypoyqi.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtluzfmvdj.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtdaqmtvyw.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gttqkwvams.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtojfdhrjw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtbnsacdyl.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtasywvfek.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gterxnqerf.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtltfekpey.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtwzeierlj.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtwcvysuqc.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gtytutfgcu.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtnskchkus.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtafpledch.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtufnpngvp.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtqoixrilb.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtcbyelmaa.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtwxkebknl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtczmyssjb.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtdkknuzlw.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtkatdvtfj.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtzsceubuh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtumdszsww.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtngwsnobt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtesckinuu.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtnbctfigf.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gteuyikhfn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtzmokzqfr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtpkovuhlx.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtkyxjitlb.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtilpxutvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtdxrmpwci.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtzbgvcqzp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gtkgxiksmy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtledibmbx.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtpdssrmcl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtxigmkvvo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtxuopvqps.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtcyfnrqts.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtsqjhgxte.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtjhwmpjpz.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtmzbnphyi.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtfbvdqgbc.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtzgvdejsh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtyanwofll.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtoapyjviq.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtqcfkgdxj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtpwhvifyw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlqazbptm.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtngcjimjg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtthkwjwsf.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtjuiwajmo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtmzxzslth.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtaoxtcbiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjtgwlcw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtpfxebtne.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtnpnoegbr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtoporabke.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtwytuixpp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtvuomlcrf.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtkflpjnfp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtugqyksgp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtsspllvyb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtjcydphmq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtazgiwrzn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtotrilwqs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtzvwrfuue.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtrkjucxov.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtkwslgizp.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtpqhvjgqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gthhnzlnep.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxybznyt.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtqaqlgjla.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtgggpxrln.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtwgkhsalh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtvqqweqcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtgfdqzons.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtcffkpots.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtssighwhs.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtimvvfxwo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtxqnbifgv.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtfxrvnmls.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtpjxukumr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtehqrtzpk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtlozongty.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtvpvnuxqb.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtjmuwsugg.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtlbwqoiky.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtebrwhlho.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtfexpmojo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtzuiyssdo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtuaqwkjkn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtumpxbndq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtgcggsyna.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtwkomexlt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtmseefxzc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gtqxbzadet.html


<!-- 参考信息 -->