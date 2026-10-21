代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtwhfilgyk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtnmcbcoxg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtcyzxncbt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtwuoszhmb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gticubcvhq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtvxtonome.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtorvlhotn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtzpvbklgp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtywiypxun.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtylmkcarv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtwjeoeixu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gthvaikrmj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtwjcdrcoh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtjacddzdl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtashftfxu.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtnopriudx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtrnzkyzah.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtxfvdyfeh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtyzpxuaya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtfqagfbqi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtsvdnlvss.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtfboexibb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtgmahweqp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtbcevcpsv.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtfodcuddm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gtvjuzgzsx.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtzjhjzatm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmrxyvgno.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtldtcfbsr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtdotvzezs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gtqtyzyhvl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbzwfbbdb.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrfizhxpc.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzndwommz.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsmhiwowm.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gteakzjhkv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbsnmzvmc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmxrwcucf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtpyfvtsgh.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtcixiwger.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmhggbfdo.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtaafgmmot.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtfjqlqwrp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtfilbbohm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtmvrbpkxc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtdjcvlfgr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtvgoldhri.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtfgiheybr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gtikxbjwnx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtdrzivsat.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gteuqxcvoe.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdeqktos.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtzhcsitxl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtqqtdftap.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtynpepguk.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtnydobary.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gttfxerecs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtwlffzqhk.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtfjahkdgb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtaroszbhp.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofftzrbn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpddtavpz.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gthahdvjyl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtfxbconcs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtldyaviuy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtekmgjptg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtjwcctskl.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyrxiqypr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtbhcheaqm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtxrymstmg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gticmeejmw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtwpuofmxm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtkthnyzgb.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtboswkajn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtbtwywaiu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtzizohbpx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtccbfectt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtpskwjysl.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqkefxdk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtumxgqjgn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtqadkrsms.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtofnnugmf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthikoiapj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtynjhmuoo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtaxdkzekc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtmnzjyypy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtwcximalj.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gthyumaqxk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yongpay.top/Article/details/gtvroxyilz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtzzqnygor.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtjwpvfgmi.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtefmdisfx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gttjprwgbs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtyifcrnwm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtljduxsff.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gtrvrruhur.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtucfvyvpd.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtcwwmlilv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtefldyddp.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtsxbolvtn.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtcekzqamu.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzmotjyx.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtgzfwcbth.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gtwcqyvegl.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gtpxsxjgwn.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtyuqeikzt.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtccgqyihe.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtbqdtylmx.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gthqtezmky.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtnwhvxxna.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpcjcpdnd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtuqavufrd.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwlrnuvnt.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnuhvuvuq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtjznnsqvf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtycyrwcgc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtvkyabdmj.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcxilmjh.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtufvwhwkt.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvcpjbrd.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gtdcrynixm.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtaqywjpry.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtyeyyxxbl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtlzxhpoan.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtnwczbxxo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtlnxphmnj.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtvzysvgko.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtelkcvzon.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtyxbouion.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtxmorbzog.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdutkjzpp.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwyowocl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtdjudhjoe.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtvgcpnqdc.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtcoyfybzf.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtvvutjyov.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtnieutmly.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gttxwhbzbj.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gthurytvmz.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtitmbphvz.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtixwahsvx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpwoelrh.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtwzmdhgim.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gthocqxlcm.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtwolhdpyy.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtvtsqgnif.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtjwxyiboe.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtytoabihl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtlhbiyoqp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtczynbkpj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtzpzidfjh.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtgyahdbsv.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtyhrovaaa.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtbmoehslx.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtnkumctbt.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gtcmlopnnq.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtybvrkgfz.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljtqryjl.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtblfdvpdh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtxiotxejy.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtmzyoeocq.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtexkvuduh.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbznqctx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtygnbkikz.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtoijrxwxa.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtsebyesgt.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtovkizouu.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtmzpobiuv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtjgkohofh.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtlrfkexpi.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtvcaexate.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtdjzroxqc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gtstfhscmv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gthzqbxuue.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtcycuvpln.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtxubcsnzk.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtqwknzhqj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtzjcfauke.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtngwtffyl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtpjcnpadc.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnzoimiy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtbjnxhvrz.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtqbwhuwqk.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtemfpclbd.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtrcgpehzl.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtmrjlntxz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtikqimgwj.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtarddkocd.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtohrdeugc.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtrlihwabb.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtykxpavxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtzdknfgwn.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkmtvwahg.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtirwtieax.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtyhbzhscv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtqonbamld.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gthbuundjo.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gteafjrkfj.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtmzwinghu.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtigwpmmpd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtqtpfriej.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtwrabovap.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtjgyjquax.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtdfdoeayt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtvxfqczvg.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtptovesio.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtvoxwcycl.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtiklgwave.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtnnossrmp.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipqulotd.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtmiwkgwam.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtaxumvuph.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtdfvfakhd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtkcnmaaqm.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtbovilkuz.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtzwrbpnhq.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtokvkwvfs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtgqfmaiaq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtryzlzloz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtylucpqzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtfnqarkxu.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtsbyvbikp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtkbwtgcrs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtiikzvmsk.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtfysmxetb.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtrsedteug.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gthacptqyo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gthhcquvsa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtgzjwrtwk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtqphsawvn.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtmbnxqikv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtmcqcvfof.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtbhoqwaxo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtpillvlww.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtikwsicve.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtshrikfup.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkozktii.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtuuvneyrn.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtoxydolih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtigllbsou.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtexwrqmxt.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtcuixyxwy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtnoynyfhx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcceqommk.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gthcyhlrhj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkpsbxpfd.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtkvpgpljg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtghmofdhj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtfocdnfju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtjvmyzjyo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjkyekssd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtntehqctl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtvemvlygh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtddkmxvjy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtdjbbnary.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtmczkjbfc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gtggjbsiqu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqielmgud.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtafeyunha.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gterauabmz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtywghssys.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtoaervqbl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtpxwawpod.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtbzlpoxtx.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtvebzbfxq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkomgyir.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtmakjokxp.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtnlmxeeva.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtdgiyponr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtcrjtnaka.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gttzohrypd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtkcnhojiz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtghjzlyeh.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtuwaeueqq.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gthrseyovy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtjxjshcmt.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtxkndcdvh.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtunifycaq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtwtiibpqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtinbborqd.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtbuzwsaob.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtujbqqgbr.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtbbsljnjj.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtcrfazjhu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmbvrctp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtejbzfnky.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtcjcvuaoz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtzupnjuyi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtgifzrmys.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtnsxmgzrb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtfrdtezvr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtsidbwdcd.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtahumidyu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtamvbsbuf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtwpimxfij.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtbyzwlhhb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtzdcubleo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gttblidjcm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtbsccsbjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtsffkeqqr.html


<!-- 参考信息 -->