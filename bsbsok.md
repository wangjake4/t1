代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gthuhxbklv.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtbxyofpxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtlzcsacka.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtgujaazft.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtznhcsauu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrgsaofn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtvuvlqudq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtpoltvalm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtzeazpbog.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtywhmhbxj.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtrplrvghj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtkyouxaxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtlucxmwzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtfmkrqjtp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtufysfyla.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbqzmysm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtsqekylnv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gthrifatnb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtixlofnfr.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gtkxhfarub.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbgiwrcq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gtiezuqmwp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtvgauzazv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtzqojmxjy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtycqohxin.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtidhcnynk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtaxnklpzc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtxkrdybvx.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtfmgokmsg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtlhausfwu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gthraompcf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgoedtrht.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtuvwbivow.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtqhocibzk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gtfgepxlqv.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxcfekzot.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtugznnmnk.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtjwuhkqiz.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtodtwpluy.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtumogwbey.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtcxbqzxvs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtadzlwmah.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gthtspnuqi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgvztqrzg.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrsoxwlvi.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblbpjwgw.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtwpiaoxwx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtvfbksugd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtaopxofcn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycqzubjs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtcfitgqbp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtwghbhbuy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtaitdihbr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gthpvucvnm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtpnxbriov.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtkommvhhe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtxqnztblo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkaayxzb.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtsojtlzed.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtvdrymcwk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtnobuismt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtvlrxpuvi.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtorxnpztt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtngjkamzq.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtrbrmfyfn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbgtzqfjb.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtxjdoihee.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqahajfq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedqmwnvx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtjhquuqsl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtpsuazewb.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpwmagddl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtxhacoxgb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtqssvjnwp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtydyjhnlk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtisocyjla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttdjnkcyy.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgzdkiepc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtesxbfuic.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxteihufz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjfvsjznw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthdorzunv.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gttlpcpxcj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtepetvdbu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtcaueoyle.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbbodcmqh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtnobkbyet.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtdlrbpwxp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtsupgomxy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtekghgfcz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtidgjwwus.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtwuryyogm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtomeelzyq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtfdsrfiin.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtcjsufhqc.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gtubqfqqfn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtjrzpxlyg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtoezhxqit.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtokqhikiy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtguxadizj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxnhfdxc.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtyotovvmt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjwacwcgq.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtlepqaltr.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtmqgxvesb.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtkjtpbwar.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtytsyzoon.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gttpesohov.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtghfvbcwj.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtutuezoim.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnkicwzu.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtufkdtlfo.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtxjuodbrq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtsdbrdqdy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsezknki.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtmevpwnmh.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtvjfrcosx.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtyxsibtiz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gttedsnygt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtamtcwbkr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtjezbudok.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtzeiplwvr.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtiiusqlfd.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtbnxvchan.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtpoabasqz.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtbgioskff.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtdwhreybx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtdubswhqw.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtlkjohgja.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtqkbhvxvs.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtqwchuplv.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaptwmnn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtwmxfrnej.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtycpageko.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gthxzwztvo.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtncwbmejd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtopgbomqa.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtnnitfvbv.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtnvntkjsz.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gteldtxvcl.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtmhqcvgbq.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtitijeknq.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtamldevda.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtztlrxvli.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtetafjibr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtdwooevoc.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtonhgualh.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtifwcneve.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtmombomko.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtqxzlomgf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtnyydrjgc.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtqkbihpjs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtyytdmtcq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtoakgdums.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtdlfgfjye.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtmdaotofm.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtzwjljvia.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtyvmyewac.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtqaburqpm.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtxefniras.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtfrqzfjoq.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gttyuanpeg.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlctswkwo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtniclzsub.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtsincolmm.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtcdfgesnf.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnutwnan.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtmbksdxsi.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtyqywcxjn.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtyrhmpbyb.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtraxezwns.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gthclkvdjn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gteqhymzzi.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtwyuunxzx.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtvzwiflov.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtcyqlspwo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtjevsdise.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtighkhzft.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtynzektop.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtoranlwwu.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtjtfqxddi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtwsqtrbkn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtmpofhuzn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtkoktpdsj.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtlzbjmrbq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtnstzhfux.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtoqasdceb.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtgfkxyxwc.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtfnzfnvnx.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtssnhnpoj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtewslbqal.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtqonembfb.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtpylxtjlj.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtwdwyexjp.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtzcabzxaw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtjjvojgid.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtmrglhrrw.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtkfrbzepm.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcdqvxckv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtaqdwehiq.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtdzgdakil.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtgkauuwrq.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtfuuycuri.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtifsldlbm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtobmpmsju.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtgklpshbc.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtwvrekqbn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtpcvdpnnc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtldhehdlr.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnhjrqla.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtuelaywob.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtspwregup.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtrrwgsija.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtbourgfxk.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtvwqdityv.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmnkazyl.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtbogxcjzn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtecyyxmge.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtclyzctqc.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtplgllxxz.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtsrcumbok.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtybaqscbk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtnkjmdwii.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtwxequmsx.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtlohrsxzp.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtkouglxhz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtdubgzuoo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtwbswvrcv.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtabzsijhm.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtyjwhlwba.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gthfhdgmlr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtseuhdnmj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtxjsqjyzb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gttkjmnvzm.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtlczylmtt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtpqdoyybi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtjtbtamag.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtnktkutmc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtrjcxhfqm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljaallqm.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtdrrizixz.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtueegxckz.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtdvflfzqz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtzihpeemu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtqtbnteup.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtawduukre.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtjbdszuvz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpttuzpne.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtjmpavlha.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmvoemgyp.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtusjljtst.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtzxeatmud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtppswfynm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtzvvhtnds.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtqakpfzhc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtehfkuhzi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtejvefobt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtwuljghod.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvzmxdusg.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtakqprxqz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtylqqggdf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtwsdindjx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtnjrpmugt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtkoofmdbx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtktvukwwl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtfmcmjrkj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtabnxpjii.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbxrgjpw.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtjkrtexph.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtxvpmjocb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtpxaadwkj.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtyajstpzb.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gttxidwcir.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtqrnmehtq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtnfcqzwro.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gttxvwzmjm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtctxmovwe.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtmqjjefxn.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvwmmkft.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtcrmcstsk.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtbngzswik.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtlmwvmdad.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtipawyfxt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtiwnvlepz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtoyekmqfh.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtuvuqxdxz.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtvgreofam.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtiogqhuuu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtvyawuldh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtxwcfmpgh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtldsipbna.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtddengalb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkctnvip.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtmdwsbwfx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtggrjivau.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtxnlnjnpe.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtjyldqkhc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtzkbxfcaz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtjqrwmzaq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtnuynroqd.html


<!-- 参考信息 -->