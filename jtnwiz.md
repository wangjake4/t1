代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2eafuplwv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2ytmvionk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2ptpajkrt.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2pkdgdchm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2cispfzoa.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmehtvcu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gt2zjwkglsr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2clkzbmyp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2fjpeiytt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2uhkaludo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbdjpzyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gt2imakjmdv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gt2rvqulgre.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2moglqens.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzivwtdc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2guratukq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2jdihzxqq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2lrqyusgg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2ivtnxijl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsaatqod.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2xmyipjyt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2ebxceirr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2ngryrtwa.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2hiupkeqj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2tyshnbdj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gt2tspiyjws.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2tisiyzvn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2hydkzeyn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2amhnixcs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oawihlbb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2romubhzp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eggyujvb.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2pxjyxgub.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gt2dclpdvwl.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ijazdsdf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2iqkmrkbx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2nybydbqp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2rxqsaumv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2ufqybwds.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyencupf.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2vupzvkla.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2npiuukmb.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2kbcypauq.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2guuchhud.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ezkcnvsq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wllkangb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuqppvrp.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2hiwpncyh.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2kjxhacck.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2hcunmhev.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2wlbrvgty.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2dryxuxbq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2ftpwzqjb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2aysrdqmr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2tqdrwlyk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2cueduonu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gt2vgvstchs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvmchpei.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gt2hnrlwhju.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gt2nobklsmq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2whdscooe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gt2jcbchhvh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxlqzuy.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2zatyahaq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2zlnkafta.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2ivfxboqt.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2ockhiato.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2tlerxzap.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gt2gpkqiccq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2jljzyinm.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2rxudbvnt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2dxnupywc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2mgmetfjf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2oksbfhqc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqwwqthc.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2oiqzlooe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gt2pqsayvso.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gt2rcqszrmy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2qnegyuyh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gt2oahdvfjx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2kgdtddnq.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2qfspwobh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gt2iwisusap.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2cwmtlgdg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2dsnhifek.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2vxwxymjf.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2ofvuikyq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zqagmyrx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvdbwhdy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2hwnzojzx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2lmfykdqo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkananpd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2zvkiooir.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2qrbygksi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2igpqmqri.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2ovmojoee.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2schmltrt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gt2djsoiaid.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gt2rwnccvxf.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2qjnhlkcd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2gbsmpxev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2zblkjdmq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2xuzhjotk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2brjmiaps.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgbazsst.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gt2vgogsneb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2khdmpgzw.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2ditemdan.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2jiicveal.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2zgheiymy.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2cipnyuwt.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gt2bqeckjdy.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gt2orbusetp.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2vvmsypnh.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2blvljvig.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2rmltlvyn.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2jpliisdj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2wqlddqhy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gt2kthklwbz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2ouhndcih.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2rcibtala.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2cnlimgbq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2ttdentfa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gt2ryztcmim.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2bsnvxozj.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gt2atgkluhw.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2qfpptdbb.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2vyxfpzjb.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2ndglmscn.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2zrhqogfo.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gt2kaintzse.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gt2xqqqdggu.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqvansev.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2excfkguc.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2ormlepuh.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2byhctpai.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2mlvmhlbv.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2kazucsok.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2lhrhexzk.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2jezkhnlm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2uvaiwqnl.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2utclagia.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2rcqelvfm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2suklosen.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2rcmhilva.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2qcoowjwp.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2atxgrgcn.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2pjsukqwl.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2bbvimlrs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2zmlmzyaz.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gt2ixpgqber.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gt2bdibydjg.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2gqsuqiak.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2hrmrqjme.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2jcadpcod.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2bgelyypq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2nyxjkkun.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2juzpyzhk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2psjshzbw.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2wtgnjhol.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2jczmnxwx.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2ejscbzsq.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gt2oipqhcyt.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gt2xpgjbyjj.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2mrfklzqw.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmirppuh.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2ixdskpoo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gt2xdcnmfaz.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gt2wicqibxz.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2djnbszmd.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2vvexvxpm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytnnpchu.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gt2emtirkbw.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2jyybnfaj.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gt2gzhlping.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gt2unfgskna.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2xipzteul.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2sitljaqq.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2anyozayj.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2fljuhoyi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2tgktadvz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2nnfbeomr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gt2eaukhspl.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2fepfsbjq.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2rxoxkhaw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gt2jxpwernz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2evvibqvv.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gt2ypbvlckn.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voubnbsu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2ccnhltmt.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2mnhcwjna.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2sbxrtzhb.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2mjzipxan.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2znkkngma.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gt2werngetf.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2wpsugyhs.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2ndsafoir.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gt2zllklfji.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2ussjfrjg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2whpwpgga.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2ksggkywp.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2yymkwpue.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2hpvbjwwc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqrgjjbv.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gt2zakowrev.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gt2liqfbwmo.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2vkiqmgzd.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2wypqrxqf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rtatltpn.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2zgesioed.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2krwouuhx.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2hegdoyex.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2btkvkdtr.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2zbakabxa.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gt2hmkminrl.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2qkqhalho.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2xtdfkbaa.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjomppys.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2zqpcjybp.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2fuebhavr.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjsgkbpd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2qwzzyqjd.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2kdpjznuw.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gt2qeaaskco.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gt2msbgcxaz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gt2xuekwelf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gt2dzmtkmdx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgjnxklf.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gt2hdttkqfu.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hphwjrxq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2rhsjdakw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqifcayk.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gt2gzeltvzi.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpaztpyz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkqjjftc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gt2qslopqqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gt2ryuifsbg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2tuoefsxe.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqqrwksu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2szeegtcg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gt2yzmqbeko.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2uecmfoma.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gt2lmdcxcqt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2rshqyfdf.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2zhttlbxi.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2yjpmggiq.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2czpzgdds.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gt2duqmuxig.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2mhsemdas.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2moucjjfh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2pfgqwlbl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgopkgkx.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2ownyetvs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yosjqrmh.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gt2ifefwjwd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2vhynwqbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cctdqyia.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2izhtvbce.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2ytmqojog.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gt2rgptxxkl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gt2vyapwyif.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2mjjgjbmk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2sarvtqoj.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gt2nzhyxdde.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2nlvzuysk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2apbiohqy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2vhpwslxq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2gaykzncx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2rpmoruho.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2jpzfeaah.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gt2rflawuxr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2hfailgmc.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2eerytelm.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2yycjwtfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2vfgmsilv.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2htvrldxu.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2szowwfgb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2mggwprka.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gt2pflftlqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivnmujqb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2ukjfoaln.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gt2dbchpfsd.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddycvdpm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2ifoomjbn.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2amxlbyoa.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2nbtsoboj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2tuwpmzxx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gt2hfzssdwh.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gt2qcxcziaj.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gt2uqqmdgio.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2kzrpiwhx.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gt2pugpnywh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gt2onjmmhev.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gjdkwobs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2cbxfcczx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hfqzlfsc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gt2utxjfgst.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gt2tnmjcfvt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2tgwdvcqe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gt2kygzibjy.html


<!-- 参考信息 -->