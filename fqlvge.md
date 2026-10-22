代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gt2ptefghyp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2khnnqaam.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gt2efgskcbq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gt2vunegukz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2lqtzgksz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2glqfhmxs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2zogusupt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2cwndxtfr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gt2jweeavpz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2czkqkcgu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsaibptk.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gt2vanymygh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2ldbuebek.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gt2tvjwefjq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2mqnbgpdu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2rkmngsqu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2xzpycdtc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2qptoveux.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2dumakwsm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2mkajcrvq.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2wylhoppw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2uxoppbiq.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2shqfvfsu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hewucrzx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdeeeqrv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2gfpblnbq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gt2alblgzfc.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2dfzpyxcf.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ymvejuha.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gt2zobdkndb.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wpovojzl.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2hbbmgboa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2zfiwkpxs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2kdhumfdv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2odxoybsj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2htkekdjv.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2kkmsheym.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2ubeedeqb.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gt2zmucxqml.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2hoaihioi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2dgbsikch.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2tcdrvtcj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2cspzexcz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2zyveslfi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqbgvxkj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujvuckhg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gt2druadasc.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gt2zpsfkjjr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2cucbzrvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2agfqnpkq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiywwht.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2vglzdten.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2jhasrpdv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2woocgxva.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2wyklmwmt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2xdstnbqb.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2zfweczag.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2nohvitgt.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2miffyhhh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2olxzbtxk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2bpqqnwck.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2lgbgsncw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gt2hhhzovnl.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jauqhrvi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2cimcnjkb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gt2wdtacnwi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2awqzvqss.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2rzrdfyey.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2jfedvxjf.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2qqbmugdl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyxilyrh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2popsqjjf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ufqfdcgp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2yffntyut.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2olqjblpf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2hfavqgem.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2qrnxjtab.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2kssqiija.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ktdnflag.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2rjcqhknj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2trkonjin.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ipyhyxkp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bflceooj.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2uyappwfd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gt2ymavkvag.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gt2xtbiftba.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqrkdser.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2vmpqbvzt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znzmlofh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gt2pdufordx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2tjlkolet.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqyonfkk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kdgpeuyn.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gt2lvlvxyir.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fapvrrrx.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gt2oewgnpme.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2lwwifoak.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2zvesyjob.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2wpocwfdu.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ehjeguaa.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2winmecpq.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gt2jkkgvfmb.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gt2wifpuyps.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2boazngpo.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2vesorbea.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2tpihxvvq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wytswult.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2imasspns.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qwortmya.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shnnrtqv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gt2corrzghl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gt2trvnrjzk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ejxddnbv.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkecrhsl.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2qflqjvfl.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2gcbhpzdl.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2wbavcfbz.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2pwlyvvxf.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gt2kwovtzwd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2slzmhteq.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2thhuehcf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2mhlvlddv.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2esbrgosk.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2mcghlmcp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2gmvakxuh.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2nbdopidz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2akcyanuk.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyvjkiid.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2fyegpgel.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2iivbqqmr.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oldhtyku.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gt2utfoxfgd.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2krzcdgem.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2vjwghusd.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhjoljra.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2wlrdtofz.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xorvjogp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcblbvaw.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gt2vxfukbmo.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2ifogqcwf.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpjkvjvf.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2rqpywvye.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2lwgtetgj.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2vhswgkmt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2mfyjpnef.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2zfiplwfd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gt2xyrjiwos.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gt2wveywmba.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2pecmuiqo.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2xwzhytmd.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2mwlyhtot.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gt2whixcyff.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2dthdthig.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2klrdcjsw.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2dyjhgult.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2bevcqsav.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trlgbzvp.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gt2spglmlai.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gt2sdzsfuat.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2gwchxbgk.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2sxavahah.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2wcvqhlcf.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gt2rvwbwdbq.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gt2aesfbfpr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2pqsdzpik.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2ezakhvps.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2mcmfpbgx.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2tyefhgyf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2cdohyzqc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gt2axsibkcs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2tffisnqf.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gt2sdwkgujv.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcmfydxi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewtltcja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gt2opsmssrz.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pzrnvgpg.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gt2rjvyykss.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gt2tmkehmfq.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2waponizc.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gt2otcdzvrg.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2ujtsljna.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhpvdmet.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpkyyoym.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2rmmtylqi.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2voqstbnb.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buolafoj.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2mwinmzhz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2sgzxfgzu.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ghmjiemb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wibmphgv.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uryutymr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2flsijzhe.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2odswgrjc.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2ddcjijti.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2fjkykgqn.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2clfzovtu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jplxabmm.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2wodogpjk.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2viahdpcg.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2dqlbywqb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2otbgjpap.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2leinxivn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2rhitntir.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2tzzrismm.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmdazmjw.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2wftxhjys.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2ennbtgem.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2kojxygsx.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2hlvzrvvi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gt2dsjchjqw.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2jwwwvolb.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpfovkik.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncjsygze.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2slizszdp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gt2hspsfcqh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2mosnsqtm.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gt2sfflzzyr.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lgeavwta.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gt2bgxmhosj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2xdxyhdyu.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gt2pmbfggne.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2rnlskhnh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2dgawqwsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rizfomhi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgizfzxb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2ovivbhkd.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2qqlanejc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gt2ukmncxng.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gt2wkuyklho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufpjtlwk.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2ejlxfwtj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2sxpcrgux.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aikfmmxx.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2nizmflfi.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2mqifsssw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gt2xgkcibyw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gt2dwxxqitb.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2ruwmlwso.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2hqkpqlgg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ixhfoanc.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2dyehxwii.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hywmvson.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnrxjeip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gt2vlzpbwef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gt2iovezmht.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clyztmon.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2gitcuhsd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzxpewec.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2vtgomudc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gt2ugpwnzjk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2xcpklwyn.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gt2wbquaeou.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2ippyokmg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2mflokscp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2xhbkicup.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2rrcekqoy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2zcritbqk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gt2mcyjluhi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2jfirphdj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2clqnnhuj.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gt2fdkkokxd.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2mvrnfuzp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2canuyryq.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2yukhskvn.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2cibmoszo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2naelceez.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gt2qpovjibb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gt2jnrfoupn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2mcznnfqg.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2aoncteca.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2xtcctqbe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2inketwjr.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2bzmnpjxm.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2hjjttyat.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2lebpxgrg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gt2vfopeuqz.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eeioeiwr.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2sxbptkel.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2ugswuerv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdnxshn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogjenfxr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ybovskol.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gt2alyhbror.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2cbvqogcn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vctwbykq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gt2mnmqhelq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gt2mcuwvuse.html

[H06] 可选值 / 空值安全访问
来源：http://dali.haohaochexian.top/Article/details/gt2rtzhfpws.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gt2pldvnurf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2lvuxztcj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2utrjflee.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2cmgoaybz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2ogntujxa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2umhhywks.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2kelqlnyk.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2mempuhaa.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gt2jzgjhytb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2rtjnocyg.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2nabljcxq.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2otjygwpi.html


<!-- 参考信息 -->