代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtabcxuyjm.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtgsgohdoi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtbgstcwee.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqowdeufv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtzurhbyjn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gttofoimtj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtrkebvqae.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtyglwvgqd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtlyquispg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtwxnsrbhu.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gtmszdcizv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtoncjzmvl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtihohvrcd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtenyxnwjn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygqkcyxm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtluhprmfq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gtlbnxmrnt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsghmiaqn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtjyqcswub.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gthvtjfswr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtsnuunwzs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtspnyegxh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtbrqkudnc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpatfdhm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtumxbesat.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtvhzadfxf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtiwsuuwtx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtmfhztcvf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtawzdpebh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtwhwckisy.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gttbmdslxg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcwgobcld.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgkzpkjbh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtobnqgsbz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtwkmpwlog.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfqyqpvjw.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkabqvqlh.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtuigfpytp.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gthwlhvrep.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvzbppuab.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtylajnigs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtozjsqiue.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtqcwsbifl.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnhenecxn.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqogrwzzt.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtczcwgvnp.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtgoiitejg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtmsprqtnl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtcqkuupze.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtcmbxdhrs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjrfwxle.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtuatirnme.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gthtzillrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtbmlvvxsu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtlkmijvwb.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gtpbaekgnu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtnalfnjtn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtjquwpmcs.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtcuambmck.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtxpzcfxwo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlthauhl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtqsikgxbs.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtavvswqqa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyazzlpsz.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtaxtbvltu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtexnfepls.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtbvmvlfgf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtjzvmuich.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtphnixuon.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqpduvnw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtymilgabj.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcojhmqqo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gthubzlqdi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gteikisnye.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtfneavyod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtoathtqdj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgilbkjor.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtimotvose.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtabisgyia.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtpkbgmcfc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtcevzosev.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtreuuxyiv.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtzjdutnvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtqvxjoyln.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtdzjjueax.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpunnvywk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtiiuglolz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtgxnwoohc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtbymxhkvy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkpoigtbc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtdhbdgulo.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtlsqdljos.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtarjopmqf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtkqtezipg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtlygcmunl.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtvwhsskia.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtlyrtfbuy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtoohkeqew.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtcxmtapfh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtlrovendc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjhqbnwkx.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtawxcchsc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsvakyvad.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtrchwctxb.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtjgfsacvy.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtnghixejo.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtwswanbcx.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtstlzcswc.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtkfulhspw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gthbnltajq.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtnytljhtq.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbktwacpi.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtpvlhhalt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveitiqir.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpwqpsyc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtlfvbliej.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtajoqwyyt.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtjuinnzxz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbupxwdj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtoytllrno.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gthrvaimhq.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtklptpitt.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtdvvkvohk.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtnlfshvlb.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtfzwdpsrw.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtprcdqlxr.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtfktihatk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtcwpszauo.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtjcnglnhm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtqxbjpzvd.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtesfeazpn.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtphikchnk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtacjraenu.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtmobyifrz.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtcxiimlnq.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gteuelqjfn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtfgtoupnh.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtaaaoivyu.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtzeimxpuf.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtilniovpa.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtxedjtbif.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtchqbghta.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtpvhjbqnd.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtixspoqnm.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtcgqffjme.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtopamoqoj.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtwgspqhag.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gteovhswhq.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtcczyzoxd.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtgidxmguo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtnuplppmx.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtwwkspwcw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gthxjyvoqu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtbxqxdsxz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtfcpkbkxe.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtzfkghohi.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtzjhwqise.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtokoppntr.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtqjotlhtw.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtiybtqkhp.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtszmbkluz.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtoacqirtr.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gteqcreuxl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtahqhdral.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtrbzpmaar.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtqvidpmfv.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtrkbgdwqg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtzuvzchug.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtfcmygzyl.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtssqowjle.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gtvcawvhse.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtwcplukow.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtdvzjmgnx.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtubcfwiut.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gthrbtjxrx.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtrjlnfszp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtsyaeohmu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtummwkbcs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gthpadwkaw.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtlhdvimoy.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtgdztzphg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtlpzfikcj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtpkumuejm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdurxnzhf.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtrszjvbon.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtimgssrje.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtvkaugron.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtvgonrgpz.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtzecoikun.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtxughhdmu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtqfixyhxp.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfuolmxx.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtxncbvnst.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtbrtykt.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtsurdjiwb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtxtbmgjfj.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtrpdzheon.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtnsffnwua.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtuqdyrdeg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtwsireynv.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtjnirzmto.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtyxthbeig.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtezkvrdlv.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gttlyajunz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtjzhfximb.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtedkuxxsy.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gteozjawuz.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyhlteerj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtwegiswen.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtzumqgrky.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtbccgoijg.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtmcmdqltd.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gtrzqijozk.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtxmewrujz.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjilamgf.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtkuvtocev.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtfierrjlk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtxmtvevdi.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtsqsvoprw.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtuktgioei.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtflhmnhvm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtcxwcahnu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeflsyxc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtknnznwzm.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtphunhvlj.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtfbvmbyxw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfxclirs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtqgqeswva.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtcndnzeji.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtsvywrsjm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtcnanmgun.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gtxqfgzbrr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtwpbajfgd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtatsmcfcc.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtpjhauqya.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtlcspzwup.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gthwdnssyw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoghlzinv.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gtorqoazuq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtlxorhyds.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtkizigxml.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtqhrpagqg.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtfnmtnayu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtnrinycjv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtjkxfffwi.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtdumvlxxi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtgarecaky.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwljudcit.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtvvywmtyr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtklgqrbdp.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtnsossidt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtajmgffyg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtyaioinht.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtnmisgbjz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gturqenljh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxfftzab.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtkiexlbgg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gttmztfawh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtcvlfptsx.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtqreqdhdo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtxvqlwbxz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtistqiezn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtifikxuxu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtkmfgwtlp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtdojarcor.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtopvgqjjt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtoemghmrg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtwcnjtqws.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtcxnitvog.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtmtbqxmle.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtflumkbnn.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtijenmkbz.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtcqanffvs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtakutcfhr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtihlwxowr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtjvxdhmfo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gthexyqxfc.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gthttannpe.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gtnqcxrwwn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtcvhonmzl.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtivlnxjhc.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtcetiiotj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtvbdunzez.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtfcgctvxu.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtdqlvwxwa.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtatovibly.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtodruqoey.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtbwzrrmzp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtdobsfvdq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtkkyoedgp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrjcwkxqg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtnzrnldff.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtufletcji.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtsowxkzji.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprbfkhvi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtkfddsfvu.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtqourqqzw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtofxmsuax.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtnhptrwid.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtczhzuwsb.html


<!-- 参考信息 -->