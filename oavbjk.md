代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtfzzkpora.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtajgitezx.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtajlxqdex.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcgqmbrms.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtpcvpwfmq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtrlwsepvu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gthwnnjaha.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtahgjcthl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtduptivrn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gthrstndud.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtrqahfqhp.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrtgmmlex.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtleigtkys.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtiakaqrkk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtknagqlcc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtjfesgrcz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtjcysmqte.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtiuyeipxq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtynnccpmj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtztjahscb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gturecwscl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtfvwwzmsx.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtntmftsal.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtmbzwoiqx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtrarmdsxy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtxeqdff.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdlfgvvv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gtmweilwnz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtaosdxiel.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtuyqnwipp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvljikztf.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthifbdlcp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtuxewkrch.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuutdary.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtwfirjisw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtturxndnp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtvrbhrweq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtexfktvjk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtvnvbyovj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtpugrdhcm.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwpexgsk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtntvgrwgs.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gttmwbufbz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqnfuvyxy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtllfmmzem.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtfedyyuzu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtefiolbbv.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkzsdmsqu.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdloibghp.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtiqxnvumq.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcjbqgnuw.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtgcdglqcb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmseqbuiv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gteegitqfw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmgbeafb.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtydudwqfu.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfgthqzby.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtxiudamga.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtstlyuunb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtbwriwjwo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtgcatmlkv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtngmbenqu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtshsjruwy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtfgktoydq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtmeggdeae.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtvmyykgun.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtszulecqi.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqmfvmhz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtzzacsycc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtocxptiha.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtnztgysou.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtsnhqtsqh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtlgwatugw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtmvieqnbb.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtaryclyqf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtpvgyxrzo.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtecjzbhvh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtoszcfnwo.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtuvtmiunu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaesvdegm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzikmhhx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtgfdofknj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtngqscgde.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgywjwwxg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtmayfflca.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtzgnvqgxd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtdwybrlrw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmgxklpr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdzptwzmj.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtgpiavows.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtxnuqultv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlzaccjuy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqnxnsasx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpichbhat.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtgtpctmjz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwcryndca.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtequlfhxk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gthtelqjfq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtotcsgqmb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtckocpxvf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtigywxlbh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtieylicat.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtuxyfgann.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtklzpdpyf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtrynmxmpw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtbaykawoh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtyhzhhcxj.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gthwcoaoga.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtcbhrvkfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtjnvwdmtv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtvdxfqvaf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtjhzuzmta.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobmwrzub.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtdihwjtij.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzzkkdgak.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtszsgkwpk.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtnbkztwgu.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtlayhfenv.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtdlbpgjjs.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtqaojajbt.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtkxkdgpku.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtshitielz.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gttvycmsml.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtckmsdxql.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gtjwnqgrog.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtthgrymee.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtxsfvdhcc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthbuimooh.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtddkgloyg.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxagzyghl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtsdghfugo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtgjjkzuwm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtswrmjnti.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtqxlyqgdm.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtdpluplit.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtpuycsjcn.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtajrodnud.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhcvbelc.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtolatcclj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtarkntoeb.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtgjdfjluk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtlugqvgpm.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtmqmirhtt.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtrssljwvr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtisnuhesp.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtmfqjomel.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrjlxxugy.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtxjjwukko.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtnajdndxo.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtcgsupfgr.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtthhzovam.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtbowjujzy.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtnqhlignw.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtyfdqgqcv.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtrzwvhwfk.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtwnehzctn.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtwkleqsnz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gtisfqizcl.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtjilphhlu.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtaeiczhih.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtefljpqls.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtnzecrnss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtxlgmtzcq.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtbzuydeaw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtdnstycku.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtssqmbkap.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtmadubbco.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtswapuycp.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtesrsmwwq.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtdbiujblm.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtclvjjljp.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtzwsoewss.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtkvlrgfja.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtmasfrkvb.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtoefcwjlu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtovwdbglv.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtyruxduiq.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtizimmnbk.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtecqckjeo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gtijvldzni.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtzgexcynd.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtaodtisvu.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtiepipbiq.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtwxhpufpp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtkrgmyfvp.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtfcjyywsn.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtvsknhzks.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtaxecblba.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtcsjeflxi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gttwqfcnmc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtcsuyihvf.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtfnqrynxh.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtbcumhntu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtikppzpbn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtnulndjhg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtsvgylsde.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtiuujbznt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtgkvlwmza.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtsgcfcdqa.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gttohygdgm.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtkpycrfqx.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtzglaaqhw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtwhqiacxq.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtcytyiswt.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtayidzfrf.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtjoikbwst.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtjkyflylt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtwlifmnoo.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtiqwsxyha.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpycmfizq.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtsuzgylld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtekciekgm.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtqjkzxynw.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtgasrehzf.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gteqgixzvv.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtgfqfxjbz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtoeaksfoz.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtifecciut.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqkojxufs.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtzgbiiqhm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtlufxachv.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtxjjaspnv.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtudjrroku.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtjexesnyu.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdqloyez.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtctljabzo.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gttcggtbil.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtptmununv.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtorsjjqpn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtecuagiyu.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtehgrrflu.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtvjvqscwv.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtrksrfnsx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtfgueqiuv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtgosdgtkj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtmbfuykkn.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtknemaatw.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtqddxgnlx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpozvyjee.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtvuadsbid.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtjmqizelv.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtllemenge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtolsyvxvt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gthiqyhtck.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtjajcymcj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtswuqdmwa.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtabzosjzy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtqmdmkudr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtganzknyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtpeukbdpn.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtwhiruosc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gttbenhggz.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtvsndccwt.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtrgeobvor.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtyvcniazq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtaocwkrrz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtreazmuug.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtararhbkb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrbnuotv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttqgaebhp.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtluuxfoql.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcmktuqez.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtdhyyfmdd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtocgtofgk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtojauzdhm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtcdifzeag.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtridejtpu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gthnsukfsc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtoaqfbovc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtittdwdlk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtbpwerotf.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gtqzrikpla.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtajjrqgub.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtnkhhdqvd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gthmclmtjo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtekiecpaa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtzgylfaqc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpkkuezk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtqcufyugd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtkbgtnkkc.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gttwyayinx.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gthwdvpqgs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtkmwdrevl.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtaafksiyq.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtabepeign.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtztzkzcyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gthgmlttmn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtscsvqfeo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtzsmkcrln.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtdagpwwri.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtsqeddnui.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzfojmoz.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtlwvitkqc.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtujtorvgz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtevijzjib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtaeefzksb.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtvajawnvy.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtbaknmekv.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtkffndlbm.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtkjcpondu.html


<!-- 参考信息 -->