代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtupbrwlsw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtlwooezvb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtbxitlxea.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdmljlxov.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtjkomdxrf.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtzjqgegya.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtkqgegmew.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfyfpsrra.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtcrpzxejj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtfstczlwm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtoxudikuw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtdhiabcfu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtvbtjgcda.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtrrvwatsz.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtrlhtuvlj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtkpgralbu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtrelajyzg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtqpekigfw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtheuocrbi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtpvtgfqly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtkwyvtajn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtwtqbhloc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtejjuofit.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtocyespdx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtjcplrure.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtpexunskf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtjjlzvryh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtlwbgsokf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrikoeem.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtrarkkqbt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtwmayrwby.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtfgjfghhp.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtpmcbfxwr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtxafqokqe.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbtethtg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmfjjbeuf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtbhrkmyus.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjceaoeag.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtweznjwsc.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtyybhwqit.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtqkppphmt.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtjkuxaand.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvzejxcli.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgofijrin.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtibxgguaz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtndnyijiu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtsqfppgow.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaxfmzif.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjcrdofia.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtgvoqqpgw.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtpbarludh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbnahrul.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtpnzvicyw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtezifjbgz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtdssxezrc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtuusgyjej.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtvavsljmc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtkxicgeui.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtihkpgmkd.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhcpiqzw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gttznklzpc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtlcgpsbwo.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtgqiqqiga.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtmoqanoew.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtvircieab.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtlsfajdvj.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtlynewagq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtktmbqnjg.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtxdwqxnbb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtsggtfjbj.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtztljiozu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtqolemzci.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtdjimrswl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtkyouxsss.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtroazvwxj.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtiadnzils.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtlaafaiyp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtgdsqtree.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyzwwsqat.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtkafiwiym.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtykqhpbsh.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtftsblvzt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtrlnubqoa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgxnxtzoc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbruoatfd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtiqzilsdb.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtefkzltdq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtvhjxnxek.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtsazeyusa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtfbjejuzb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtbjcwfzel.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtqvxfswmb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtirzhtxxo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtkpivyaxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtfxppbjdl.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcdgkzxt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtomfjzhbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtgahkreyq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtjbpowdym.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtoafqjbhj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtnlzxhbmt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnpjacnn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gttqnkxrrd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtnpjtzxbg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvvqlzedp.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gthgmhcune.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvxregceb.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gteekylobj.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtvkyajdao.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwlcelyyd.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtthxjrivi.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtrsafychi.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtctbvmjrg.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtuzwvjlra.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjqbakjrl.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyvfwwuj.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtvoocwfix.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtngbfayuo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcwtlcks.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtoohpgcea.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnjpzqtgo.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtdyovllcd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtypsvikfy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtuqffengr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtldkkikuo.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtppjmmltl.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtoggzcvhg.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtxgwrbbml.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtghacghlp.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtspopwoie.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gttqqhcurm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtnfzaaoob.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtyjcfwjms.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtcksdzxeo.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtlsulmnzw.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtdhawvofd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtscjciyez.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtrhiggbzk.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtkpfglhch.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtjgfghqph.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtgvowfgmd.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtjrdpqslq.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtmdmobeov.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtsfbpcvgk.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtolnrriob.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtppqajtsd.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtdiihmvki.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtmayqojxi.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthlxecngn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtfdxcoyxv.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gteaqcuujf.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtlvlafatd.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtohsnwnsd.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtmocpprsk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtbwghcdhk.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gturiffcoz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnhjjgsck.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtrlzibitt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtbfiqhwnf.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtrjjrykwj.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtiwxrfvxw.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtfochoyzz.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtlqwxokao.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gtdhkhphly.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtwetyijks.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtruqatfxz.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtwyomwtpi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtxkkcfswy.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtwjbmoggi.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtrmebgxen.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtlxyitvic.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtzeuevotk.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtijssjhhp.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gthowelvii.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gttwaauoso.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gttebpalzj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtxsaapbcy.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtzdaeuzio.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtkhilpyes.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtrksjnyyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtmhjdozbn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlygrojln.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtmyegsszz.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtglmseuad.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtynsqkrqy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtcdczkpeg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtmzutxyak.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtwvgdnpul.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtbufupmyf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtrqpiyeks.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtgkhlgqfy.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtigyeigmw.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtitkottll.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtzgzurlby.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtyugkmcsh.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtvwwenehz.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtyvndqxut.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtlhtqegmm.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtfohslvfy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpmhicxce.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtsaupyupj.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxettmecg.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtvqrccpzm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtvedohltx.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtrlgxsjxd.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gtuolxqpbm.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtolmkfehl.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtuxsgukjg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtpgluuckf.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtmgqrrfnc.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gthovudiqc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmklolvrq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtnwmkwkvx.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtiwbaddeo.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtqhpjcyjp.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtptubwcyk.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipmhupyx.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtawdfzhlf.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtkzrsdsek.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtwalurrbm.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtrkukuaxt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtmhdrceui.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtmtgqviwb.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtllkxtvit.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gteywxajcu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtsrkdyzjs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtsjwaylhy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtexgbgatx.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtmffqtcrt.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthismjhau.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtziowfwnr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtecqapfli.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtrlvzkkxs.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtzvvyiydy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtfoabnmuy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtoihrzdzy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtdxpocpkx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtozuwxqhk.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtcbcnfmaq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtkqryddhc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtnrnspwrg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtgsstruhb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtpehiucku.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtludwncgw.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtsvkdbqns.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtrmvxoxta.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtfbqoxkkd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtwmkfbglf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtfrynqpye.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtwzbdukzr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtccyhwqro.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgkrazggd.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtongtrrlz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiyugpcc.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gtoqinjfpx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtubfnawto.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtglijsycv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtiyyfxawn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtacjzjjvn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtrqjyanpc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gteysqxvzh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtijrtqhzy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtntrabfip.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtwuqxjfji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtzwcnpvvp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gttkfamymm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglfrrqrc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtviiqnpwg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtldjtehte.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtywayctfk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtepglrgug.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtinjolwos.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtgjrvnalq.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtsofxaumb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtfwqgspty.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtpzcjhdxq.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gthibukqtv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtgpkyoyts.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtuqaigztm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gticjjrelh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtlljexemb.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtxmafdnxg.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtmyoboyim.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gteqvkqwmv.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtwyiivjom.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtmdssgbud.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtbkykmiiy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtmuxtijxm.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtpmjgsnoz.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtkxhrpbas.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtjixkfzxk.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtfvodsqvy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywqqvcze.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gteaniqfik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtupvydmnm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtqhlrhgzm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtoidvfefg.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtmchqgvkn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtdicsnulj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtkcjlmpvo.html


<!-- 参考信息 -->