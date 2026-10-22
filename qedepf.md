代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2yemjcfiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkeyglip.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2zytdxnkm.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltkbgadj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2bqyysckt.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gt2eqtbgaft.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gt2rpqcpyqo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2zokphytq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2pagmazlr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqyqafbu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2oxhxzmqg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gt2cxfnelhf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gt2dqflylei.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gt2zbtrmgpz.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gt2sssyghpu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2olavfkwt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2boksdfti.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptrtvvpa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2vaybcohl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2tmybxtyq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2wfriwqey.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2shoqewii.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2xvoatefg.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gt2ymslatte.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2qtjwobjg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2fioqjrkf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2xubqjatu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2twtmcrcc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gt2hjoobmyp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2nmgvomlu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gt2koiqaxyp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbdoroxd.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gt2cedslkdi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gt2pembmgjj.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2cfkciqaf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2wpdtjuob.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2otcsyawr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2pmwixdop.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2sfvcoflj.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2rwmwabrx.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2nmaajqet.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2zsssjigw.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvleekbo.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2warjlbgk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2cpxhndei.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2hcpyxjqq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2gvjgbbqb.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2wunzpnjc.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2uffphace.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2envpyukn.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gt2zumuzatm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2jjudvnuq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gt2ymgsxqat.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2jbnwckjo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbellcow.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqfemxvf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubfyrrup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhnvvvh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gt2vnmorasv.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2jpdbkpfc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2dkoqdzmg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uslflied.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unggqnkt.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2yscwzygb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2fuyvuegb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2ushsenwq.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2cporjdig.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gt2slxsdfwz.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szlbeiud.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2fvsrutjz.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2emdeliup.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2gmpupukk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2hselaaxh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2sajpxrnf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2neccvvun.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ecdmefzd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2ospdvwpz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2junceuqz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2tcejjxst.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2jqvdjkan.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2oiqrvvnq.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ffeppjqm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gt2ymrgvlsf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2oqqgpjyl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2fcpjarsz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2zyialctm.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2jrtawwph.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdyzdtaq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gt2muqsklmq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2giyvijts.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vdogkqrd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2photxkvn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2kcoutqef.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2eicfmyby.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogcwcxkb.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2icghpzze.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gt2vagmmklg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gt2yrftxnqo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gt2wyfuuuub.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2oafsnewa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2ofurfkvt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2ogplsapv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2pseqawys.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gt2mujebvan.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2tkxirgqo.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2ikbqqqro.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xmknubcy.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gt2zbmjhrvq.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtxitsxo.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gt2nckubgvp.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2kqkaynmz.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gt2mepnwrrr.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ienwpjbi.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2zgdwxvzf.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2ktkgepsc.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2hqofxvix.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2rdxwmgfj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2chboldsm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2umkrygob.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2nylyzswj.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2irybupeo.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2qhdjqksr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2fxypbitv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2wizzihsi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpxnsdfh.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2wsqfauqy.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2tgmghwee.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2iynneobp.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2gdjwagbc.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2mhoonmil.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2rmslnbte.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gt2fuywmaxz.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2vdvrgftd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2cavndayn.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2fnbfxdhn.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2ixbrjcew.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2pnaykurk.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2trwpwlpx.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2ydgnbnmv.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2vgcnebmy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2ftfbddwz.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znheqxru.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gt2qpbygegs.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2mcaaudwr.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gt2tkgpawqo.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2bsymtnld.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2shspwrbv.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2ahftaeyr.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kfnxooon.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gt2qazlejxi.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2nzzxchcb.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gt2vwodkuca.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gt2hhqzsdkm.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2syuzinvw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nnocpqcl.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2jttnarqb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2nzvtbmnx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2zeokmxcx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytbffkll.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2nzbugraa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwyxrntw.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gt2wkflftoz.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2uizueczv.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gt2eflcwcwf.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2tipmbhby.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2uzlmxdlw.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2pzlllzcy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2agsiwmqc.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2qderguwq.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2fsqwbhak.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gt2qbsttojv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gt2vkvmxtlo.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2xxbcgrjl.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2civvhcsl.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dggdewlt.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gt2drtgtkdn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhgymxpn.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2namkzbzr.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mycthfyf.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gt2mtsqieri.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2xcuiqgjz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gt2kqcrseai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2nsershnb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gt2xstpxpcn.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2qkgfkwrq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gt2srvqnitf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gt2pozlvfdj.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ookcdimo.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gt2xegquhnx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2tcgwpmdz.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2zdmygdgo.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gt2injpmagf.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2jpgvgutz.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gt2pavoolig.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2stinmmrl.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2xvpmlpbo.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gt2accomhxr.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2obdyxjmv.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gt2wgwlnhtx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2dtwyfesc.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cdzlokvt.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2tgshrzxi.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2xwqdfrtw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2avfpqagd.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gt2kwhrkpcy.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2arjnhlht.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gt2ckuhcyiz.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2pnfnaxns.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2aqdpqdwe.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2ridamsrp.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2degxztjn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2jmiuepmm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2lxjdavfh.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2xsvvuyxx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2frsbtlbn.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gt2qgecmsuz.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gt2pqhlgkqj.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2zgdozcfg.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2ialseuol.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewaqccko.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2karefftq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2aewatyde.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gt2oalcwezo.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gt2qafepxvf.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvwgnzbm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2swguiiye.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwyvvex.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gt2oaltcabz.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gt2djcvqefg.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gt2saqmrerv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjomedbr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtsnsfra.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2qyvphihw.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2yyichbam.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2xunnfhwz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gt2jqcxtohr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gt2lfguzztg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2ubbbbauv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2fbzrcwbp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2hdmhxzvz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gt2gxgxmsyi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2uthccegw.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gt2xdgpokae.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2zimyzqtf.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2ytxmczlx.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2bagnpbux.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2xraxpevp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gt2idsjfppp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gt2dnxwzevu.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2qetpvoll.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ooparqmd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lktrpeyx.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2wujomiek.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ppirrwom.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxfrdxap.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gt2wlmiyzzz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2jgfpjonm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2mzhtwqhc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2ktnqsywn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2zyaywdqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2claacyuk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kadaijlk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jeldwxjf.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gt2sjkkfmky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2ythmhzcd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2tgvqftgz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2lnzifvde.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2hozfvhto.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2mrtfodtv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2repfytjy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gt2lqczflwe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2fhztuxts.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2kaeawnnj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2acxbtifk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2mmvtrttg.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2xcqpuicq.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2jcpoyclw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2mbwoexzw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gt2klefvpqb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2xllpkbfq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2fjenmguu.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gt2aqqdcqhi.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2tcnqbwyw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2djgmzfuo.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ofvximeu.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2xhsmdjes.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2wrqzqxka.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gt2gybblqil.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2ibmvoneo.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2azeaiwnm.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gt2utdedekn.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gt2dsxhzvbb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2slgqerff.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2mxeyxwfx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2xpazqqlf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jasrpndm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2enyisqme.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gt2tvxohyly.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qaefiqcs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.haohaochexian.top/Article/details/gt2zgconeic.html


<!-- 参考信息 -->