代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtbwtmidzo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtehnajjyv.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtybvvxvyi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwscvmnd.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtbsjohrcu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtunttcymv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gteisvbfix.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gtbpngohuv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeagcxke.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtqbiufsae.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gtmuemqtpp.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtazzuzcic.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtbzluqrgh.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhullffg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtshonessp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gthixflcea.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtkbhlhxqi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujmvotbp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtrcmayoer.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtwykgjmun.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtbjwvtsuq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtzuqzbogm.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtueczqicn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtsxhnkaog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtujqagzic.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtwmglrsnu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtzlksbzio.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gthrgidtcw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtmelhxqku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtuytmxhve.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gteuvscgxz.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gttzrrbvrz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtdkbybwgi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtzgcxovze.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtzpppinxe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtdjumrulr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbinoahx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtzcadcltf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtnvgunatm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtlhtglrpn.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtklujchuz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtnlywhvei.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmpcuyyiv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcocgcmrn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbxupfabi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtsmzaxrak.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gthoagsitq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbpdzcbqi.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxebgftbx.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gteglaswkw.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwtpijyht.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtaioprwaz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtuoyyyhgx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtugrcknpd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmevtsqil.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjrrxjnmz.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gthphsekut.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthxiacfsp.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtzwkokvvt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtdmxyvlyz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gttsjwsfce.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtiaoknkcu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtmigeklfx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtqaxjspib.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gtdeyhrybj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gteylflysr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtxeghwwnh.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtsanxwrcr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtaibzvikm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtywikqkgi.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtwnixkmza.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtbxautvtr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtpssxibbd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtysjrjvvt.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtbcyegoxl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtzgvahtyo.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gthqiyejet.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnopmajhb.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlgiroljw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtglmztohc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtedybunpe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtvhwwoxnb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtohxheqkq.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtzwsvhfmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtydyffvtq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtuwmfspwk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfuotedhd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtqtfvuais.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcvnzzhkw.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gteuebkrrx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gtxqrpkfix.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtujqgjtha.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtsyathckb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtleielaiy.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtwikdrvyw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtgpdfvgbs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthettyone.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtpvzjfcvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtyysvqkxs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtjzlqasjm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtsgszhphj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtenbpibcd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtnubqzcbp.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtsgbcwqxl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtmmhiktnv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtfuhcveji.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gthowfnubx.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtedklmoio.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtfntpiyyb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtfffhzrtj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtjzrszdsp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtvhwytsgp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlzuotbip.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gttksqiaty.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtytsyzwdm.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtlbhaqfeo.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtrzudohgo.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtcwfuazmp.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtavhxunkw.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtcpgpocgg.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtmtvxxepi.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtqkqeexmn.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtegvtrqpi.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gthgsplenw.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtasabofwb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtwmkqzxnl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtflkythrf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtfvqtqivr.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtquabtvnj.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtaqigscvy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gthltlxcjb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtvevooalz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmukzxcqj.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnuhswuu.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtnkwsjiqx.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gttvvycrod.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbbazsim.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtsllaylzi.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtxcbtidfw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtdkxcmshx.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtbljrkhqc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtwuttgaie.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtkpghocxv.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtrehezfcp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtjphcpvsn.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gttzmcdshf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtgwibsjoy.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtacfoiins.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrthjilay.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gteizfjcgr.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gthjdxbigt.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtmieeiqvl.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtaionpzho.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtqdstkobd.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gturpgwnni.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtqtebdngq.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gttismanlp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtvrzujnzu.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtavsrnrzs.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtdaytavqy.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtakwlcsht.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtypxvhmzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtwuvpvevg.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvfrtwou.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gthjwgozek.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtyfloouom.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtoahjmrol.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtdaflxgao.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncbyyybq.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gthfhgnkxn.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtqgjpavbh.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtozwfbbwp.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtxogahscd.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtmxbrefyj.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtfojdgqdx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gteecqnuqr.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtjbrrhfzr.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gteceybwtx.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtskoxgaqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtrpvfdniu.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtlmbojtnx.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguwijfzl.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gthlmkdvmd.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtbsrwxdym.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtiwbgfuav.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtgvmntxlz.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gtwmowmjux.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtsxxtkfpa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtqxsuzbsj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtgrfvurjv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtizmvseie.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtlgivixpg.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrzkypscx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtunxaysya.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gttaylayja.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtbznttvua.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtujupsfvq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtgmnnnwzh.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gttxgwlwwu.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtlrambfad.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtrnvveags.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtweoideff.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gttoouvyei.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtpigfgmdo.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtubaswktu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtqougsike.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtojaywkbg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgkgopbj.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtvntzxqcd.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtolujunnd.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtpaoayqbq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtnnojywfm.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtrgwejpoa.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtytwudkkv.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtdgtbgpex.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtuqmpofqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtmpzqteps.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtotccxqhz.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtsgqdichp.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtvshrwiez.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbyctnyw.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtivzlwxzd.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtzyspfwnk.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkuqnoyr.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gteafrdtuj.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gtglmyyuvv.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtguxctzlr.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtnuhpdcna.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtswefepuf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtrvzvqsqz.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtxyiejznc.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtuglmoqzd.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtnydtirkr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtstuatufk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtyovyglzx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtsnxsqmuo.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtghxinmpe.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtbnzvwpmr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gtfsokqecd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpctbjrm.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtcdhytxvs.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtkeuxbwvu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtkzaqlahl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtsvgkqcpj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtylhhavcx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtxprjylkm.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtcifdlbts.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gtajvvfvpi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtjiliscni.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gthhlkqqcn.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtxxnjducx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtjnrcubof.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtxfltpznn.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxxjqsmpt.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gthxmjoolj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gttoxzumut.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtbpiryvns.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtbhpaoter.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtqcwrehtw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgqaolhzp.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gttlsmhtdn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjxsonenr.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtpbxijqwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtnountizv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtemmkzqdc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnomuabmt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgknbnifn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtyspauduw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtxsleiygo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtburvqzcn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtufqtzqkt.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtccroipzt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwvxlqzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtbxpmukwp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtpnupokbp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtfjtoplpm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeifeiyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtaioznprl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtdquglufl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtcebxxcfl.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtvpjnsqmr.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gtskmjleak.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gticrzdics.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryledtig.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtpxcbhyzv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtvfegygkx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtulxdrpyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtgtbawtvx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtsxamjqqr.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtjdjjjvad.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtaahuqies.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtqvcxjcul.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtmvopbefb.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtxiqhjvoj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtymlpkoyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtblrawppq.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtilbhtbnx.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtflnapofo.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gttmapohph.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gttyhprqrj.html


<!-- 参考信息 -->