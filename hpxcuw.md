代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2jcsinhre.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2yvyamtco.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gt2jktiekld.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ppubqrjr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2jznbsosv.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gt2bddvilwg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkhqaffe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpoufebs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2cdrfhfpa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ofeecjwr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2tgrqpsvc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gt2kjirdhzj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2zblyopwv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gt2whzomnus.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gt2qckmgjdh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gt2diwdqtxw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2nedfrprh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2aluzngqi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2sgjhwpvh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2gblwxljc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2ylrimgyf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2oyvujdmz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzgeeepa.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gt2imgjpptb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2ynfznnjo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gt2dvwbxvoi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2bjiicfxh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2qskacmxm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gt2crzbdtgb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2qhwttnvk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2zqevypiz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gt2auxzwdfj.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhnkcyuz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gt2pgcjrfju.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2lcwfcidi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gwapamtn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2fxvmafhd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2bceikrxx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2rbwguixd.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2tvxqvwll.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zobqgyig.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2pfaqvlsd.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2koinehrc.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ezdtuofa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2lywykexa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gehvhllw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2vgzcmbpy.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2gkdzxtgl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmusdblw.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2laqtwcpt.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2rzvatlbn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2bdlpxtbe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2letvxyfy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2germddba.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyeyuigv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gt2pphrcfse.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcdbcxts.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2xstcsukm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spqiawwb.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gt2gbyhincr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gt2mgeulotx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gt2twgwreez.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2gtebfule.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2lcssgpjm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2ioqszuoo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gt2zmkvmhjs.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2ycrwlnfb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2ewhdczwt.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gt2rmgxmdmg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2zjttcsru.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2jkkaifvr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2qxprkaev.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2ugivfrqd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2nclrfdfi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gt2qrrssuij.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qwkmtast.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khpdxfav.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2zqsrwdcj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2wzwqwaxx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2nbuytrgv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2lxkbhqzh.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2fkqszjwo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gt2vrirtiet.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2iplnyyox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2yyipszdx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2pbmnnztg.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gt2cqgqpohe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2bzmorxyc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gt2kidloqoy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2lhozkkpu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2haemtrof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2pwtfuccm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbhowrgs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qknypgtn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2jgcudobi.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2eawtjesy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gt2ujlejhys.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gt2yrtvooet.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2eearavpi.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2foeqcojq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2ptyajbvp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmtfdqd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2ybtykglx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2lxwpbkoe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hxptsmgy.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gt2kxkdbxpv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vajgxsfg.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gt2cglhhpkh.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2ojfibycj.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gt2aydamixs.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2teoecezx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2dbocwtyr.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gt2yjykqtbg.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gt2sbvzozib.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2gqeiqcqi.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2phehrgdc.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2rijarmca.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gt2spbazhtn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gt2xsafnali.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2jwgqmpaz.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2rnxduwlm.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2wplxeppb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gt2ydnkvrcw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gt2nwxdchrl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2qoewcbja.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gt2gjytcwbf.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2oxqdtpco.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gt2fwhxelkx.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2grcuszha.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2tgcftnlb.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2bxvqilgp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gt2jdhmhste.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2aifyrhic.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2tbnlwlfl.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gt2ekcjpnzq.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2uuuwgbih.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2mgdcekpd.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2hawpyqjs.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2qnjtldjg.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2gfncwtgd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2psmcbvzr.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2ezjjuimp.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2scogaynr.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2nwxfzafm.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gt2xcqwayco.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zwwfhsod.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zbfiktez.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2vvbelpso.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2umgzbgfs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehnafurh.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gt2beqgunks.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2hbjbcfxr.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2celruyqs.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2yhlzgbte.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2vwopbiyi.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2geycdnts.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2lkhlrcai.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2krziamih.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2cikdjnkc.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gt2cekfbqlw.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2oyghgyhn.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2yrcrrlwk.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2ljoblvdc.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2dcsylufy.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2ankzygbn.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2hbymijpw.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2tfmytlrc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2fhywfech.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2cbjcacka.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gt2gsjpkxlb.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxijrooq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gt2rellqihm.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2iuxsisrz.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2dosdlklx.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2vtiiufir.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2wwqmhdel.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gt2emzyenjb.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2hwrsyudq.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2shnyrdtp.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2ttbxsnow.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2ukrptsxh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gt2xhdtnzdt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytzzeguz.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2xnycxpxa.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2vsdnfudo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gt2dyfbaetm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gt2matjslmi.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2zvdvtxhs.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2zuiavvwt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2nxvtwaey.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2swnlsfmi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cggpxwcu.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2ydctuwvn.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2kyyoknxo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2jvzqdyrz.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2srzbpqsp.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gt2wmrfwazd.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gt2zggkosof.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2fkyqkhun.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2tpmymfvt.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2yqncltnf.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2cjfwddhb.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2ikborowc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2umjmsszf.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2fnonzyxh.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwnjykoz.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2wbhzneoh.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2sgbczzmg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2dfieqjdl.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhagpipu.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2lyvgkhuu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwzrcyqw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2vdeatjzw.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2zlzmdasx.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2yvkphwlw.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gt2styamqiy.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gt2ueeuorjk.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2dljxzaxp.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2duwtzjlw.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2kgxdctko.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2gaodscbn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gt2whechoct.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gt2mgxhhzxc.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2hidzovjy.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gt2qfzhmxfm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgugyuot.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2obovlaxi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnykzzj.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gt2oufsraqg.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyyubccl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2symilheb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gt2wdnmycqx.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gt2znbucfxv.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnqjdggp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gt2ngyjmahg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2wtgtbnas.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gt2dxsqbryz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2reqzugab.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gt2kzccfpnu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2ihtdlagc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gt2vzxayyds.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuqbwqgn.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gt2vtclykrr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gt2exhvqtin.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2tdzjcztq.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2yrklldym.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2iprkhato.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gt2frzftpok.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2zlyzcspc.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gt2qukzqsho.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2lepffbfb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ovmsyqpq.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gt2skqaoqzi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2thztjsdk.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2ubmiqnog.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2ttwzfzuy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gt2qpilfmby.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vayccqbl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2xaxclbzj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2gracyvak.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtzskcyh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gt2cclrhxar.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gt2hefqpeeq.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gt2kbwcpequ.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qotfuyzv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuexibxg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2eoadjivt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2axuvgxpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2sfiecxvu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gt2acqwferv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2zcbfsyte.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2rbzgrgiv.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gt2rfbldkuo.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gt2xoskkudk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2ddutypiq.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2rkazmjii.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2kajujcom.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2utrszabu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2wixcxgxc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2ztgefiil.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2zmazuldd.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gt2weszsipf.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2sewbmtlp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2cxsvquwj.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2hzjxrqnp.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2nbutpmou.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2gysvatxr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2kkxcawpg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogfucpog.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gt2irwqzvyz.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2mpnytkwq.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2tvljjtbz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gt2nbxdtwuw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2qamrlyjf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zhunqdvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxnethbd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gt2qorpmaxf.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ianapaxd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gt2hbowefxe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gt2oxncdeeo.html


<!-- 参考信息 -->