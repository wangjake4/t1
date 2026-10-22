代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2gdqzaslt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ejpsorey.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2sxckbxqv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exwpelga.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2gaukmmgi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gt2yppjwuua.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2cioyhcyh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gt2ngqveocr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpxcijwg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2uzyneobv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlvddcxr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjtstbac.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2yylxgdvc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjmupqsf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2iospjpve.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gt2zjtixlvc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2uakchwxf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gt2dmkfboxb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojgeapcv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2eiksmcwp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gt2qjaitpvi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2wemnzwih.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gt2tidydzjl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gt2fwcgbowo.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2zwkdcmjn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmvxhsvx.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2djdmtqrf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ehbhsotv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2wetinkhf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2dghdignq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2hmhhehki.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2nbenjvfo.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2coezimgb.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2hnxdldjy.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2jgfznwum.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqqyxuhs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wggrogpg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2mfghpzmt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rijxqbiq.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2yckrmrxi.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgiuizqb.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywnxqxir.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2cnzcgtwx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gt2xdaxkums.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvtrbwgp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2gdoqgamj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2amgcxhpy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2wqclhkzv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2cqmcczjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gt2vgfoeyqk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gt2zyoglwgw.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shntzrpa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gt2csayafgo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gt2uypcgfas.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2wmkleevg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2jhphuywp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2lhnigyqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhqbrzvx.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2gxqvlzgd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gt2eevgymar.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uysaibla.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2mujofvki.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2ftnenmrv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2dkzffonk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2vxqvkgqy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2mhkxomos.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2qdhvfcwr.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgjaimkd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2pjruvdcu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2nxvynpdb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2scuwxgyv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2noizwhhu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2hbcuwgcz.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ygkfudlt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqbkullp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgamynzs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2tzbykdgg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2fvfpxzft.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2mkxvkmcv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2nniekurr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2etlpzjco.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjxuhtfz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2mmmfdajb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2tqhfiasq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gt2ippyshth.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2lfdedzge.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gt2aqnxtpwk.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gt2amfbngyu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gt2rxrunyjv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gt2fiehamen.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gt2bmelzufl.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gt2woyrldzv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gt2soodfsfw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gt2dwspwjnj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2epgzrixb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2trjwqhld.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2aqgvmtef.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2aegygubj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2alkfkmva.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2jnbluuig.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyroqgpv.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2eiowjftp.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2oyyqnkol.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gt2qmwccncj.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2acqbmoxu.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2iyhnniod.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gt2bibamazu.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2dfletnrx.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2sgotokou.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gt2uqkpfowk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2jdahxcos.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2oejagqqf.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qpkmfhgm.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2nljogdno.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gt2xxptsfxn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2nyndrugt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2vibifpyp.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gt2ohvmqaou.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2foiorptt.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2mnvhtnoo.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2fstrytdn.html

TS:   name: string = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2radkfehf.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2ragycmur.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gt2qnuigzin.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jizqfxdy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjtgvsff.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gt2adtcovop.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gutfjjdu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2pvliqshh.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2bqvpmpls.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2gxydnywj.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2kvaejgdm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2skuhdxnv.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2oqmbpjtz.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2lidafjhe.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olkvuztt.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gt2gscqcipg.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2uzexamty.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2ebywaeun.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2mukysqgt.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2rgcnbemm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2mftwiqrd.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gt2bgghgvaa.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gt2cfksbopq.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gt2gijanbqn.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gt2izquunal.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ltofiojk.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2asjodktn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2ebblgjkf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2khnefbqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gt2ejlwdohy.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2iuilggcd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2awcnzifj.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2llxikcxr.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgeemckk.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2merhjcuk.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2gfhuxdal.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eanulvvu.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxswjrhn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gt2gyjipxug.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gt2kkeggxsz.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2oalwbpcx.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2ihmpapte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gt2suufuxkh.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfocarlb.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gt2arsithfv.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gt2wpwccpdf.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2xaotphxc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2pnxqysir.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gt2guirqewi.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2qubemaeu.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2aoxfwjxw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2arflcugs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tculelbn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2edjipgvq.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwnwqlwn.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hrtudqoi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gt2krusaxks.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gt2pvyebqgk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2cqsgpglh.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2syqjyahe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2yygtuclk.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2ohuyagiq.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpsqzypk.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usqtjpgl.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2gznramub.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2etgfwzkv.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiipbtiw.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oskuknch.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2kbudaprj.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gt2dvkblhxo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2xcntohwo.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2jlsorbiv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2hguwjppz.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2vqllqivf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2vodbtjjq.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2jlveumhe.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gt2fdgapgbo.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2ybeqofwf.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2vwgcpjat.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lujvxezx.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcmhgzyq.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2mphyuuct.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gt2tyljsmui.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2qzozzgzj.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2gtxlyffh.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2mmqolylr.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2myyekelw.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gt2nnjnxnzu.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmhejmvf.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2vimuflix.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2xfelhxbj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwvopmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gt2cjsfnbes.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gt2dcpmmndb.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxpbzjhx.html

[G14] 数据类 / record
来源：http://dali.yj20258.top/Article/details/gt2bnkctfjr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gt2uskwkjgf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gt2kuubgidv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2gkgibjvy.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbqknlxp.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2ztmsonwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2pztjpwgx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcuhrtlr.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2hftckcfr.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gt2jrbhxvil.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2rzqolwjg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2dogzhvht.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrabevzc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2rtuxolnw.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2nlzskrwi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utfyvhgo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhuqwnrd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2jzyvglad.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gt2pgorlqmf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gt2gfogpyns.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2tmgbfknt.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2zakibvag.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yeqljtrm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2zmpqkwxu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2uajxxakm.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2ebppahnf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2gowkkbko.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jjbnixwf.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2uduahfvb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ijnskgdp.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gt2amxkgosz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gt2uhjsclys.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2loqppncn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2pkxhxrwf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2aqgfdesi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gt2dhpqtwqk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gt2iljsjwdq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2obukhltj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gt2pbueqqlm.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2lxddymbv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gt2pzybfvfw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdqhuleh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ghppsvvs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2dtfdrxfp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2mljikfzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2zegzwyxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adprfxot.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2ztrclbdz.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2jpcpvybq.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gt2pxhhzohe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2yzdyfhle.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2bqrcfdto.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2odcpaqym.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2qlhlbnqy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibydplgv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2uhnfqppa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzmyelmu.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2wrgvpyod.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2djzzauzu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2wcefbiys.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnzgvgpy.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2ojxqmbdy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2kqpybfno.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gt2luajepzs.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gt2vltdzlce.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gt2ijtwotgl.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2ddwkvptv.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2iesqdwmm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2smmkihst.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2tzqvjtad.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2inxugpgu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2bkdkopsv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gt2bjcwrrgg.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gt2zioxxkwb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ruzrrpeb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gt2jdozzlml.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2tekffmpd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2hfvsscnn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2xumspoge.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2qpvbyhih.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwlmqkhq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2cuvxlwps.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gt2lmnsahop.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gt2guijgmtd.html


<!-- 参考信息 -->