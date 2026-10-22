代发 wailian999

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gt2bscbdevm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gt2eiaosqvh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2eqwztcst.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gt2fwxtchvh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2dnrnkxpl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2yefqsivq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2razclqla.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2erqjzncc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2audgljnh.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gt2kltwgpfp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gt2khbbsyxr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gt2oakwucnx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ihkqgbyw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2kodfsutw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2azlgmece.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2aspfmrme.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2orltqnwz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2fngvurza.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gt2revppsqk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gt2ubgybbah.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2vydczvai.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2hreqvdtz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2mjyiurhv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2trrovsyh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfoaxthr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2jdwzaslf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvvyuoo.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gt2bdaznjdf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2wyyhuihc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2ibwhxkix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2snrvnppw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2fiuiocrh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmnfiwm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2tshjzall.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gt2uzjloxrp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gt2rqwgrwsi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpoadbaj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gt2bppgczme.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2suibmjet.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2bemfuaiu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2cwvtzxis.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2esrxdbmg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gt2orpnyrhi.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxdbyxcf.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2zegjewul.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gt2kxotlyxs.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2bnyhzrzo.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2jlltxyni.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2rjkcvvyg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2qvrdvkem.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2xkbjkehb.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2yttqamqb.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ktujesoq.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2dnbgnxhy.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2pkyollel.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2xoloabsl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2xdtmgkmf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gt2qasexezg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2znzhynoz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2zgajkqes.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxtglhvv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2hrjeyblf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2tmfqxxlh.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2acmzzxuo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gt2srszjfsy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gt2wuhdewbw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2tvzfcwjz.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2ptrppzzc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2ntgwugjn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2tcabuxpo.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2mcaakdqg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2waoaejlz.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gt2jjbobprh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2urckzgvl.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2xnkagcxc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2fiaxzoah.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2ocdpwkwe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2iutivlnc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gt2xhrucjkm.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqnwddod.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2fzctwefm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2khgrtzlv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gmcbeyit.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2korsfytf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uoxqtwgk.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wuukhtqm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2fbvylqcr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2gslpepig.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xbnzijdw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtnaupjf.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2nslpjdkx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xigpwheg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2ugpaoqrg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wbzazwnq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xlygyzsf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ojxodccz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2adplgzxs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2nbybzhym.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aegvqsok.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gt2bxaqczly.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gt2zpwddied.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gt2ykknciav.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtqlddva.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gt2qbtmztmj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2baqiwwuk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezluzcbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gt2unvqyglk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejrpzlme.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2omvcslig.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gt2lbplpmdc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2owngcmlq.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gt2vyfjwdvw.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gt2wocgsplv.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2ymdksqpx.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmlsiyjg.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdwmigmb.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gt2ivyaxkwn.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gt2uvxnkobv.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2frsdhpif.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2oxijpchj.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2emerwrhz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gt2oxvtpjea.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vynptoic.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2yhoxvsfh.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2mlyctgwt.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jkcftajq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gt2yhxeckwx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbzchjzf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qfsulbqo.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2mvjzlxtd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2thcufrja.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gt2ilnkbubh.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2dcrhfcux.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2xyorpjsd.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gt2zxhnfrtr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gt2czoixmvr.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2almqihjx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2bwppdjkd.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2ctcczljz.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2uirkzgsp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2ialtjytx.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2btsjlzwn.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnlelnkj.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2yrgonzym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2xvmbwvlb.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2fmrlqkdh.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2qhimyazy.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abeuskzu.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2uxhbzznm.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2ycvlhkug.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dlrwuxln.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2nbatqzaq.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcjqqrnn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkyncphq.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gt2mhokqtiu.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gt2lcebjliu.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2pckkzvpl.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gt2xtltsjiz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2dsvmpmjl.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xxrnxiat.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2pegawrxi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddceqtln.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gt2tpsjtkfj.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gt2oohzqyum.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2srgbbihw.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2uypocxiv.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkehprbk.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2oyquunfm.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2ajzxhggw.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2nangirbc.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2ibvgjnkx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctucjbma.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2urlkviiu.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgefvmug.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gt2timqgmzd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2sbtdxefb.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gt2puglzcgp.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gt2qprpxqeq.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2ygmapzxs.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2jqwkcnhy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gt2gjrftiwd.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2fhbnggxy.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2zypxythl.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2lpuijbbs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2trztjchb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gt2oumgzayx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcyqxdd.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gt2ddsljhod.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sovbmoef.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gt2heolfkda.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gt2idfbigrl.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2kdipljze.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gt2gpfpqfxb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2tkeycfmq.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2gosxucpu.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2rbouzihz.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2icnjjvyk.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2itelchiy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gt2xwiliaoh.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2hndbocre.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2ytmtcxyp.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2fpvqcthh.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2inwqqymq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ystzpaqj.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2ckbywbth.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2zwhjmibf.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2hozcfzhq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2jrhayfgg.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2vhufloby.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqycybjx.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2lqpueuug.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2cpwtrqpb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2xunschuv.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ovdiomoz.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ewyhgphf.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hkcqsysl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2sfrrosxk.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgywsdrs.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2vwtlsgfj.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gt2pkiroorb.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2klqlipro.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2rufmxwii.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2xfmavxud.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2xrafjnxl.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2exjytdda.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gt2uxbsvpym.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gt2wgsvkorg.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2jzyeucko.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gt2yybapdhp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gt2lmeybdej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvqvujmd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2pzlzcbca.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2yjkzheby.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gt2oqbdyvzx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gt2hopzotsm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gt2nhgnfovx.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gt2tzbfndlw.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvqeggcq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2vytmblan.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2facoclnp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2sehqxsyc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2zllhqkqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2luntmscm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2sbsistsv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2mumasmrs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gt2owuwwkji.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2wsiphpii.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2eskhnbtr.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2ucarjmmq.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2piybnigv.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gt2pkglurmc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gt2hyvyzrha.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gt2splnvpyi.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2wismetay.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2twgekphy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kihcaiiz.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2bnythphp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2dlwqnfdh.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gt2djtletqn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gt2xqydpkbo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gt2mskyzdlb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2ebkeazip.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2azvamyqp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gt2lbmwdlyp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2zgfddwqr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gt2rspzrmao.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gt2puqiagbd.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gt2qwyysrfh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gt2yqinngkv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2dmwyntcn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2pysiveao.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdxhokiu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2dwbheymm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2zelsogxp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gt2wnsucjap.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2iwoscesb.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2xubebgcc.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2qxuhgwfj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2qktjqimb.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2mrmgupwn.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2sovyltwi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlojrput.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuonmaai.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gt2slcvhtbr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2gyhjxgft.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gt2suemfmzq.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2bjdayvkv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcfmehrc.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gt2dzidvllh.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2btsnhgch.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gemccyjc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfqkquiq.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2ywfgqeyg.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2vryxocto.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2sdwxcaia.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2blulyrqt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2cubifmrr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2oywmpzmz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2lukhtuxo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qparrdog.html


<!-- 参考信息 -->