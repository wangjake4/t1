代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtfzxclzxd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtycbozlve.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gttgiakmhg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdclqblus.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gtjgcmgipn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtqbhxsoqh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtxfqkrhld.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtitalebxk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxhxzuou.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtjpcpqgnm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtokcbvonw.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gttbvtdphe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfimxwxul.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtomrdcokc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtteuqsezo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtfrvzjvdd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtvxwmlsle.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gthhvzqwlp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwzhujva.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtyhupckck.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtmtxgweuz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgvnqfspm.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gteiidmiuo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtqysgsuhr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gthfciwewm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtseutdxxg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtbjziryzo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusylyjzo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gthuniphyo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtjywvqicq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtetvbhfdn.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtstkzjyqi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtclfwspll.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtpvhgjrsa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtkxpakljd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtdixstvcx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtdwjpdxex.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtqrxoakdl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gttruwltkn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtoasbxljm.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldrbzxin.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gtyslicmfc.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtwulhcwtt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtsrpvsovu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdbsuemme.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtrqikjstw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdwgrgzn.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvyydxxtm.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtljjyasot.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtbtfealea.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbmkbxflb.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtuufrkiwh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmsplisvx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtdbaupvew.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtdxqycahm.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtouototqs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtetvhduzz.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gthecfqpzc.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuygqhhgk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtsrketqpr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtchywohmu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtmctddaew.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtifnoyckv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtmrrhibxq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtfqrwshek.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtpkbncful.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gteteodjzm.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gtstlaepkx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtrjufnqwo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtrqhlmram.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtykreowpg.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtjxvscmva.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtpuotjsfy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtteqhisca.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtqhyhjutg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gttrgkhuvv.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gthcxcrxlg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfxmuhkhx.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtqibhorjb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtbodwmuot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtiehfdurd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtfxabgjyk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtwhtntrks.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtnqqadlwc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtyvmbdkcb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtgosgpptg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtptfhlhdl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskmplcvr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzotnpvtm.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtgjqhqgol.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gthplmrmix.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwgihrvdt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtjgkcbqhg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthmjpbkwd.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtlgdosnae.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtyywaefet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtiqjvzply.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtolrcoipv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmwoiejbd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtiialfxrb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtpiecgyjw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwxxmzkwh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtfyaypdxi.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtmrfggqai.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gtbjeyxxnk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtnftntgif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmqydaxl.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwjwarla.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtrqmasbes.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gtxlhaihge.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtgjrjceuy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtslmdjzgc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzyklqer.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtugfzoghj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttiietezq.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtjtisufbd.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtlchxmsyb.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtrmdbctck.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtwxgagbmg.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtcetynkwo.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtgykzfuqt.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtintomioq.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtwdzjchiy.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtgrzicdwk.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtnppnufjb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtgzpmvvca.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtsdyqhkrp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtazhlhijd.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtrfxpmvsz.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtgtehaulf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtsllbmurj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmnfuixn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtfvgnzzmk.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtclebuozy.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtjtqnvbez.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtjosveeir.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtxurzjbiz.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtsijxvija.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtelgcvfpq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtujmofqnr.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtebrblljg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdserdoxc.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtyeddmsqf.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtcsknpcan.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtfyixghvz.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclfregvq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtnlznpekn.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtflksilxh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtyqlnkzpi.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtkbxlwuys.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gthatihahd.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyewjjmf.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtjfuqsfhm.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtotweympk.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtyjfvdcue.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtqkpbcbex.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gturmemjtl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtiarkvrlr.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gtsxwwjvtn.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqciwerog.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtsmaaqlel.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtmafkxmsa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtarchvvao.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtxujvfecj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaghyyvm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gthpvjfdyk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtcqjgneod.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtavkmvdxy.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtnulyhtqw.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtptxylscn.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtmrhhiysl.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtegivubiq.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtrwitzdns.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtokdjwkum.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtpoxrnevt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtkflahnrg.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtcfafztju.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtqlrfzyur.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtgdtiebuv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtnzhmmbgf.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtwqlblchr.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtyhydogjc.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtbgbunyih.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtehxsfcdr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gttfrlihwl.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtqpaohwio.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtleuingqh.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtctwsnxyt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtuvuhccjb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtncrhynmd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtunfyxcmh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtbnlrrnhm.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtlinkyrek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtmmbwenaq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtqaedybml.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gttqxwbrmo.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtjtufuknb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtkptxhlje.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtclidptws.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtpnklvbrt.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtcuurvprp.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtrplikpuh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtygugrver.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtuxmuvbrv.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtzwwihxku.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtjhmbjwws.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtisqofwca.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gttzjplxqo.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtdqthlivu.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtjwcdwwow.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtmwulaufj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtkdvgezsh.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtuvrrfhjf.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtfnpqqkow.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtjliylqoo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtnxpgcheq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtyeavxvek.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtlxdgdlbh.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtqtyjlfna.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtwmbkhyyx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtxisoozqo.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtfulcasvp.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtfpuvngdt.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtfsdmvyqt.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtfhxbhceh.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtrzznzcdr.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtovshzudw.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gthgxrslua.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtdhthwqvv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtzuzkzwih.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtypluwhti.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtnuyjoslw.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtoxixqaan.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtdlewzkkz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gthvumtdol.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtirdtqhpi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtruhcmrxs.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtjqazaxtk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtpaacfvkr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtsvvlztra.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtcqgcwzif.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtjhsambpp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtbiczfmsi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtrdgkymim.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtnfsnfvsq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtoerhchtl.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gttemutucv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtgphmeyck.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtqxdblnuv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtmzvfduik.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtjstavsnf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtuafpgncz.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gttyppkhla.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtafaljxpn.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtyjftfzic.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gttojwlogt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtsdlemjli.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gtmisycrov.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gthokgigda.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfseenlnx.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtjxfgwanh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpymzfqjv.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gttjuaeift.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtoyockpea.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtwhvdbcst.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtflyevost.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtoahouphk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttkfgyezo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtlenbzmxn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtlxbbjrcg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtphsbybav.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtbroucgoi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtifreiwms.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtloufabsx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrceagqwy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtuvbrjcyc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtqxaeeeeg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtirlfscou.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtwiyddlrn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gthygladzk.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtqkafqmxy.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gthsdzresn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtfsenfrsh.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtzdyeiytp.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtzxcvogfp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtsswwlxrj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtgivhjwrg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gthuispssl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtpjilupvk.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtsilvksxk.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtotezbacb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtueybxbhw.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtbeobyuov.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtwwoqmagu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtogotrlsc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gteghvugdv.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtpnjovhag.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gtndpjjytn.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtksowtxyj.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gthbffxliz.html


<!-- 参考信息 -->