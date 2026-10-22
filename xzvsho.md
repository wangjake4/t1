代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2sqgsdhlo.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gt2hrbfvqcf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2xryroaos.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gt2ohqcdmbs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2olzzwhpc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2frytkcyx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2dfywtknz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuxkmapf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fctlsqjo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gt2givjwbll.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2wmkncnem.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gt2vkbmvnai.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2qwygkdpv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmawfxkk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2bjdhbegw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2ddcxryfk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gt2cqnzscxr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2plucijhb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2dppwcvqr.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gt2clgovaia.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2mnwehfky.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gt2cvirpyrp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2jdbalsvi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2nrbqrjtl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2wrhqzweh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2tbdoupcr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gt2euigulkr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gt2raqerwgc.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2pzqfokhj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2kdmraclu.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulihhkmj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2sxratpku.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2biasccyg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2wttwrhnq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gt2wjzvupkb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccgdiikf.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ljmcawtm.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gt2dtokbvlj.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2sylyxtgl.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eevoopyi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcvakyxt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2zeidggdg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2poyzyfbo.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2irkrlbrg.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2fcnqgoua.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2frosayah.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gt2rnspskwr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2dexrglcj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wigjggwa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2inhygmwx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gt2xvoqeazh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gt2lsdexvfc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2qzbxdrkz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcqrirgg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2qpifdfsh.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gt2jnkzjprf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gt2vvaxsxog.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2wjiunvjj.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2urabrfvt.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2favztiyz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2kcraihlk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2xcqawrnq.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2cvcryvvb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2iscktgvn.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gt2tcjhgkcn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2rnuqeidg.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmaeatzv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2offfmawf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmsnvoag.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2pjrlvvhz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gt2cxsgtfkw.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2jazatlnp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2kaeschtp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2hlxuzlwe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zoacknah.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2zugriqcu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2kvebfzmc.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2bcnskioz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoibvnph.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2znjhgldi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2tyhrjsen.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbjqckif.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzhhpacq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvwkqdmj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gt2hnfesvdc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2anrocxqi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2wevtttrt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuxaqirn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gt2frraokga.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2jknyxpob.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2kltnijrr.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2fgzobyqq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfoccgwl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnvoyqei.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gt2lbfxmvoj.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2cukuwwkn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gt2iwtprwyk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2rbeaxlpv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lusftiwl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gt2cedygveo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sbifzsak.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2xkqrzovu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qninsnuz.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxxdanne.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2niaulref.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjnukx.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2tlokeejs.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ykhdbfup.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eolwhsin.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttgulqkx.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbfpdneo.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2hcvjdtve.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2unspjqvr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2uctlrxvx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2codwctue.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dybtoboz.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fovrrrmr.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2kydftlod.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2fjrpafvl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2bakhtvyi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2gzooysfy.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2dajgzuva.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2chbmuatt.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqejbaka.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnwpfiif.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gt2iqwhacxb.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2bgazyoyn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gt2cucwgfqr.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2osyvuphv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2goibgena.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2uehnbzun.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2wqrwoekq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qatemuzi.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jmeamtjc.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2rnworfob.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2seqznklg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2tepgvrzo.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2bzvmknfv.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gt2bwbtzkfg.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gt2vqvkhvmn.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gt2ziuckkxs.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tyuunlgv.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pupjtdhx.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wpwxlhiz.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2mvylodfm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gt2uykclgbp.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gt2cwlajmwl.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2mkjlwdmh.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2zdtopjvb.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gt2nzmnlbkb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2pplicvhz.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2iaambfpt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2hkqyhfmb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2jnqnbxss.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gt2zgpuqhir.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gt2xwxrhaxe.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2aasajatj.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gt2rkhcgrtw.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2ueeejmlb.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2jxnnmqgq.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2tajjfilv.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2lwwqrjks.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2zrgfxfvz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2letrpbnq.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gt2bqiyiwih.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gt2gmjgwkcj.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2umtbfztb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gt2koettooo.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gt2tpsezeel.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gt2dhlzvsqx.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dlqhrlkt.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2krmtcrff.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gt2eyqviani.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gt2mqoncyxc.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gt2esgmvprf.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2mqdjmwuw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gt2zxspcngl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gt2ljhtzuii.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkhowdtr.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2fsnoeenl.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2cdnawpip.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2wqjdhqqw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfukuial.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofnbvyxq.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2xywgxqrg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghnapupy.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2xvyvweqm.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gt2vdqytsuo.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2yjupwbnt.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gt2leegsvfe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2tpzjpcqg.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2pqvhufkj.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2hdrfkqgu.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngvxyecu.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2rxelzvkn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2klxkwiec.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2yigxujcx.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hikqkbrq.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2scsuzswk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2oyqpzozq.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gt2vnqjpqja.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gt2tybkmyvg.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2jaryvnzg.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2pqwkaxre.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2ykwtshox.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2dhfhgpis.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2pitmtttt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fvpqvyju.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2zeomyrcu.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2oxwhrqcp.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2ovayhhov.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gt2tauhbddm.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2mcvtknpo.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2eveigtxv.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2uljurync.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2hztmctco.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2yogammaa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2ielizpxh.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2zvkvvazy.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gt2tofoazbw.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gt2dcprdvtx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2vaacxezt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gt2moenavgh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gt2dfddzjru.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2zlhhaipw.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2yyemqhnu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoyawuya.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gt2scjpocoq.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gt2bqesptgl.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2cngmzulp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2rxndgfjv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gt2nchqjktj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gt2qtpvyizk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2yafclicm.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2hxnpntpl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gt2ielqzwpv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2zeiedsjs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2dxrqmorc.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gt2ttmopjvc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2smropbzw.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2aefjnopn.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2tlfbeigu.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2acogmuwv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2eivwraee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gt2oloehuzd.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2aekglwxp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2mrnbgqzo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2czhvfzew.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2gscejtqj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2kihjosgb.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gt2gdawlypz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gt2fcjfiomt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2gtfbybnq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgavbaux.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxwyzxmd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2bkurgvkg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gt2psnysknn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2oetmabbs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gt2looxyoex.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gt2vpgfdind.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gt2rzqdcfzh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2kxepemmj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2vnejvens.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2muvkajfn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2johwsaku.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gt2ydwfuwpx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2dhvdpdwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ynjxorwr.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2whogeizd.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gt2rkydbjzm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2lghkarrh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2woaznqxi.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2kkrxhngi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2uxusjhoc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqtrvodm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gt2cihypfnm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cujqyhnb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfjvakw.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2uryqdbbt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2qyofwznj.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2sxwgtpie.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2runyhzrw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2uiajsklx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezeuyxwb.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gt2plrkwloe.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kpfdycnz.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gt2vvvzukgy.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2ilmfrbts.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2xsglwxzu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2mckqgbul.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kzynfbtu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2rgfxvukm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gt2ztnbkywe.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2wncmgkyh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gt2dsavasit.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gt2ypgwpjic.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2jiwqnebv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2fqaxjfub.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2ucxxhifm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2dzzujyml.html


<!-- 参考信息 -->