代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cqqzagep.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2degyfdoa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2rukhnfnq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2xbzpbfej.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gt2ahbgsmho.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2ymnrpzsc.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gt2weuuaywa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2ajrrcdqf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2tqptyxmw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2jeqkohvm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2ezpfvnrw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gt2zqtkgsbe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gt2ciafeouz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2yjttrzwa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2aqrjrkve.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gt2fefaipsu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2yenxtvdy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gt2omhcbzaw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnzgtdzb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2qfrdekbm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skbexgga.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2spywxkth.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gt2wueowmwl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gt2upyhmpsi.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gt2abbsrtmv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2mvyrsyfv.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2bceedbod.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2iebpiulu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2bozgmvdn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2utqkofsw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gt2uwhnkswt.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2vlicqlck.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zphsvaty.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhlefkpc.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2znfakqkd.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2mszxlzcf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2xdexwyrf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2laasbngd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfwgship.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2uogzvcim.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2dqvisdkq.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2clajyiuk.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gt2spijxjuf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2ityclklc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gt2vkstgroo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2dtdxeavn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2ciulslty.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2rxbnyzyw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gt2ltydzxvl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2jkkskeoi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2hjeykwgr.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gt2pttgwggu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gt2uelelkqf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gt2mcqoczul.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2etprhdww.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2tompzhch.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2eoftjphq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2sioggfeb.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2bamfgeqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcprrjlx.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajmiuclc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2efuteugj.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2oqyforpu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2nwnfpcsy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2ugfmsman.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2ewxxwyjc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2yndkejhv.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2mhhdtulz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2attgmdsw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2nmzhesdv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2hskegaxm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2wdqnvyhh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2bbtatalz.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2nxleaddd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gt2bighnbge.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2lzvrksmm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2lcpgwnaj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2punadmdj.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwucfbji.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2nifjdyrg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gt2yajknpoa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2jdhlecxq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2gdkotneu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkxbhnnj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjjxjrth.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2pkxjxueq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gt2cmjdtjso.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2coileyez.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gt2oxrgkxui.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gt2egayuqoc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gt2iwhmtata.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2nemgbnbm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxdxawua.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gt2iyzszdwd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gt2aasgoomt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2xsjcyxwo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngbpmcdi.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2qexzlhbc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ckozzgds.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2jjyrespj.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gt2enzhoefi.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gt2faofyyqc.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2wejpqnws.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2ojgkcvur.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2wtesxexq.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gt2qzxyaywb.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gt2ixzuynjg.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2mtcdaufz.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gt2ymstfbwy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gt2etdhrdoj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gt2qjjqktuv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2woibxjfa.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ophqjpej.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2kkqbkvqy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gt2kecbtqfe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2kaaultoo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2clgvmgkw.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2mfwyhkmg.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2smxekkvi.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2hjazaipp.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2slstqktx.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gt2jrlcqcle.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gt2mrdrktpy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2mphorofh.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2wzddlsvq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gt2apprnwmf.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gt2rkxjbqoc.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2kldukklc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2vjiqhiee.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tducfhla.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2kwsvwref.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2cxxpaymc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2sopnowzc.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2zjwwvhkk.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2htticjuy.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2dfzutopp.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2kylodtyl.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2grfrhpgk.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2flerlayw.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2hdrglgha.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ryupqljt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2xkjwargj.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gt2omidmrrm.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2wvmczylz.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gt2kozufypi.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2xszfyjtt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2zmbxrvxw.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2tycogjie.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2niwaoaau.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2fyguaeou.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2lztxybnq.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2otcgmplc.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2smubnmpc.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gt2wsvssljm.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2fvddbsni.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynbgsvou.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2irmdevpp.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2uyseselu.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2nitvmmad.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gt2jbefptho.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gt2kzpybqiz.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2eggskobo.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gt2zvzzhrwt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gt2kpxagmnv.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2mkkwkxiz.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gt2qtmgenwb.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xxxwwxml.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2qhtzmnjj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkbkzeia.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gt2stmvpyio.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqjadizw.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gt2pepepnzr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gt2hfredusc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2ougtmjwv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2hijluqlw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2vsyvnnel.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2seiwufqt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gt2bouyalow.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmndygaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gt2mbcpgmgp.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2bogjfark.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gt2plrwzimk.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2omugdxeb.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhrgwxpm.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2ujtytamx.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gt2ufpnldnv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gt2psxeksrc.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjnaniwx.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gt2nwgccqvm.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2parxuype.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2znyovexe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2hrxrjrdl.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2dtmruehc.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2shqhbkhq.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2yneymcfl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2yzkaarmo.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2srobvlzv.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gt2rojelxnk.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gt2vhdqlvwa.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2evvstssm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrwhctkv.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2agfniopd.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2cfeizwgb.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2sdfjmvfd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgbevkvj.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2auruqvib.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2ejytjjxy.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2ouckjhqm.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gt2psjsoqpf.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2ordayudo.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqvqmulf.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oivpyciv.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2uiwoqhsi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2agsmjjkq.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gt2aviivqwn.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gt2xnrkrtuk.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxkwxlbu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gt2peevswxh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2roaurlip.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2ofcxmone.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gt2pdlhlgum.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2stexgiou.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2lsyuogtb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2xiwdmdiz.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2egpteeea.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2warhnjns.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2rvxjehwc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzdwnedf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2ajblledl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2hpbqzlry.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2psuotxhb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2pdfmqday.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2uaesdxms.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2alxlyaoz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmortxt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2fnjttwge.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2cqhyazdt.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ieumeuzo.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ksrbavsb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gt2wnmnhiek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2amfcalgy.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gt2iwluyatp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2mymmnqrh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlhhheuz.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gt2ezzuxojo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cqovnpqp.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idxsbivl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gt2ixqrgxgl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gt2yfmixjhy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2ujnhkgug.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2enlswlcg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gt2rstdjrre.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gt2ruelnnfq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gt2cplhsjnu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gt2lwctozmw.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gt2ijajggxy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxkrqarh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2rcewdtow.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2cejfbenp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2svewgmwn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2iamkqxli.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gt2ptwiwlsn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2lxoodwin.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2uujwgzus.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gt2xizixita.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gt2phvuowng.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2snteewte.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2sfgejfwy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsegltbl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2pmjbsoxr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gt2amaktnuj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gt2nwuqowfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2wchhgukh.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gt2pychyzsg.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2hfcnxhyl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jqsqhtud.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qpdycgmv.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqlmfdoj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2awrtunjv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2ekxekajg.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2jzxqgqks.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2edngaprl.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gt2vmyqbmgg.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2esmjhntf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2gxicxatp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2dgsuncon.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2kwggexud.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gt2qghbfjpv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmbdwugt.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gt2itjyvkcc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2fhlfeall.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gt2ddaxkxcv.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2wigosexj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2twfvatcm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2ymxrtijl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2snfujdbj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2ubbwnbeb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuklqdkt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2zsxfqjap.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2ksfkkvck.html


<!-- 参考信息 -->