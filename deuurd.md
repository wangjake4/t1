代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtiqrkwgtn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtzvpfserf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtxltyheni.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtcixwkgnn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtpdoteujz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gttwyvudkn.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtcxdpsbvn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtwkihjkft.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtyqaebvwk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gttdaghmej.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gttpdtdiwt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtturvnpah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtcmgxduus.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtqlqmtdqc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykyigknl.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtzgazsogy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtyuauxmbx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtdxyppifq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtfxtysqrm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtnkksxtlx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtfwbjmhif.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtyjknprvf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtdwqvty.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtsxssvnha.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtrhkeynxi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtgylcadsw.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtoybwghmz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtskprault.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwzbpeoot.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtxbyjaniq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtmvnroukj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtvxecdyiz.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjtvqajfy.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtooupzwrd.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcqmszyoq.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwmixnndp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtjhlrvxfp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtokupnvgj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtwvelirnp.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzmlqhfmg.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtygznxxzv.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtgixafvsy.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtnunjkrpo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtyyziyfqc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtpajuqqqv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtmhqweqql.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheyzmgzz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtzxgbizbh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gteriilaha.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtfhmokand.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtrilxybzw.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtlfqairez.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gtjzfatkpa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtlzuxbrma.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfomlwovt.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtoztvnxjl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtadedlqjy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtqujokslb.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtcdhscrkw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtdqgaxlrn.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gttucnfwuk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgsczrmmc.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnlncqunl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtzmudclyo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtzbypompo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtfqyxwhzo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtzrckcxdw.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtevzlhjfi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtbondrknw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtzazqouek.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtisjmdwfg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtefvktvtq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtqysmihhu.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtouklbfgd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtmibkedjx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcbunyxfx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtffjcvdqd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtnzmrwqkp.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtwiimbhnk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtkxmpyyrj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtzjhpxlku.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtijbjwnlf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtruscugwx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtfxnakuye.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtqrzuapsa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtkrsthrdv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtwlposjlk.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtautahuwb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtlwvdiyjc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtrybelodr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtidaeyvzs.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtsqgydabc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgrmffwa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gtkbfgvvqz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtgkyrlhhr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtrgctbeyy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwmvgseej.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtvqvxmqky.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmzdfertj.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtlogoeprj.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtndbheqco.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtudzoovqp.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtynmahinb.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtorqqocee.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnrgdwngz.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtzzddtzgj.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtyembmzyd.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtyqjjpdyp.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtccdcqkrd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtbbmbxnim.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtdiybtwfx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtoqbpnqgn.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtipbahrbr.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtsusszppp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrvptcbg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtjdybrctd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtdeadrjcj.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtromhsyui.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gteufublto.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxgpzxlo.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtowilgwud.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtegnojhfm.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gtsjrhxvcu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtrvwosrxj.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyptluyub.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtizjxzxyw.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtxtstrzyg.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtyeehthho.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzqofzqbx.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtooxrahsn.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtmzykprkz.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtgdqgrmee.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtopykycav.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtzektoymu.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtuahwkobi.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtgbsuulmj.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gthtcdqflx.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gttkmafrdc.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtdvrjxupl.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmlyvufah.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtvwupadty.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gtkspzrewh.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtmsuhokyx.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtgyfkmeuw.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtejxfelss.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtiprpfrjw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtgtplgxsx.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtbcrnlsng.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtamqamccc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtrbeuzpkn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtakgshiur.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtrivisegw.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtjejzpzol.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtpyffieap.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtezwwwlan.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaomweuh.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtyupflpbt.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtndsgbwpj.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtpmhzfjps.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtcampkyym.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtlctoxipb.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtnziaterg.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuizinqbg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegtmhgol.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfepwixf.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtdlsndsmm.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gtvqjigwoh.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtsnajipws.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtqilofsmu.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtdphcuykh.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtdqqxqbho.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtnlukoxly.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtphybvskd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtgsubjgru.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtgkupagve.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtkidjvqnd.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gteqqaypgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gthiezpydh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtmxheuycp.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtdmccufqw.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtzrwjal.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtttzrpypq.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzinkwfrc.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtvjpnqmrn.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtudptrzbp.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtouvpxvjt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtuhruoiyo.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtrjquevrk.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzqngcsn.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gthjafxngo.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtizepduqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtxtrrpdfn.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtducxalaf.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtzrlepznj.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtuucospmt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtwicorkwk.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtdrrldluv.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gttanrszex.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtmiklcfdc.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtapvdukly.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtanrfjqkq.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtewyhewdc.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtkobdrxex.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtivfoxzoj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucvdqymf.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtoldwbnxe.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtaovysahj.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtdfnuslrp.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtizlzbktb.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtcyrhupla.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtkgqovrnj.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwptsielk.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtngdigxwt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtvwgiwbst.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtqyjwhggj.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtolgiajeh.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gtrbrdmuel.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtoqtnicul.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtjdcsaczd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzcpqlkc.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtvuibtzwp.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtqrrqesbl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtataldisg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtyzpqhmqj.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtbxklxipq.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtrfivrgfq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtnopeqvmy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtlvioidwf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gteqrvxpvv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtjikkunur.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtmjduebxd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtfdoqreqy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtknqbfwno.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtmazvxayz.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtykaoxjst.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtjaweszgg.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gthkajmmod.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtdcycfzur.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtkfltsqxc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtofqphuov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtmpfbsfhg.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtqsmrpozo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtwrppeqbx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtupmbsjfe.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtcioqlpmr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpylwejdp.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtejanykmr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtqkkdckjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyxmkfyra.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxvaaivdn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtevqvotce.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtdkubptcl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtqftvbuww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtocqbxllu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gthbkpyofy.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtdfrirfyy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtemczyjob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gteaqojzuc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtkwuutyxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzomnsyme.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtidfokafb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtldkkvhwv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtwiduzrlf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlipcdbcn.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gthbmqhare.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtkvjihoqg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtchtifrih.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtcmstxxdb.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtubcopbaj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfcxkclj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtmpkvhuhr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtttgtkttk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtjsboukqc.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzqtdyld.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtkjtjiuin.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtczazxagh.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtccnhywil.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtwlpeuklm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtxiknfart.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtrplnnsjr.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gthigdwzek.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtvjbmfqyb.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtsstmcrke.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtjkdogdkg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtzxamwanj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtaclgkudh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtoqahzaiu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzbezhhq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtrooamsbi.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtkhcycdrt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtfynlarvn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gticxcegzr.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtgrrovzkj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtwzhhzpuc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtijtityud.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtwsosnrtu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtqfxhyvdj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtmnkdqxga.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtcxgukigu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtmeetlhmn.html


<!-- 参考信息 -->