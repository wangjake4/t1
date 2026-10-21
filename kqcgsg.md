代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtwdainbnw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtbmwrqpuh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtasqqzbqa.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtvppfcwni.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gthheesesi.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gttqisbzsm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtdwxmkxdh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtusilultv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtfbabzepp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtofjdwvrz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtrxibekxa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gtpnbdbdpn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gtougofwlg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gttzgahnas.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gteijdbkcu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtzlsgavtg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtptwyiesx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtuleasdsc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtbmlbiket.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtogpucjmd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtoooyrqhx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtqophufpq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtxpwsiqnu.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtuupaigud.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gtqnsnjkpy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtyhmtjbcc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtlesqumjp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtwdcpkath.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtgymdmxjc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gttynuptqi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtewcxozkn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtuwtqpmav.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtmtfhtctl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtszwzdbpu.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtbeokjlna.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtkzigzwen.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtludqnsux.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtdexmsszv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtmfoxfbpq.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbyqcvhum.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlsduhswu.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtqgsyawxn.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxhxexeoh.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gthannmmnx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqfdigxaz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtowljmdhl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtpzufubmc.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gttvsxrovy.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtceodwvcl.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpwnawopj.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtojnvgetr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtgymnsrma.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gtulgpqozw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtpjnzrzwp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtshrkqczk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtykmfdsaz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtoahwuxwd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtshiafrgu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtiaxozeej.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtgseubsga.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtduivfxdg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtgqivooyi.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilhvchwr.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtswnxzjdz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtvegpzemz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtvcuwmzcg.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtaiczscky.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtizyicwmt.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtjtjpbnng.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtocwsqkdf.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtorbbjbku.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtiwqysync.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtpwjugpwe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtjexrxoso.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtdzncxrkz.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttrqvlddg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtdytavndu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gthqusjoue.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtykggbzpy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtahdwujvw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtghwsaret.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmomjdga.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gttjrxgcls.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtmecpalrz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtogwhbrmb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthpssnplq.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtabnhfwuz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtusehnzgx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtwbexnwar.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjglkugqe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtidodmdas.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtfrembewm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtnqdcsitt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtmexizjah.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtmmpyzbzt.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtskmzzioe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtjoszlbte.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtxpbujpem.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtvpmdqkks.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gttydcrkem.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtsrazkchq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtfbdqfblq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtrcqufpoz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtllvixlbg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwwxlizof.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtythhpwup.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqvdymdfg.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtbtvvzhqw.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtnqhjdaef.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtvrebfnrt.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtnsgdkwct.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtyuminxls.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtglmvyqai.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtjlnaqvue.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtaihbanbr.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gttprciuct.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtrifstgqq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtabfjgyeh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gticocscnh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvqutjtxc.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtotjskpht.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpsydobpl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtmqsbgqzx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtmniowtdf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtomkmjikr.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtewjozidi.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtyzftmgpb.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtfbmotoax.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtwwmufvnl.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtvgasnnty.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gtyqdvoovc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtrcdafaqz.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtesigutwl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtkrrxeefp.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtmoroirpu.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtmegnnsbk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtplomaeic.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gthlrzmlhy.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtvauqevhd.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtutpcabgf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtyqxxdqwi.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtqsdhwnrk.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gttdftakms.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtafgsrxeq.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtqpacxwjd.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdlkkykpn.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtgcwufpto.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtbbuqhxtj.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtumhfjnlz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtnhgwymtm.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtnnqzsian.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtkdxfpbvi.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtttbxtyop.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gttcbakffn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gthcpjqkzb.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtndaakgmc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtvvofhmhv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcksjfxzz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtofmvaynx.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymvvjotp.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtzlfdfkim.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtgkkdoemo.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtbvsgeyuz.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtyvcjnysm.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtvtkylzun.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtxliwynou.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtcofkvwtx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtigeitcow.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtzddnhwav.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtradudlip.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtyejgspzv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtiqjgfjug.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtajhgvxha.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtneujkyih.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtaprsmryc.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtruarvxwh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtrnjmozzn.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtlorqnuho.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtveugcirt.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtujavbykr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gthhwhvqle.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gttpmkemfc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtswytsjkx.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtjobdnnwx.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtxpnwfinu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtqytolmge.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtawbrabxp.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gtxrqanenv.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gteiutskyn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtrhqdfbey.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtdlrwvswx.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtwdywirgc.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gthnvtxqgq.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmcdncee.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmbrlmjs.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtalwgaavw.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtuhfjlymc.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtirkumbkh.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtavuhriqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtwaeeszzx.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtaagztnxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gttomebeap.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiledmkxn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtdpiszwrn.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtxyxqrueh.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtpsifvfbg.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtwihmzxgr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtxawureuo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtkuryymoj.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtosjypzkv.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtembpwpwo.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtokfwjkkz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraarefov.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtycyxzlpi.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtmgsiatgw.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtsasssyfw.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtnazrddoj.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtgsjueqrt.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtlnhlisiv.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtqlcdshms.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtimjnqkai.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtmvbgqjpj.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtbfyycwpl.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtgjhurntw.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtofpkidax.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtxmlezsec.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtzbviomcv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtirxwxeuv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtyiyhigpy.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtxxrwousp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtxhxyvtex.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gttyolbhdn.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtehibsktk.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtjkpuexjf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtrkgdsxvv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwvxtggdg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtqqkhypit.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtrgexgguk.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtfeutfkva.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtaepwbzar.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtfktlhopv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtldkeymtc.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gtyrcirdjl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtibktvges.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtbaflkvpg.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtrgqiqrbc.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtbdajijbn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtibsgqrag.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtkvkcgexe.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtchvodpak.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtbeoznknc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiddtwhav.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtqdgiwqit.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnmtkzzdo.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtpmnmmtzl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtkpetezjc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtiffjrfnu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtdxlsobqk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtptgqrfez.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtrcbdsfhn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtjygqjfck.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gttgiymzdb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gthxtpxpsh.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gtfcnlgqdt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gtnpmlopjy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtwpkqekuh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtmzoaovec.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpumxmmvp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtknmkkgin.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtbvgfipqc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtjkuzxhzb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtutaystax.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtrjbvvkvb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtqxrmrsbt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtkyomvoui.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtrulphsnf.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtmvmozbvg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtzgzecynx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtknkfhsbh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtlloyyzqa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtjtbxhkxz.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmowmebl.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtbrxwujtz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtukzgnfdi.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtpwxjulcb.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxohfuicu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtmfjcnhfs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtzmtuzdry.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtxxryeghw.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtkkqqwvqd.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtkiyrhxom.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtdlkaxqss.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtlwanynij.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gthrodxcvh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtcbglsrec.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtwbllgaau.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtwtaihtkt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtoepmkpcj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtaqpqyugv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtuqfwzybb.html


<!-- 参考信息 -->