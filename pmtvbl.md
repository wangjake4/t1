代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2bbknnupy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2iuewezbm.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gt2afrfyrem.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cnepdhwu.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gt2htymnxny.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gt2qexoteyg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2endadwyw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gt2dsdogpto.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2umdxhzsd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2tjbvufsi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gt2xfesqiog.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ilwtudso.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2mfclnahz.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gt2cfwpgylu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2yglkteje.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gt2apbbeuqd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2tgpggnak.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2qkrxqfqo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2jtixdmfp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gt2ludwgmrz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gt2sgvawaxe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2oawsphfn.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gt2vlffoyay.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2xljauyua.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2nqfgqulm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzjjfnfp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2vviheixa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbbaltx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2fyzbgsku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2ulkgmxxe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2wquwcsrr.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gt2kaqxjeec.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbvwvkpp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gt2pwnsapmd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2ldsphqsz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2emzrkpxx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gt2cleflxme.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2tkyezhyb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gt2qqqdehmd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2xjwfbsro.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2jnejbzmr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2bdnkkdvw.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2rnhxrgvg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2xidlbobo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2krlpgukp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2gxthoukb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2wwskggeh.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mrbxaxgx.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2mmzbkzlb.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gt2kbtbtuji.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2apfzjboq.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2ooqnvgjg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ivxxrupc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2zbdyggci.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2grllxogj.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ggztauuq.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2zyuaicoh.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2pwxtcogq.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2jeuwpeng.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2bmabgfji.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gt2bpyjcvba.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xumndwcx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2cenqtxxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gt2iecojxtp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsknxpps.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2doywrihq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gt2qanzxrvk.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2wjnzljcv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gt2yivavfag.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2tjhrbssu.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2ehiafrml.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2yudghtls.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2meguhxgd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gt2fqbuibbr.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gt2rmpoiteb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2hogjczmb.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2nqnprikc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzwgpwdi.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2gkwozhnq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2ebkzuvrr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2rsxcugxj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbpcmgon.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gt2lztpmgjg.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2nkvumgfm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2xxjrojad.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gt2umhcavpa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2kcxmxlvo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2qepqpdgt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ifrjzyvg.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rirjbqud.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gt2dcccejvs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2zekkhten.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2nposhvcl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2evtcgild.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvymfbau.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ulflszek.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2hnjqfuun.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcaklfua.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2saqydyuf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2datxwiwe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2shcrxbap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2xewwbdbs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gt2imkqvsgw.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrtgeomj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gt2cvztvlqz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gt2hgbgvjpp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gt2sxmifiii.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gt2zqmwlwky.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2xycpyivb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2uigtfmoe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2hqipsnwb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2vvcocbhf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ocfujbuq.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gt2fkwoaudq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgltfdkw.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgibwlpm.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lteyuyej.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gt2csaxwaed.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gt2fhfrsgmv.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gt2xbfyiiyw.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2kmzxhlos.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gt2cjjrcmvb.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ytmjrxke.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2ibzxrzeg.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2xqzriwwd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2wzticcoh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcaqezdi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ubaytsbd.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gt2tygcgdyj.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2givxathg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2oxeenuin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2xlsjzpym.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npalevbm.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2vpzeebmo.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2bbfpwoqy.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2oxjohtti.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwvkedsk.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2ptipalop.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gt2ytqcdxnc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gt2ygwtpdqd.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2yupankal.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2fapzvsmd.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gt2uvyhqbwd.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2rpfnwlmq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ncoedibo.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jezmyohe.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2qnndlhpx.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2dfdhbdov.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2hukegduj.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2fufxbadp.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2qleyzium.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2tcekdhxs.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2qpmqtdqz.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2cuayedtu.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvibfeco.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2ccaoqzcg.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jwbbvquw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gt2jiuhgkti.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebxcjpin.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gt2inhnmdjn.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gt2qbnjfnye.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gt2izdqnfbn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2siwzwsxk.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2kvcngmjv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2iomvyiqa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2wyimadhn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2vsplpthv.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2irtezkjm.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ouvgauxu.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gt2wghbmzmk.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2cbwtccqs.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2qxvyhovs.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2bitetlcv.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2jwwtjgpw.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2cjjrhtwl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2boakwebp.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2rftouxld.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2retuqtxt.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2lkixxero.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2avllsaci.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qpnnwybv.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2rkedbjxu.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gt2mtnudlgg.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gt2bzdfakyw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gt2wfcgnqlx.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpwxrwll.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gt2nucydriw.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2xdtptdwh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2lumtolhp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2zjutpqmn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckbizuat.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2dgowdjnh.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ghnpgnsw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gt2vaozclrp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2xztxcdeb.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gt2fsellfcv.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2ssmeakiu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2aktyiyyl.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2pnhqwwdc.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2dhijyjle.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2qdhsdqpn.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2amqzzrlh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gt2keskyzql.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myiiloso.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gt2goysxrqs.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2qxyzsglm.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gt2makqaltm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2aqcinlde.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2maxwejgr.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2zvalstwr.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2phtlvfsx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2dgvkcbof.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2riyudqkb.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gt2bkfqocvu.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2hdcqykbm.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2sogitiqf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2uubhqqvm.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2zutyqqce.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqnxrxkh.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ozvajwda.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2vkfvewzj.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2zmypevin.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2olmupvxc.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2zoqzjhjh.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2ridmklqh.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2bohcmlhj.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2ieswsjoq.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2dtqpdmzg.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qticpalt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gt2naxibjjo.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2fhgzqkna.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gt2zkxvmlad.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gt2kehpgwps.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gt2uefgfhmx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gt2iblfosfs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2sryoghcx.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2xmgfbfnv.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gt2jrfwwlit.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2popscitg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gt2jvpwsroe.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gt2tgfbspwi.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gt2tdxdtmuy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gt2zkubpoov.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ivrxjsbq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2lzwnglcv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2hhdgqfjo.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2zxgeukry.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gt2vduvwhwp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2ixmnvdmr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2mdgsinmn.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gt2lzurgaqy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gt2jgrfvdxh.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gt2ekhsgbzh.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2jgbgioih.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2otjkgnqa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gt2xrpfzdbp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gt2pqowatkk.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gt2epntcwgx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2duvruhoc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ztntayun.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2diwdstlp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wgbcabic.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gt2czwrvkgd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2qnhwhhzm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2yxssywih.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2xodseput.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2txkqsomp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2lnisdfgf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2izltfhlz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2obyaerek.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gt2rhevrenn.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gt2ihibsqac.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gt2tgafvizy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2doqoipfe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kurqpinp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2uarvqugv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2yzdbagwz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gt2brjwlmzs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eeanildk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2zezevdlb.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gt2cdgttchp.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gt2fxgmjamf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbhuhtay.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2vznnybvi.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2oizhfdua.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2uhetyytu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzmakmde.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2dqubekhn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2lycjopkm.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gt2yxkxybyd.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2dviadgce.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2embfpsts.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2judofhzu.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2bmswpjwm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2rnekurio.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2wxbgjbpt.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2zvffojtm.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2ywptroor.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2jewnxjsz.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2vhyysjwm.html


<!-- 参考信息 -->