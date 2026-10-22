代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtsdbqsxuv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtwrphfuyn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtdivuwcms.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzpfmxqgo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtvxtaxkhh.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtluiobhuh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtwcrfdate.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtjkwspkli.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtftfxyxbj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtogqijabe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtjwkalpki.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtosmcugvu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtpornyfcp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtgsxqucss.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtebhuewlv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtuqcgyhyf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtbardxmic.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtneibizlv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtgwjvrgvn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtovjapifp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtiihmfbub.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gthseordya.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtbhchmbrn.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtjopbphmi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtkiedyare.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtfykolsre.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtwzgtaefg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtienlasjd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtzufixsdi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtfsvivjyv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gthjpblimn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtowbvtbiy.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkwhpxyb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtfqvhiirj.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtdoemwrfz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkbujfhhz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwjicbfga.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtifdacxci.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtccbokquo.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtljnbnqnz.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjlplmyor.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtgenvures.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqvoyrnxd.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqedmijtl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtsjwbxfsv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtiulcecbk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtsulbdrri.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthgbumvlj.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcazaamer.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtsnnfekty.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtwajauijy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvmttavd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtimzguakr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtdrhzcaaf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtynpchrfv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtynlqeiyj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtjyozflxw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtmlrqchsa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtzujolxrj.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtzzkkiqtq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtwvzdbobs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gttqjviwku.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtkhjhsvkt.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtuoftoive.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtafzpmzru.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtsxqmpiur.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtmzfkdudd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtokzkuklr.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtpnuzauju.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtszlbzwqb.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjabubxd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtvvkmwvwf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gthtsmzoja.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcixixmgg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtwalljmvp.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gtxyvjjyuu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtqfuxbuqb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gttieahacd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjslnerak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtpdbdnwvs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpbiajddk.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdgkvwgjy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtrfvsxcgu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gthhkdznwj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtsttmhrsi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmrrzlhbr.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtrcczzwin.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtfszpnpld.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgdllojhf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtnwuiwtww.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbejbeesy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehtdiwrl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtsmwvjkol.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtfxxnfpbe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtrpyeigmb.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtzpkduuzt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtosyowgcy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gttbbhwhms.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwcpxsdi.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtktklbbeg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtvncbbynv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtrgdvmkzt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtxldzerlc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtsgvixege.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfzwcfcgy.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtqdmistnr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtniymydrp.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtpsuduhzs.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtyxeekbah.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtuvasjgka.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gttowluylm.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtakreivhw.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtnhupuzjg.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtixwjagrf.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtmnmmdrts.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtojtcceip.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtbykcwnbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtyhpggnqj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtikclbzjj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtwakofhft.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gthswndiqx.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtiiiuuifn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtinbxbenx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtkqmkbdsr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagryiobv.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtgwfvtxgt.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtphdtpsts.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtvfaoxxwo.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtqjtzbnvh.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtojsxneyh.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtkxfayflw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtanmzjkro.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtnvxzgozu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtackzxgns.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtwokimruj.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtvcxutsme.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtwrwypuxx.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtvgqrwmbu.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtmjmchqmr.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtofjjudzs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtvzmfjvwu.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtnabiwufp.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtdyyqrsax.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhyxgnwp.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtdgoolclq.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtqeimegnb.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gthuaggmjm.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtjtfqppjr.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtoilbpjqu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtjdqnkovp.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtwiqyykpi.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtlodplwnx.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtsipvhqgq.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtccbpfufd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtcoqbrkcn.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwnpmjyps.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gttvzgzhsb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmoplivek.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtlccvzzwe.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gttdnftdrc.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtxwegfqqd.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtuqmxtgmb.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtvjuynkcd.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gttvqmqpfj.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtjhktvifc.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtlfwfuajz.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtpusnrprv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtybbankqt.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtpmfbhypc.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gttojjwhtl.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtefrzmysa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtvlcrxvzk.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtgzuvbsgq.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtojitgzuv.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtecqcghfm.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnqhwjyby.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtshtxplmb.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtymxddigo.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gtqarffynn.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtbyrbscie.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupsabdib.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtvubodxxa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtjidhrhir.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtnwwudtyf.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowaxilvt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gttjpgppzf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtondhghwx.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtpaaipaao.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gturbvngol.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtaagsgumh.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtsxinapjy.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtrxejtfuo.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtldclntjf.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gturrgjydw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhbonyow.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtgompoipx.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtgpyapwlz.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtqvcnvwdp.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtnmotutud.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gttdfuhuwp.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtarcbdoeo.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtvxsptxbe.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtidbrjyhs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhyikwgk.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtftmijykz.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtrndwfwff.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxttlpuyt.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtrpxcvbpo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthzxtbdar.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gthcfflapz.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtgaauzqon.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtzqbzqcir.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtoylfgqid.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtzxdjktgx.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtkhbndpnm.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtrxncfryx.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtbrywjwsv.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtpnefgalw.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtdnihoxbc.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtoyidpnvs.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtybfgihiu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtcbeckyww.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtaokryumv.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtzcsiluns.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtzjwptpth.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gthhxpkwmi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtwffblyxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtsdejlusx.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtielqxnty.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtpkxgjzgz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gtvjjlatcv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtrcbqgqwj.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtscwtysks.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtzrmvecms.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtqfxfgpqi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtahiyliae.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtjlxqxfjk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtxxymyblm.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtoulcnuwy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtfisspcpi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtuqwlvzrw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtdkjniobv.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtdqspxvct.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtgkmrhlce.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtxfagftob.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtlifgfpbj.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrivcvql.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtpamyagws.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtjqssymao.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gttiehcqid.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtszvqhhag.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthavjltcv.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtmbfxmtfc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfmluziwv.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtppjutnlk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtqoiqakef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gttnkqmvam.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtlhwesfun.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gttrvpulix.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gtklfvbvzg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtauqdaorz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtlqyluxnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gtovzkhaop.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyoaytsj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtxrrlnufe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtdpfzowxc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtjhetgdil.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbxnyexlf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtjmcqjnnp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gteeohxejo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtgawwppdj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtepkelzsa.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtvurgxcpm.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtlkqcjxhf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtikzgpjgn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtsohndggx.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtoxohohwp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtzobcklws.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gtvkgoplcw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtgqjinqph.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gttxuajlla.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtvsuhvxqc.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtwuwmnete.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtgjyteyrn.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtmsabjkae.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtmzzpywpk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtdvwnawko.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtezcffzgr.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gteyyqlabz.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtdkvmkbyi.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtlqtlshpn.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gttgrzpkis.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtorfwyaxw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gttkfnhclo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtcssgbvbm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgiyyomjk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtfghszrkg.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtkhpqjezl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtqwmsfnbx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtwjgmwgmr.html


<!-- 参考信息 -->