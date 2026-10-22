代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2yendejhc.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2bnlzerfg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2baoihexl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2rboafxrn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2owahnfsh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euceqzfs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2hklsuzdv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gt2oawlufbs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gt2umfzgfsm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2fpimopcf.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fshpccot.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gt2isufoiqb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2fmxuoqzh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2ppnkttdw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2cquslawl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2ivyrznae.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2izkglzkw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2qljpvtkl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2ztkbqgkp.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2jxnxqkbr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2dmpqabmf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gt2hgpciqsh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2mjtlwzzf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2vofdtvgk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gt2nbqgdxsk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2qzuifhly.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2tqpyttez.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gt2zcckuiqd.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2tekzdtnx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2lcplduni.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2palwfihi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsfdrxba.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2jesevlqs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2dzyazxxw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2xamzrwcg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evtcbsgz.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2phbwtcgm.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gt2fwklchcu.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2atewxjxc.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2exwaikbz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ypofxmyi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2nxqdfyib.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2qmznznev.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eenxzwzy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clwljdzg.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2itrvchmg.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2woqzeify.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkvqukuo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2blpfrvep.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2eqnisbew.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibfdasop.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnfcbgiz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gt2udhxezog.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptncpnsx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkvzagbz.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gt2zogdiqzh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2jebauwmm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gt2rjqfsuwu.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2xikijcdb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pssytqoz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2vvbyteyx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2ougpqspb.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gt2mmheurrz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2sdeckohs.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gt2etpcuwus.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2xqqsmrbo.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2exawlpjw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2wiqrvxmp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2xirtziet.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2ugcwjkeb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2qxllcoac.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2behwlatz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gt2hakkhtdx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2paeaofpb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vzsrxfmu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2yggoggvh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrzxspsg.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2vwxgypos.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gt2yeihbzev.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2doaoukoo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvrymbfk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2jznobufq.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljfjejbn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2yzfankht.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2jgjxolls.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2xaoejlyz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2gqkdgqxy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2rwkcnsur.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2gzgygysc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyyxjmph.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gt2gnnohshy.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2mqfitqgi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcocykbb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gt2vgsegnfb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2pywhibck.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gt2tqqbnmuv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2sygggsym.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gt2umyssvfj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2oyuycblh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gt2tnreeyeo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2atodwyqt.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gt2snfzrjqf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2dskxiyxc.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2ffhjbivb.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gt2csgqbyyt.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2qscxfhuu.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2rrcwabkc.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gt2ydtxzvvf.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gt2jcryiliv.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gt2wqofimee.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2ytmhifvo.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2bjnokxqo.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgfytryh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyrgpuul.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zyuqittv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2kvdhfzbn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2whalxnbs.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2urvivfjd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2troddimd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gt2ouvaoiwu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2cqysaxpt.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gt2buksbpnc.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2tkqtzacb.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gt2noxtcbzt.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gt2rsizmilt.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2owymlekl.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbycyake.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gt2maeswyku.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2arfeyrmz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2pyluqdod.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2njzzopuu.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfnmwkjo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxyahpky.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2ewlfrhgz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2twzqotqx.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2dnwzsmod.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2sduigdbm.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2oxraqfhg.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2nfhanimx.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gt2klvrcwdh.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2wdupbheb.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2kmnblpso.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2grpeysua.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmhpalxo.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2spaidgdr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2tzuecacn.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjwwcipq.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gt2xjkpjrrd.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gt2qhsbccuw.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gt2inbvhmty.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wenfqzlj.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksjjfhhy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2txeglbrr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2oxtwomof.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gt2pdhswyft.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2uuitxxtj.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2mmfantjn.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gt2wlfzoxue.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2ryzhlfsx.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gt2exinnccj.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2dwrpgbwo.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2lkzjggao.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmpphjvf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2xqqyjvpy.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbmwtihd.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2dvhdlbrv.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gt2lrsivpqo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozwzbinq.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2nanhwogp.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2vnqvtttm.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjsksagf.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2umgvclly.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2xohirhkc.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gt2saptafid.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2lushwlbk.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gt2nvgfatxz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2zutidemf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gt2rjjmytvq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gt2scgfqilf.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gt2yucmfamn.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2iyazkoqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gt2gabqnzzn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2jthlnwiq.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2ivljjdkn.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gt2yybrlfju.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gt2opbzwqgs.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2smvofgzz.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzxwfbjx.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2amoszzag.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2sidiaygq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2faxjvlrh.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2sdwlzwlf.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qupwvnpm.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gt2zizajdfh.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2vxqjvawu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2mszzmjcx.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2iusoawgl.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2jinjbgbl.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2lxdfyyef.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2ttsjqtpk.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsbcmwts.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gt2siaeowos.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxrvqekk.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2hhkofenn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwmnmtzx.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rebhkmyf.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2bmpiatev.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqzewwpe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xekzycpy.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2vueswfqr.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2wrnltqyt.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gt2qtpogbkj.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2fzolzhgs.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2ohcnadjj.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2sbqzeyer.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2pjkwyzwg.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2ddbtvluw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2kxwdfmwn.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2dumdbpfd.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gt2ebafeqmz.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gt2fzgzmero.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unelbith.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2teikorcq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gt2lhrcjgmk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2yclxhuvg.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnwwmssc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2blzxxldq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gt2adkzklok.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2mppapzdv.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqhwrmyz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2imdrikem.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czwkbtfq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gt2cczpxahk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gt2luowujdg.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gt2vveamcox.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2tmcsexwb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gt2vwhtofoz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2jngwrzmy.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2boiflysw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gt2uybqyflz.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gt2qdizaqxy.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtlxqpgf.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2bvuesrhr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysthcvdn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gt2jhhqtogh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuynfsz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2aglyzwxb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2tjafooop.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2jpohtqbc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2bzaglieu.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gt2kkynvpsu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gt2poeackje.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2eytfbmok.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2umurkywr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2dppzgvbt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gt2jbsatawv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gt2qpyglatg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2qypdutmb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gt2ixmsexgh.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gt2suoemewb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2pbwgzxku.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2sjhqspyy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2sukoxrui.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2eoyghqiq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2nolgulvu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gt2oylokpnb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2fjoxsxkw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2azhwdudf.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gt2rqbuclyc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2laxgozpo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpcpgquk.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2lvelfkqi.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2fmrrqeln.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2gnzcpyqk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gt2gwxgmjvs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gt2refdumhc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2gxarwtzq.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2olcgibcu.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2vmpbakjy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2ypnivcun.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2caimnaxm.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2cbsinkrf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bcjnbajk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqtuxusu.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2mgnblbwb.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvegopld.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyygdywx.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gt2aekykgzw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gt2qysnfurr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2ugtuokds.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2osqkzjmm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2zhtzcfjt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gt2geeiyvef.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2ouzfmakr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2pmihloxy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2shbqcsyo.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gt2icmosafx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2kgfqakxd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2yhfncico.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2taacwzgz.html


<!-- 参考信息 -->