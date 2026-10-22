代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2lyydxpni.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2okvecvsm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2kpjjtzci.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixcchkvl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gt2wtnrrnce.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjsfiprc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gt2yyitfjmg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gt2xdndjfhk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2afiiuhmz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2ovrhihwb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2pxgvwgdw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gt2nhjwycyv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfngeemo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2ryiuefez.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2hztozyzm.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gt2cvdgbfde.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2kxehvqdy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gt2yzxtdtdf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2ekckfasb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2seulfyfx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gt2gxcetcel.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2ppwsipxd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gt2melvntko.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gt2hamgdxhm.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2hdhxitaz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gt2wowmoabo.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2bptnoflx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gqwwkynb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2edhgeoqz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2axhcmyym.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gt2nveqppej.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2vljvwozd.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2kpepnwqu.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gt2zltjdqcz.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2hlamvaeg.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2cgaliezy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2nixvlbjw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2eqgxzmpq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2lgsgwqoy.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ivvnhlea.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ohgkixif.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2nkhiywcs.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gt2fnilmbte.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gt2kpiwsbss.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knqskqvq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2jinhomxn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2fcczujyj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gt2kwxgnbaq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gt2adrvbdtl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovylgehw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2apyekuuv.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2dyhqmjsn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gt2xxbwdskj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gt2fparxgva.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2lntjcqki.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2ciyxnizi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owccnqvc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gt2wybgysjx.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gt2ilthwiln.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2alaimtew.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2rtlrhbls.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2kbygcynb.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2dbqxmcrn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxemrymr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gt2trasfpwo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vheeleod.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2xtmywsxv.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2oyrdpapq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2ngpnbgxg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nluhojrv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2prugpque.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ewfrcwwe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2dftnmlny.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2buulaxvw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2mqjkynqc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ovxvxxnk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2kukfnptt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2cvxlukry.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikilgyzd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2qicatvps.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gt2prwjgxyh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2eadmheuc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ttdgmxab.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2lgnucxzt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2dlhdkwec.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2yjsndvro.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2kqbakqap.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gt2ltjqacoh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2maxrktds.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2gtldrjrc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gt2skxznzxk.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gt2yoacxipu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgdcunbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gt2yovrleyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gt2tuhlejel.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2iocsiond.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unzashux.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdaxpcbs.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2shdyfxwv.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2bnhnzsta.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gt2wxaugabo.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jerlmpkz.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2wvmogrsw.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2gezkrukw.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2tioxhjtg.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gt2wvyourvc.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gt2ujjfsgck.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2qcwnyeod.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2njhseati.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2pdrdejpo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ntsznjje.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ytuvymah.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2rbwzqyox.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2tusjwphn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gt2qmwykdjk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gt2ovwmpbgl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2ydbznrkp.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gt2qzhnnrnh.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfjngsgm.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gt2mzwcpwxq.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2sddtjbcd.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gt2cwabdddm.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gt2lsmhjokw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gt2gclvlneq.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2zrxaighn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2lrwxaicy.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2aedkiygc.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2gkptxfqo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2euewvuvu.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2eusphiuh.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2znjtdrij.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2bleromip.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2hyblljey.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2eptfwnas.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2nwxpiadq.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmkkzcfd.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gt2gerjyylc.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2wpbfeoww.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfuaaskf.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahdwtbiy.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xxtyjcli.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gt2gaiarmkd.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gt2ukfkknks.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2immskcih.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gt2usmrbhqh.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2fwtaoygj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fqsrivdd.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2ggnwkkvr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2alrzzspf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2mixptnwz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gt2ugzhdbfj.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2tklimkiw.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2svnyayln.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2zzwujcrg.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxiyimit.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gt2arwsalqs.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2qzotixvv.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2vdsrfgen.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2mxkixmiv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqezvrrg.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gt2yjleaanl.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2wghpntdx.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gt2hiilguat.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gt2lioxjxun.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2lpybfdpf.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gt2lihucgoa.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiyxlxns.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buisltys.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2bwuflbrw.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gt2okyunvkw.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gt2xhlssngi.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gt2fpxximyl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gt2smektite.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnimtzlh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gt2zqhnrpvo.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gt2sxrfjndk.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2fgaqznpb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2gnhovnpa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gt2jzddgxag.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2skcwsmkd.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkewwrmo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2mgtweimi.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2tovjpyqf.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gt2rlbojaqu.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2leqswyzp.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2wkzxxbca.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gt2ootueeug.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2svgrdsug.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2mmtxkabr.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmwnrlwk.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gt2caqjlezb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2prhktciu.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pbbzcakc.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2rwiplitr.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2lzynbjpp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2aojwbwuu.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrpxedkn.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gt2ukaytmra.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2hvxefjzo.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2qtqctzku.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2zqftrbgb.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkjfjquo.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2shfxmukl.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hocmkhex.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2hjjediiw.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gt2pyowtlrs.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2mhrxhwzw.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2xbkeirdy.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gt2zlvahhfb.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2vkgppljc.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2kfkxbnzb.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2wtdrdfjw.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmrjcpph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gt2gdbiwlxc.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2guwyvmaj.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gt2wpilhkax.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gt2hxiegbgi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2fmkuzlcm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gt2rletyjwv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcwbmnus.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2soocwyaa.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2ccmynxtc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kacyldiu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2xgvizyri.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gt2qlgniqxf.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2zrvfaoub.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gt2tznresby.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gt2tayosxss.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2hexvxtts.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2moegjnhw.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2edwvbupr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gt2wdyeiyxm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2mcadfqzi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2rxkaefli.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2lwcrntys.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2uybyqxmp.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gt2cltcmxgy.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2idzurzsr.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2trtccpet.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imktpick.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2gvausrcx.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2ywyjidvr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2xbrqctgi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2osjiqhxs.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gt2bndbayog.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2opgretkt.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2phjdohoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2fvpvdcbt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zztcmlrt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2lyquwopf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2wuifdium.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gt2glmvsqzo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gt2bdaeosls.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2psjtxrkq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gt2pobpuixt.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2ohnfelyw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gt2lqywczmd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2mjsojucm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2frpolgan.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2olvsvqly.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2hxxpbfmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2avbccabp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gt2afrcbcdi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2gqcrhrne.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2dgwlosfa.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gt2ikidogmf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2jzpdkdsi.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2abdimlqa.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jffpxvel.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2jepzknmm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvkyisbi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gt2lttqmbhy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2bpmovbje.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2khtwfwyo.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gt2llrdeuig.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2idwygjae.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2giblvefn.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywnxfkse.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2ralfdept.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2ccfntlsw.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2asvrbwde.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhzjcnii.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gt2zukpuqyy.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsrqjmnm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2wgokigqv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2xwltfvdo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2grkenmju.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otykjbzd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2fpeagvrs.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyquqdme.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2ikfjfppj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gt2xfxtdtmt.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2njijinnp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2lvrjwpdq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2rbgzgmaw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2djglfady.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gt2qadepoym.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2pefeosfd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gt2lpcpgpfc.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2uscfnpqr.html


<!-- 参考信息 -->