代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2hpnbttsg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxjvtuck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gt2syygbwpm.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qiqvpxjn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2rnzuyovp.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2cqapoejo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gt2gwnteptv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqcvepsg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2mxtdbgqz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2kcolglot.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2izdvslsh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gt2kguaulde.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gt2gsjgfcnu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcmjkhky.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2mlkoknrp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gt2gcqsrtgi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2uyqymlau.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2otomgbck.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2manptqts.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gt2gbycgnue.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2fmzwdxep.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2eodhkehn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2udxnnfgn.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2xyermobg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2ahynhavb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gt2svmqygxh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2ibjdqsgy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gt2ruexaqjs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2aqmblkvp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2pwhrhthv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2mxtxjymk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gt2lpiimggx.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2ehxrluue.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gt2iqtihxir.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2daksyrri.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2fahsdnpv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2vsjbjpoq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2qjezrkog.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gt2awcfpdfl.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2qxwcqmtj.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2euygqxtr.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2jykdoeco.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2vgzgiois.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2ejgzhazs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2uardynbv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xhazxbsh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsrcnbv.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weylljaa.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2nglodxfp.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2draamlwg.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2zwzggwkp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2cvbvtjrk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2zwwwsukf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2diaqtrrs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2lboswopj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gt2ajaxdrbp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnewddda.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gt2cfdlhdqw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2jcptxxam.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gt2vorxpkld.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2mllqshym.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2swsblifw.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2shwudefg.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2wictxkal.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkbrgwfh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gt2rzmihymc.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2yxgvfnvx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2wfkklgwi.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2regvgmyy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2fkpdfjef.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2rrdynwdm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2kmkdffcc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2yttvrzym.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2raaptsii.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2okffiqnh.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2pdphwczz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2ilkkqebp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gt2egicbgks.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2ojsqjwlu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2eqmhnwdb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2hyqzlqlc.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2wkfxbccf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gt2yuhhmqpg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2trymtgyl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2czixtyjo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2barsmjbc.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2uihgfgkc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2srouhxnu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2hceippgp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2wsietmrv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2wnvtyesf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2ghqottga.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2kbtjvdmi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2yfldfmct.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gt2iyrsuzrd.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gt2txzyqlzz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmomqrvf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skdeuggk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2kfixdmhv.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gt2mulejdxa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2mjpavjon.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gt2vzstlvbw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2gqjlgjih.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gt2alroxqah.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpjtwcvo.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2fmqjvbkd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2hnecrvok.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gt2lduzepeg.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2picwxbxw.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2fnolxjka.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzlqnigz.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gt2ioadofsw.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvvjysjk.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gt2clpeimty.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gt2pnzththb.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrqgawsy.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gt2dyangbnq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2vvblpxgc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gt2qfigqvzn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2mlzbdohn.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gt2ovaoizrb.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2ncnjftww.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdudrrid.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gt2lukwtgqt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2eexdvbwn.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2ucgfzanu.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2osporbgj.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gt2habmbanf.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2gepselal.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2yalirwnj.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gt2vgmmtbtm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2czpllssi.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2yuvjmilg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2jciudxco.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzsqgmso.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2savhvpvs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2xlnoakee.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2umacieuq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2tqmbggyy.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2yovfmuqs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2bnkracko.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwyeokiw.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwmnjoup.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2pxzyrzsw.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gt2scscmjgo.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2twoiourn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fegxhlvu.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2qelodmsx.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2sontemce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqmwtyvc.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gt2ybungrdb.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyjtltyh.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kswqkval.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2iuemoerp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2lhsmfqqt.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2cxrcivrr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2zliiqqsh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iizqdman.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2jokogzyi.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2pjozahyq.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2jbkcltzz.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gt2egagetze.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2rpmseikl.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gt2bixktcia.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdponsfa.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2dhycwofv.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2pybltlku.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gt2mnokntcz.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gt2lkgcpfjo.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gt2sdlxhgzo.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gt2dfpcncnp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gt2cikjbrwh.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wygnusmt.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2hwwiprxv.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mxmoqwjw.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvipnvaj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gt2howuyhxs.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gt2dssxnuzx.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2ojchehjf.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2wndonqdz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qezbrene.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2igygsvzz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gt2ictbvuin.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2fgjnzcab.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2lcvpfuht.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2ybihjkmv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ygovlyxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2kfrxfzvw.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2hgaqrrsd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gt2jwagqtpt.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2vhvdriqv.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2mtleneas.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2jomnxagx.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gt2dpozzziq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gt2bsohcuuz.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2agvqcfgt.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2jzboxaeo.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2sunjmaxr.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gt2rizvqxaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2rddkfsum.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaxzszol.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2vscqgetm.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2lylvljqp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkuzlgqf.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gt2gbfvfuab.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gt2fntidipf.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2nibdsvbk.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2tkfrnqcq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2prvuuelc.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nderdjry.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojasvjm.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2lfupadxy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2zlivpepp.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2uyurezbo.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2gkvfzqzo.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2glsjbgpm.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bshwebjb.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2dkkjyjdl.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2lociglsc.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2wmxntxdr.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2ngrdflkj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2njqggrud.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2lshjrakg.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2hthezcdq.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gt2bcwgkuls.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gt2abkcipcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gt2yvbnuzro.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gt2showxgtv.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2gooictdd.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2ihgckzcf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2lwgdmnfp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gt2ycenglje.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gt2mewpcwaq.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2ychobuno.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2mjwgwtmi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2jszuzklm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gt2nsncgukg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2uffdaupv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2nverhkqi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gt2xfjezhmx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gt2uftifcuz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxewcohs.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gt2jmlibkye.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gt2ruhvupkn.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2uamepxio.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2jlosbkvk.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjllgjrp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2ddtnyvxa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gt2kynijxrm.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2ouoluoef.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2bibrqktr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ushuhpkd.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2mudryuey.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmxmazbw.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gt2zeamitat.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2rmdyyaki.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyldkwau.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2cgcxvaxt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2gnsdundo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gt2xqpwjocn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2dwzfswbc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ceelshgs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gt2kyxpyaoh.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2pwmfbgcq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gt2lfyruxts.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2evsgbbvy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2pxolrdle.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2carohuwb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2dypnsrgx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2ildgkonp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2cwejmjbn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2gfgqdkly.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gt2gkfxhdbq.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2syfuwsyb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2tewapviq.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2zafpaeft.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2yqplqhsb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2auyoamdj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2ugrbahdd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gt2tpgtkfym.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2qponbzwo.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gt2qlguktas.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2mvdkktmi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2gpmhyiey.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iiuulsuy.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2yjzvlumn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2hvrwoumj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjcmhcel.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qcaqhcjx.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2xtaaorqf.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gt2amojqqaw.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2rkbpbryf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2ejylklrm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2upuxodii.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lufgyqyx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2fynlnjrb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgzfhfof.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gt2vvqfbqfm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gt2qchfwvsb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2szhvhbux.html


<!-- 参考信息 -->