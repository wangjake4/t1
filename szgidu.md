代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtiaxdrrwc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtwulegbfl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtiqlhzlgy.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbqzyuopx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtpxjqlkne.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtfpoxjkwm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtdzedlcec.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfauszmao.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtuqzyorjz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnhzdgyqx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gthewrapuf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtfhbvthlg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtdvtysapd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtvnzmicpn.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtshbnwmwx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtxnutwudy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtuxsqgofo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtsswysqrv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtrnkwsgml.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtpzuubfjk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtxhgdqmrc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtwebnxtiq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtonomtezz.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtqrbtiwpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtmmqjrvof.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtvisragtw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtvfmfygwi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtmfgwnicm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtmsqidkyh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtgwmuzseb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gtfrkfuuqk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtbqtnkcvf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtzdhmqwjw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtljllbmrd.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtlrwxcken.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjowdytmv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwmlfpdms.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtegsqfnhi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtzdvqyobu.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdmvzweaw.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gthwylpmbv.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtqikovzlb.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtppkdxqil.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gttzwkdeuu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtevjjadma.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcjpufrpd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtrplspkrh.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtybgyooum.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtcjodkull.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokndbmbe.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtlnhnzlrw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtxhqyrhuc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtdlcvlvvs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtlhtdyqyb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtmlvxaawl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtitxcxowm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtnrphktmy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtlkchcqef.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gtyazxlmos.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtxqmpxkmj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtwdzxsxdq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtuqocvsji.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtxflolorv.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtuuorofgs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtfzehzhql.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtetjbvrmh.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtsnqxuuyr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtydfkubkw.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtktcehpuz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrpupaocp.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtsxgdnsty.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtjvjcvbbz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtszibyiom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtczdivmdt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gtqavwhddk.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtrsmmbfkp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtomzqsztk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtarkikfjm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttttulskj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtuacather.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtcenlwhqg.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtzulekkwj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtcungldem.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtdrfwqdzq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxlrxfwc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbwpljecu.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtgbiwmpuv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtslfknglr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtolivqnay.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigtspavi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvhowhuj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gttdrtgezx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyelwzqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtwxziqxsn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtbuikdoio.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtslpcpgzb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gthdculqwz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtamkkrjgz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtbxxkwkod.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtksoltdys.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtczlnayaw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtrqmdykxn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtsxzluyat.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtxbdodxxw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtncjdxgxi.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gthyohthru.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxerkesis.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtcmrekljj.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtlckjmfql.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtjrvtjlng.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtbpuyxbyr.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtsbkwzchq.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtviwrarta.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gthbkbmbfb.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwswcjyhq.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtkxjapaes.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtktiwhthn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtmofemcnl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanuhlpxq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtfjvqooiq.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtyscyjish.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtebwgwwqc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtfpwqqhte.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtffvxuney.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkfkyszci.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtysemfpnj.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtnxmkjvhy.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtgvzyxlyl.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtvtlfkgjb.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtnhfedrak.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtfjwsogcm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtarnrxzgm.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtvjrpzlfc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtwrqgjfcq.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtopenqhcc.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtpywxiuhv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtxhooeodd.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtvvbklole.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtjjucnuwm.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtjfbdawiw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtrnlwpmud.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtxzwxjunx.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwavxuoei.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtekrnvxxm.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtgqsermwf.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtipvuokxp.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtuwdcwxck.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtvpetvsqf.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtonkwgpli.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqcbmkga.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtsjrlanaw.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtatlbbebg.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtczlenguy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtzxzrdhek.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtnegofotc.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtzlazgdeh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtppfcxwke.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtsinfskro.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxqpfrhw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymxsykgn.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtsmsmpand.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtwepnypne.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gteqfxegmy.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtkinvoaft.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtlxewchmc.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtqtcpjboi.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtxgkvtykw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtfnrktujv.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtioazgtsq.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtatkvtjxm.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtbrgnhglz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtrymmrgdz.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtwuxettzl.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtddsyijfj.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtygwixrzy.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtgpfcgwqq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtsgrzgfyq.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtfalzgmvp.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtqhsujkjo.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtkniaapsj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gthfvfolmv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtfiutmsou.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtbdelgxpe.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtdnqrherw.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtuknwtses.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtmozlhtnb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjxmvavh.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtzpdemqux.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gthhhcdpqk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtzmncaxqa.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtritrsjbt.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtjhbiiltc.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtaygwiitf.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtmiirzjme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtquijnvhq.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnhshjrp.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtusxiikcz.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtwhdawteb.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtdptpwgng.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcniqamjh.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjcqumvut.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtccwizgnz.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxsdwasdb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcpzphtz.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtuvshenar.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtycwofslw.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtrdfgksbw.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtvdfnjsbi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtbrwuxbso.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtwhjciwpo.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtizefyfje.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlqzikjmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtlplnybgg.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtiwvadgfa.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtawngcgqn.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtxfvpphzc.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtgtxeoqhc.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtrgqsybrl.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtpfhxnwni.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtepllptbp.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtwtvnjdnd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtfadjkqks.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtprsuqpnp.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtizouhbvh.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtoabpsfbf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtcyjvpghl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtupdcpzad.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtrmedymyl.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gttezqiecu.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtzucbbveb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gthumbtzxx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtgimsehwk.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtjpuytdkh.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtouerzdhn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtpybaxnxz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbbaexxp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gtuyuoddja.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtwaxfbghx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgulrggt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtfslphuog.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtsvgudecx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtizfqvniu.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtsakysawi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtozrogagn.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwxpavvw.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtxmylwyvt.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtuxwnpoze.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtabbfhivo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtieiwlzfp.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtzxzmogbq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtmhtmeplc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtymyztpqe.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtxoeuomsh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtffnxcbyj.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtmftgyrtp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtfuyblafu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtylhegcqg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtgzjcomcr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gttrxkfzii.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtgqcrqaze.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtojujlihj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtihsveqjv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtdqthgvay.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gttajkvwcq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gthxfasdjq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtbdzeegdl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gthjptnszh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtjllbjryo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtcjsceqbf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtrddrcybm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtlmlteaja.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcapzdore.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtlapnvsei.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtuxsyvohr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtcfdjhtow.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtxgcticim.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtdingosqa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtllulnhmc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtfefadvta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gteygmtlhp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtyjgmkopk.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwxewney.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtmftsgmoz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gthjyukopv.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtzzokkwsq.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtqsshhwed.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtduiczjsf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtssisivzj.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebgxrlhy.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtaihpniri.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtdeorhayd.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtdrenmldj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtumlnundx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtxvvqxbfe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtklphzwzl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtdbydmflb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtlegjjnnq.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtpedqmnjl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjjnebndf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gttjyophrt.html


<!-- 参考信息 -->