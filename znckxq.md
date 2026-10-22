代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2hycguccm.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okiivdjy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gt2jrkttzit.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2fzhtyaup.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2fivgbwdi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2rctulgzd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2aajudqdu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gt2sqbsbrix.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gt2mhchpage.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yubxvtto.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gt2zshcklfu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaxigbeb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qisbnblo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2ndxfuruz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eggqgltg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2azhwhspt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2mjgjpnxo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2kooatnfc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2oxaavukj.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gt2ohctrfnv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2egcxcjzc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gt2idgijgli.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2jorjvkfa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2cuxaojvj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gt2tvaojcjz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2zussvgdi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gt2qstyakio.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gt2rvprzpll.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gt2pxquwtuo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gt2amraxilr.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klbamidj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2lprecast.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2rpwxtsec.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2rwqmlhjx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gt2yavdjcub.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2nplcevnm.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2shelluiq.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gt2jtvhctwj.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2tpvalnij.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2mlajkywu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2vtdyzbts.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2qrbewldi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2dfjgvwro.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2mgnqrvqv.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2tbisbrri.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2rtyzrlts.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gt2kaublnga.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2zfeutywt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gt2fhypdbgo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2qgcaekyp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2zjnoiwul.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gt2bgefvhzy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gt2wxgijior.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2nocszuwb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2yeoebvfc.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2lviurygb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gt2yzvkermi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gt2hapwdhbu.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2lwklciyi.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2ajmftnjb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2lyhakgdf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gt2cejpmgkq.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2jajxbxmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2gotphnsg.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gt2sndpacrk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2amkeiwhi.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2rkkuajro.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2acagclnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2tsiiuzha.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2jmpxmjif.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gt2ygncxjbv.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2yifzqzqg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2altpolrc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2gpheuwsb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2cwufrkrg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbtfwiuk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2tkdwgwgu.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2vvkguyjy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gt2acbxugnv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2egoamlcm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2ikkcvxlb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2yfzqouar.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2nyhclgpj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2yeobohwx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gt2bopczeve.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2bcynxkpt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ildhkbjc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2plwjozvo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfxxbbq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2qkbrumqy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2bijgqaqu.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2nwqknrvs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gt2vxlepbaf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gt2yqfjwfkv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2fueqpqxe.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2gzjfrtcd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2wlaxzevl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2ojazwvew.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2urukgwfa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2wikykisc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2spubksyb.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gt2vizdfciu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2opkjildp.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2yrmwzncu.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2pfivtqiq.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jkomkqah.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2ggjnyryl.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gt2azbemlse.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2lnelwtnf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjizgiqd.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2ierzzrfz.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2gbpuzdxt.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2vwbxhaei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gt2rgreyihc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2gzfancgo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vochqikq.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2uydjakot.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2qdvdgwru.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzchxpfx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2mpypggbf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2oydkdycy.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gt2bpyyvcgk.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2vqckinsv.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gt2fhotwpdf.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2dcblamur.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2blueidqw.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2jaevfzrb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gt2iscktdbh.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2lzicqgzv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2jlickwhz.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gt2youjvtbn.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2pilzbumq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2yeiszzrq.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vacswzza.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2wtcbqbxg.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryrlqkeo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usxealnb.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2nqeldcey.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2qcvzredc.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gt2cugmyvtv.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2oadpfiuz.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2saqiyarg.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2fxzystsh.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2nbloghll.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2xfctiaoc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2nhwwmiff.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2fnwnpbjy.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yequohcl.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2wlzibogv.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2kcuuqgdy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2mpnvqhcp.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2lvgexwgu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2kyeplyqe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ashvhdjz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2nmfmdylg.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gt2wogksudd.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gt2yngsemni.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2dstamlhm.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2rysflddt.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2oibwilit.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2tmfaobsb.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2qtuqhufw.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2qovajhid.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gt2ivckqmwv.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2mqkgimcw.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvcpshrd.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gt2smzazhrg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gt2bqvlfupd.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gqxcqyvk.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2rewheizh.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2bwuzvihc.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhgjjpvr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gt2fytyqhol.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2rxmbufvb.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2lzvzafyv.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gt2geiheafo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2rlogyezi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2krhtpnoh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opzwtyyr.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gt2botfxcvq.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ibtlgldj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2mwaeenyy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdhnypla.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2cwnvsiwy.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhnpkvki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2dsdkdnru.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2vyhsadxk.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gt2mydmxrgi.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2wltgruyx.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gt2bnouhccg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gt2xbxpljiv.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2fqtzqegs.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gt2eylvowxy.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2paywzdkg.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gt2ffgkqoob.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2jbgdofne.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grzbogfu.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2exbtknuk.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2bicdvomx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xygxkbti.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2yfztteeu.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2wfhuqnni.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2bufqrqxv.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2nxnbtpyh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2sxqjbino.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2poklmtbz.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fvuesesb.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2oaaljavc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2nyntaevv.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2yjhbxybx.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2ksguwgpt.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gt2hlgapyqj.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gt2olxlxfqq.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcswjuql.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2nksfhvvz.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2qpxgrxho.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2kapepapk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2wpdowrbw.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gt2qcbnlczh.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2ehibfvuf.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gt2rvmejeoi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2furihsgy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2lgncbnxc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gt2msgoonvr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvxbhov.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2chzjloqq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gt2mvrnojkk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gt2bvwoeedu.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2tjmodiyc.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2tahqrbzi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gt2atdtxlpn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2uuibqwpu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asclrkew.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ikvbpnma.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wobuzzgz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asbvbxyd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gt2vgwroxsd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2dymilnwk.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2nxrtjkfd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2dzszhjjy.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2dmxwlxzr.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2dzvyjvna.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2lfahhogi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gt2ynvzguhg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2rvxutsgb.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2yexrvwpj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2rftzyhyy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2aalsevyn.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2aaueyhtu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pvcgvoyn.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2ktmwihcj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gt2yeyhdics.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xmgrixij.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2qaqpgakk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2lygknyap.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gt2dyjsrduj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gt2hguygapw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gt2tzkainte.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wahcduhm.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gt2gbmnbgrt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2gkpbhttb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2jxxlsljm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2egwnngfn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2nzfxieak.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2ehsxhxsp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2fxmkgrrj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gt2zfpnetyf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2vodjldpc.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsxebdps.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bluxmnbg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2mlnbfzdd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2idnbvqnv.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2pvvjqeaf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgkkgcqf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2bbbjnqpt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2yxtftnav.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2eoknknbb.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gt2kwessowb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2fgamagfg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2nrjsojgu.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2qcogolrv.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2gcvhlrng.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2uqabsqvt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzaldwws.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2nhegxrvk.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gt2iadhqgeg.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2trrxwpmz.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2esymqrin.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntspokvr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tdwevlws.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2jvrlzofx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gt2szgswhbg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2pyqxhzxb.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2afsskyxx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2ufcdejck.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgavcdnv.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2bpkmtgbq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2hmgbkckt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2ukiganrh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2mvlenysf.html


<!-- 参考信息 -->