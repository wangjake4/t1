代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2udkrthzr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2gzgfsigk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gt2iecneerl.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2keoxxkyk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2nugucmni.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gt2hozfvidr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gt2fbpshbuv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gt2lfabketr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gt2feuzswkf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcyrkvuy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2pqfbftxf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gt2mawovfxc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2oswhrybx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2dzlaacgx.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2grwlyayo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gt2rskvswnk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2zbxftqoj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2mylcverf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2vtwflrtn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2dvthvbcm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2auwrriwx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gt2ztkkrikx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2nstppxeh.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ddmfsghh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2nvdricij.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2fbjxomix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2gbwxmplj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2prmrxnjq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghhxgugc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2biqgydmo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gt2lvxumefn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gt2eomopurd.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2lrmvdvbt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gt2sumiogeh.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2dlgkmxsl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2uikinzld.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2sgsolfbe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2moqdtyyn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svetffxo.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2uwfaeflb.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2efvxkenu.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbuiwcix.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2zuooesnu.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2zghurzgf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2udrvhghg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2zfqdklxw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2nczjbona.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2jatdoqci.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqhzilhi.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2qrruzjpq.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gt2iesjzedt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2yxkbfisg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gt2slgfajpy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2wugzvmsm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2pblfmmpn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gt2pfbmpazg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2cehqfmow.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2voidztqw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gt2przqghxn.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gt2fqxcmhyj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gt2snhmhnug.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2mxxypsmg.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2rigargnz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2zkugndoo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2attcuknm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2euatpiwe.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2ozriuzyx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2utsxdrgn.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2lyjsgkme.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ttrzvxsd.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2vtvhrsgn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2orcnmftv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2faygzdhh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2ndwuqcmd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gt2vlpndmwy.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2dqwjyqyd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gt2kbgsujud.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gt2ltvflcrn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ddknkqje.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2tcqeqmwz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpesnfzh.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2bsgpmzkx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gt2apmpabjh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2tqxwcepc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2jhhbtedp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2nvxiefmy.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2gcahrate.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2hkwrjzko.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2acagxwbg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jemmfjsk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2wilcryqt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gt2ehzxwxuj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2ejzudwgn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2rdixnlzz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2usznhmrd.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gt2kaijncfy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2hvmywoyk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2tcdubpef.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2btlmwqao.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gt2yzzabkre.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvvfqoil.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewlaqvty.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2bbhngzwp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2buwoikam.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ghbtjypq.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gt2rejowxkz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nbkljgzh.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gt2cmxdjpdf.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2tfqapvyc.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2zvrwuqwa.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2yvaseuux.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gt2duvuoqfv.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gt2breebqnr.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gt2ulubzcfh.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2aspdhbmt.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2oixltpyd.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gt2jazujcov.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gt2igbxohci.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2aoljkgab.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2jmdyfzpn.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2cndkhsmg.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2wzjwoxdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gt2jochliyo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ydufkuwf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2pyvhbwyw.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feezmexo.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2zznmqfeq.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2vgjmkmiy.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2shhmapub.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2qdovbwai.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gt2eqgqrtkj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2neajqiof.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2iehdtfxh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2vxqepmnz.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gt2rlhdkizm.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmrfgicn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2fdrrloxb.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2wdcvrzah.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2arrahegu.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2wfufyuha.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2lmwsjfxb.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2fowmtbmo.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gt2kfioutnw.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2dejdpfmb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ekicxkob.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2tuzlmzis.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wwfmamgn.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2pmqanugv.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2dyscyclu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gt2tgodbeum.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gt2dxlkoycf.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2etoagnrt.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gt2cxgmknib.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gt2nkgvluon.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2zvyimpas.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2kttokejo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2ciikcamb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2pfkchtqm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2noaulrox.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gt2ilovjowz.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gt2hmetyivn.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2katvwwmd.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2mdedqirb.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2vczcntab.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2rvkfpxjk.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2dvocwkwu.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2rrtespfk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gt2hobgbyni.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gt2arihuxkx.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gt2evlxbvqf.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gt2dbdcscpe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2mpswuint.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjekodok.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2klshuyob.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gt2rzoypabf.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2priuasiw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2dxyjbbui.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ttyslthv.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucxebtzw.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gt2pjnmrjtq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2gdmbntmz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2nyavwnjx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnkptdbv.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2joshyxak.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gt2qbafucfx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2nkfmgply.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2vwyilpof.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gt2llvnxqoc.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2lsqvkqaz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2bgoxewcz.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2ibunrrez.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gt2nlnqgxje.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2hqezwrfh.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2skibrbwq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gt2tejxuetf.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2tibuxwpy.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gt2efqnyqjv.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gt2joaeasur.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gt2fndrmbkr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2hsciuuue.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hkuyncdq.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2huwtkuck.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2sbicfxpm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2lanpbxie.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gt2dcqamfqr.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kotrbncj.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2vmazusqn.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2cgokjbxs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2kskkriqv.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2ntwtrwwp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2rbvnyhvo.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2rbebjnfp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2symauplx.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gt2gmddoiqa.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2wgtcnxrb.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2diwgwuiw.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2knnvadyi.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mujmpdwt.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2rmfehuow.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boyecaof.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2npzihjzq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukkorkfm.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2dyfclxeo.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2rurqkafe.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gt2erkilaib.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gt2xaetdcmb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gt2ozzsrozu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gt2dfxygjgh.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2bzhagapm.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2cuzccirr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yanxogfx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2ekfkuvkb.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2pvnkjzim.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gt2hregueod.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2cgcmalxa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2uiilirdt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gt2xfuckisw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2llzpmgsq.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gt2hiaexptz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2lgtezihg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2suvmrfes.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2thdprudq.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2ernntlvn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gt2dfggdmef.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gt2rlluxfqx.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2tzniiojl.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2zbgfqirq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2aidhfvkd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gt2krxbowdx.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gt2cmkqgluw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2wudpqbyq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zdwumwzp.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fylaumpr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2iqbngepb.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gt2cocbwqkc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2rmzqmbmg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gt2ktxkhrbw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2mgpzqcpl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2opcqgcxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szmufcnz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gt2izfccovk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2ggpbqbuf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2vctyehjw.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gt2btzicyuw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gaaeydvl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2soalkork.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2oekjjfwk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idqjaave.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2alrkujzc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gt2cysgekrz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gt2bsthtjbo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2bvtjased.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2mufdrvel.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vaurvpcn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2rvlupalc.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2ljungyiv.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2qxzraont.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2tislqnqz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gt2ujemhwjl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2oclxegtc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvwqofjt.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2yggorrfk.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gt2kdjlxuzg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2kaqqhvgo.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2ajedzefj.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2sqyrfllq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2auhopjhl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2uopsjczq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeshvlfy.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbsfdrzr.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2dgwbbvtx.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2rzxnzmqq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ppcrlriw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2luzhokqk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2qaifcboi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2dxyfujde.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gt2gccgnzzn.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gt2bqrvkycn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2kncstpce.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gt2qtqloytf.html


<!-- 参考信息 -->