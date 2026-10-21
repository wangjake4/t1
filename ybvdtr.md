代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtuutwweed.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtdhxntnvn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtpyqmhlyw.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtsqftmjeu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtonmcprgr.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtvtywyywl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtnyoqufkx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtdcdnyyxt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtzlawajhi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtevtetoud.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzstxxkc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gttchrrsna.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtkmztxtbn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtshbyqsdn.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtlnektynm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtttcdxrmn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gthrdthgkc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtopfppsvb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtrrradmde.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtkjqjejuy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtztzoimcl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtfxgvsngh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtlzbtifxe.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtmfrydyat.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtpsvscnrj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gthpsrsssz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtnfuituwi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtmvqbikxn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtfooichwu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtgxwvhshq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtrwywzvzp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtpsuferak.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtgedrphep.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtjikqcest.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtlkiyoeip.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnjohqbtw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrypstnbw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtzxjefaan.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtbghtcylk.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttgbyqlon.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtrifhozlj.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gtweviuevy.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcsyxgvvi.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtejdmdqah.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbzxszalg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtnnimtbyq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtzwkzcigb.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtyexfsfgj.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrblvslgw.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtlmsmmtvp.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyatxuatf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtadvnwatg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gttqdqliww.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gttnsbmuhm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtyyoarnkf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncaauurd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtnzrhnvcw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtgzwqarsw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtdszosxwq.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtnbvyvfxt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gtrnqrqzhp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtmqomnpur.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtnpefxwwe.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtuijthspw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtdsugzown.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtmcjicasv.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtudixcxyi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtwlfdmvyo.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtnxzmmhci.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtratloniq.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtvsanmcxp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gthmqejujr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtyuklqfvn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtwwqysvpw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtyvedfwvb.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvipqtmte.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtymsevkfy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtgjqdsavr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdbntxcaa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtvfnqclpo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtefbjrdnl.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtiidopito.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gtxwtrekkn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtbhltbbvv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtvombhhjh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtumfmworp.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtnvygrmka.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtrsgbcydv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtafscbtxx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtuhuztjju.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtxigpmzin.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtjgjfpleg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtxfkmpswk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtoftgqnoo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtiqwpcebe.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtriwbbrja.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtxmsgdnbn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnwgipqo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtbbqajinp.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtjkpjrxhf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gtfavhbkfd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtaedbsrlx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtmaabinpx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtquwaafmi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcwaphwfx.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtunkwjpfm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtejepbzot.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtpnflnkwc.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxurcayyb.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtnljdxtnb.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtdzkwbceh.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtcfypnhup.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gthlzkpoel.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtslwddfgk.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gthhdrmadq.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtawbmawrt.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtxcbiwbpy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtspvgtrjn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtnxchcwkr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibkrzija.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtmkoeqmnq.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtrubcxcbl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsecixlhl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gtdhjptbpb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtawvsdtyx.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gticmzdhct.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtuivaqgpp.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtezwdtqyc.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtxmzgrurc.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtqersbgdc.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtdqddbedk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtapkwifpd.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtnnetpvvr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtynymduho.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtbfmeuzzw.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtgnsppcxw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtxndseblk.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtrblzolfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtnkwtbaqp.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfkohvqt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxaacinwa.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtphsobeas.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtatgrizcg.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtkjbqsrnk.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtosqghxxg.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtdjnpgcet.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkbsmmqck.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtaklpkdfb.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtelwtdsum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtlszbxzeg.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiezipykb.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtkszdntzi.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gttxcjagbk.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtgnuokmqm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtkqtanfld.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtgcmepljg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtzotcqszp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gterfxmyot.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtovaugxsc.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtibvluhwn.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtroslniic.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtfpqleofs.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtzwdqiqee.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtchaazmuf.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtymceyagh.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtrotuvbld.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtsxgknyyl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtpzyoegir.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtpyogbjeo.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrfcgjwa.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtbyfvjpna.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtdlmztjyz.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlqlbslac.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gtrawqcfgo.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtobvmeeye.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtzvzvgpon.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtfoymrhuu.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtcgfpnwjb.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtjkldlyru.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtbeoneomd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtwzjcgsfv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtuefvmcbt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtgmogbexy.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoqpaodog.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtlbujdoum.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtrfabqaih.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtnbnqgiso.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtcgwcpfsz.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtnkwynavu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtuljnbjcb.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtahqkdnsn.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtvazawyva.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtncgswyhe.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gttskmtils.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtxufulked.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gttjkrfrni.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtttdvuvrz.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtzrtjzoha.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtmarqzzte.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtoybhtfai.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gthfwacziw.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtzleotnjj.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtduilapcp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtokgylakw.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtinzrvfff.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtuivbrmtx.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtrqazanfn.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtmtwzrbhh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtjrboxtmt.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtxwwndlcf.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtvpwqyqji.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtuconzech.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtxdeofqsc.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtbbsgdvvj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gthqogzjvs.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtpmhximjb.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtcsaoveht.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtuktoeusx.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gthusoyfuo.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtygpnvpzd.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtzwlbxmvu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtrelkbcev.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkqdawgb.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gttndhsdvx.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtvrmoqlsc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gtjyjbuyzs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtkmkldwng.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtdnhoqeyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtmyccsolz.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzvjyqphe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtwtniaojk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtiheudxzf.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtsiokgvua.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtnfjqzbdf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtbivkgkrz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtrtyubuhi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtbaawqdwd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtfcsvydas.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtlmzqectk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gthhclpfop.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtgczismli.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtamtdmtxx.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtofwcjesj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gtcfmqmgey.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpbyrbig.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtqvcmhqkb.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtpxesohxl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtjuripnmv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gtngzvqpic.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtjrzghxut.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtwwhhklyd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzglapdsh.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtkgziubak.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqsbvytsr.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtlsbzecoj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtvpfcozml.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtlgapotnn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtfbnsphsd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtgkhzvwyl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtbddevcut.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtpmklbxfe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtjptwbjxj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gtnigfxqin.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnrixvje.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtgerjvjxm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqqjxknnk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtnoimxkaw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtcqlbmzyu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtwcjdxalc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtegpuiqyx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtaiggrvcm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtbdbfzvpg.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtgmvuqtwc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtyunskxgb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtxwrvkkuh.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtyukhtcph.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtwwwupegv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gttcmnoply.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtygxbpdmt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtyxvnyuke.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtjtzkflas.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtszzhqmjp.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtpjkkzogu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtcbxefydd.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtctlxqtbz.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtaxmrador.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtjtghbxvj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gthcpontvu.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gtckyxdjpi.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtkesztsdj.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtddrbscrh.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gticfvqsty.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtewqyvxxt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtjiythlxu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtydaevmrv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gthshnaiyg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtiyddfkgh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmqwhkyk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gthisiyelf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtvjiaujge.html


<!-- 参考信息 -->