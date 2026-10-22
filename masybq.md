代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ekvjduco.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmhmksrf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2qeotvynh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gt2crmdnzyu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gt2xllmuxza.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2qrkuoutn.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2wchcrgtk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdsjpsed.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2gehporss.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2zsujnrof.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2iqdlvpfz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2dcsbspib.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2xqwddnww.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2kgfvtuqm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2xruftokn.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gt2pmiojhtb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2altpscgs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gt2jkfhsqsy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2fhgfteqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2tcpzvcqr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gt2drtobvab.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2cuxogqlw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gt2vcrmuztn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gt2bvgcrugr.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gt2rvhtxglk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gt2hhvyqxaf.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2eumummbb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2yiazuxdo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2xvarmscf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2kjjzodzw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2dyiafttk.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ejatihfv.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2mgonvxsd.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gt2yfnwjkkk.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2rtdhlzha.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2izlihcsl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2jypfnsst.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2tjhizewm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2fqtlrnpo.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlzrzkly.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2adotwevw.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2qxcfjmdn.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gt2wqrhusea.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2nbdpprep.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gt2xqbjgbst.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2lfxjtgzf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2dyjhzphn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evpwyzgz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2haxjocso.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gt2ulpkffuh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2tcxeqrgx.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2xedjorty.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lezxaqda.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gt2fcdcsgks.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2zrsnjgma.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2lcadxpcf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nygpnxsb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2srsfnbqn.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2ntwhswbf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2lunkzslw.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gt2nepcofsd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ztseyrbl.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2hutugdud.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2ryuhvswa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2oefxfdnj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2qrkccmah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2avbfuatp.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ovdgpjzm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gt2oytkxamz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2ovybzxef.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xcgphojj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxlnszgs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qygchpre.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2mdnacacz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gt2psoghvaz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pmprdwgo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2wljjzkki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2nnypvmri.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2pcmglcrt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2kodmasdv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2elfxgicz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2icsoaroi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ofzhpqlj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2qmtzldrv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gt2nubcqvdq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2kjfpragr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2bvocxlxr.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gt2pybpsjzs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2unzobizp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtxsramu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gt2wpckgtbz.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibcrmkux.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gt2xxxkgfyu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2dkqxkwky.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyvxkxum.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gt2raiylrez.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2pzvklnss.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gt2qcgqrxya.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2xooumhim.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gt2noymazoj.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2lbzajmsl.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2elfyjyva.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2upjkulqc.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gt2jyufcokc.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gt2jncdoxlg.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gt2axnkyhfh.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2hjosuwgw.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2kthuofjq.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2ubcihuom.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npvjenih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2azlgjhxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2byztrcfb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ssqwuvae.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2kbzhfevz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2rvxiajnp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2bekfsvro.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2udwjcgzf.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gt2jxlbqyjj.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2fynqvafj.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2txatoyea.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2tvyusuqu.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2idjyiyqg.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2hoefzxyr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gt2tyvcniew.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2zvsrnnoz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2ewlkxsqc.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gt2avipdbhu.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2clqgaxwl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtrxykua.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fljpodgu.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2hwvfqnzs.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2xwzeidwz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymfbfzil.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2npfhrbmm.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2kbnnuuxe.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2brdkoave.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2jbuqamrc.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2uqdtbwmf.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2ppcbcxjz.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2rgmnfvey.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2ndncbmrw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2avxwcoql.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gt2jcssnyem.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ouerkcoe.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2dsxzvusj.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gt2pcvzhbwl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2hrubeeqz.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2lzvysafj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kijkmcgl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ioxnfigo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2sbiiwlya.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gt2fmltncws.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2ccofdapp.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gt2xbgihkjc.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2hzdeukuj.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlgxmjqz.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2zcunjyle.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2uyvobnmc.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2sbqedorf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2dmlwgfub.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gt2rjdqmdxn.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gt2gowcsksb.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gt2hjrfczmn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2puimpbav.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2gbdywqcg.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2bklpgpnm.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2lxswpupt.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2xmbbktej.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gt2icqfecir.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gt2kudkyqoj.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfuporyr.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2hepepgjw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gt2uaakhylk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gt2wuivchxb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2bjnfugxz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gt2ygccwzmu.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2lpvtmvhf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gt2gsfktwco.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gt2goovjnew.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzhshbac.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gt2qgiurtse.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2hajzpued.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pngcnmxp.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2zrmiwcfi.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2wxlkplcp.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzjgmldp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2sbmupuxx.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2vcvkwfnz.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gt2kxybwibl.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2jybjbakd.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2iihyspgq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eseudoci.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrhvlzdy.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhncpufu.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2gvknlfhw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2etkpxqbe.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2bymikpse.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2payldrln.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2nxtihrrf.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2yxzfcjrm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2eloyeryd.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2lmjpdtid.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2vqbokrln.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2bxqzlatp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2dzycmqut.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2klkqgfuu.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gt2kmvxipcn.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2kzhgsfxp.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gt2kornxegl.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2jjfgmsfi.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2iphgbklf.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2cwdbavbi.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2ouvpvbvu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2hmgdepvi.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2qinhegbt.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2dsqinpln.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2oiciwhbs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gt2nmewmkmh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gt2oflbjbkt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gt2ryvvwtzb.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2neartxmn.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gt2xsqfqkgn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2orbqcahf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2cefsptji.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gt2jsknqyzm.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gt2racoygfa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2jgjahnmc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2qrabmsxq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2glymcrqr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2pkljkgsz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2mkotcpse.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2tdquhssm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2ryyvccqw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2jgiomyls.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gt2qhbuesox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gt2onuhjaec.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfjhohqz.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2qzudxrxe.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2sgsvgael.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2renupaju.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2tkhzedqo.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gt2bxdllrcq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2bokhctnw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2csfibvcl.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2qgcanejn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gylmfknq.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2aiptetkx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cktsjdla.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2pljocktr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2psoiorrp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2mvvnjwbv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2vqixsdrv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2ajtallpt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2winsdmvw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfdxblcn.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdjrvvse.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gt2pqlvfqen.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ynehvgad.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2qgqbvkzy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2cmogjqwn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2wcyiptkc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gt2ftuphntn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iobwqcpm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2ljojjjvl.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2byjnmrsp.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gt2nainpcnj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2xhkdnmmn.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2ysyltbhx.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2bfdgzelp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2qzgblrvi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gt2bofrstpt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gt2veouvaxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2xrxwkwnb.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gt2byenforv.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gt2nevxcwbf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2uyiocwaj.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2sgrsrqsr.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpnijwqa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfdhwaqe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gt2kxwokrxn.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gt2aftozauu.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gt2xmgdocle.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gt2tudunxtw.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gt2ujhxyebq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gt2qkuxjliq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2csoguaff.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jprwflnk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2weuyqref.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2fxamords.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2hplgmgtl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2ilsbyhpd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2svcuwius.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojirifre.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2gmqcovrd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2xztygjzp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2atwuezqv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gt2ouxawlah.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gt2yfbkgpty.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izbvmxuw.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gt2yhncczsu.html


<!-- 参考信息 -->