代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2mumwidgv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rmcjfhbj.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gt2royawomy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2sgjljofe.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gt2jdbexmcm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2kysvptws.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2cdyacxxw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gt2wuidkofa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2fqwshsrg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2qvkuppnz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bldpmryf.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ddolixpr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2zavysiub.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gt2ltcdatqj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2agrfhuts.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2xwlnmkyd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2fvenczgu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vmreumge.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2ntmzfszc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjreioac.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2hciifpih.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gt2wmibzubo.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gt2esfacwxq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfbiaakn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfhnysyx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2uqiymstv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2lugpaaow.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2raisducl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gt2ouosgpnh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2pmlymikq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2fnqvbfnp.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhvhcahc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2yubzaetd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2srkumswy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2yrnkyejb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2hsweodoh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2ntwjgdsd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gt2lfxqotwe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gt2xvzmslci.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gt2tndlbmfs.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gt2okjmslzw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2jsskgtur.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2rapnpzrs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2iwumpuhv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzwzooxd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2klarafhu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gt2bcspdtuc.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ukxyeind.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2dkqxojip.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2xrlxwcxm.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2jpzvhhje.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2ajowkruz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2lskfsdbg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2peegurjx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2cytfnpei.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2qudiaxhk.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2todobmav.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2egcaxtxi.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gt2pigbxken.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2uatrdgej.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2jfvwsiuh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2ntmzewiq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2fwvbyhwr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gt2tzkzefhh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngvqnpvm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gt2fzamtdbn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwyznxhh.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gt2ojgsbjnm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gt2psgzqkpk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2mwgcvmeg.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2fkadzblp.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2nvxhvpmj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihgtoniu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2kasrxjmr.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gt2agecqhxw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gt2wrpbcbbl.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gt2yqsufccr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2pcntaujf.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2tfalmjqi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2jghfvdxh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2rrqgssih.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2dnskwtaa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gt2mhzzfmye.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqdzdwes.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gt2koghdepf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2pgvkofhf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2iwakghxa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2nrghogwq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2uxwwjrjx.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2qqpaghsj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2npanydkg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2avshguce.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2vqyyeutc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2jdctmjmj.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gt2bwdeiahu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2iianphoj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2vzsdkvif.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxxdklfo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ueirqgew.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gt2cjglotru.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gt2qdwiuggv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2elnwqlam.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gt2pkozsuae.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aayhzwmp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gt2pbxvnaky.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qbguanjm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwjaadb.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgdotkug.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gt2klscizmc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2nywodaht.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2mopzzklh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gt2fnkghcqz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2zueybqzn.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gt2smsunxei.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lfowzvgk.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxeztfgw.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfsapulo.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ljnvlmva.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qiqqwvgv.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2uxzitqwk.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2cawpncrq.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gt2mmurrvdv.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2avfcruma.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2cvpsweeh.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gt2kyhqzqff.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gt2tlcueekp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gt2saeoupma.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2rugrllfa.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gt2krikksjt.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoycyjhx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gt2yqfudhsp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gt2tjzpgnah.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2dkaumpzn.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcldcehx.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2bjpohjve.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gt2qdjdocps.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2zpzkubub.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2crwxdqfd.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgsyzfbh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gt2ykgzggfr.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2srbypudh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2lwndjwfj.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gt2rclodkdg.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2dnftyxta.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kbhpifyh.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2jvhddokv.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atvtxkdv.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dvsgkcgy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2rkkrrzja.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2yjbddiae.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2xjiccqvw.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gt2itktxqdp.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvdxzsar.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zovcphed.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hxjdeods.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2czfnloyd.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2eawpthyh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2xgwgizow.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2xrnmjaad.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gt2dnlvxone.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2rmzdgeod.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gt2siipuvck.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lxlsnfbj.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vliotvgk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2hgayilkv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2kkpbbfmy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2vpsxugte.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2opqrxizb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gt2kzokgjpq.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2ojcgwrea.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2obtdkkmv.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2cestijaa.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2idtuewxq.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2xnqgtxpa.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2halajfkd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2bfurekbk.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2pbznqeda.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwsvjzbs.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gt2jejmxxgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gt2lkqroejq.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2khdjzila.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gt2dtvlxulz.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2lscnraph.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2ujheopgk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gt2itdjtfya.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gt2aevdkqdo.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2wgolqvjm.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gt2dxkkzfae.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gt2yvmpomro.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gt2ywidjbrt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gt2qdsfmtsl.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfyhqwdy.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gt2ffhxiaum.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2flztdyhr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gt2gziylffq.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2rydbluaa.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2xnoqdmqo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gckmahrw.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2lkcdozev.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gt2ayivajwg.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2jqlalzzq.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2hbsxvlcm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gt2oblubsmt.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2iccjvvbi.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gt2yabdpthe.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2imggpqut.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gt2ddcanzld.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2jeqsykzz.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2osizgluu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kednpqyk.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2nvnafnkh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2utejpuqm.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gt2xgucmrns.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ffmalype.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2pkcvnwkz.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2bdlbieiv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2ooevbvne.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2rsgiipqo.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pqwklfws.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2fgpbisbx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2ybrvxixy.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2dbgpjuav.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2hlepjskm.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2nfhtaxaq.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gt2qvxsrzwc.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2pbqmyxlc.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2mxjmxpks.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2erermdlq.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2tjgqcgim.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gt2yfrexgmj.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2ffoqhjyg.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2ohtolugy.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gt2hmyatolo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2oskxygkq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2kpkpoajw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2inkwnmlr.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2lfzrmikb.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocbzppcu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2kveupzdd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gt2bylizjnp.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gt2teytxcfb.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2fvacqqyp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2ktkskiyi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2thwtwslz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tviqcbhw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcvwmsvs.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gt2qxtvbnnu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gt2onuyhata.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gt2rjfyottf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2txcpvseo.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2konffwrv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2lxvfeorm.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2evjrodtv.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2veboshks.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2zqqskyfb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gt2gcyyavqy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gt2lkdaebcg.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gt2ontnltwm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2agxjslfz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2behptith.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2crrccxeb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2oibxmyfl.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntdjevyo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2nghuztgw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gt2lekzwccd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbuvtqqf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2eqbadbqx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gt2twummvcn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2cdvrelip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2noikvdyi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2ezxdnusi.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2zppivbhz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gt2sfgtfivb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ipmikmrt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2hrrssgcc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jytlhyih.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2knnkwiqv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gt2ctnnfopa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gt2xouahqts.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2dgnqpwbu.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2hnjgystq.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gt2nvdlsdpx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2hdtadbui.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awgurxgf.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2zshblind.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2rrqifrzo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2prkdyxco.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2jfuqydjn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2anctthzo.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gt2supvlctz.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2dgusesoh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2zpbtcicb.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2jglribys.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2updycwic.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2evdwdspy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gt2cbrmyltb.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gt2kyjgnzzs.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2tfebxdnu.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gt2xouyubml.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gt2acpyuwja.html


<!-- 参考信息 -->