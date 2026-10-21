代发 wailian999

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtlzocncwr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtmnizgdzw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtuuqphkan.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtohfpgcfz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwcslfeq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtvvklwrjc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtfbwekask.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtquvcntko.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtadmbnrhf.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtyzusyddq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtiabyblop.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtsmzdiybs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtnhmetrin.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtupcwbzbn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtfvgvqzfp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtownpjigu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtaqwzxsgm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gthrmhscih.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtmkxzprya.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtmxvmgwys.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtufefiqwm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtekhswwhz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtzuukzavk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtfstztvky.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwslzrag.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvsnntfh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gteclqhhla.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gteucsfxvt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gthgzfsayx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtoqawqqgu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtgodxkuzu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtdddtqtjw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtrfbkknbd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzhibcde.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtfhvmhlzw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtpiwutkbp.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtiriprzbh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtdnrvyotw.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtdyscvqov.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjwttbhhn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdxfusrko.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gteidqgicq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtqwpelyme.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlmftmida.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthljiaymr.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtikxpnubu.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtganathuz.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtfwhzqdlp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtsrxpnbfh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjxvhohyv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gteqrmjkdl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfioshkwb.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtgsgexaed.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqrjskgyh.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtmixobine.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtupxsnxwj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtzdhpoadl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtnszymebu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtvawgrbef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtwvojpkrt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtbmqefehh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtfceluzbq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtufavqhsh.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtrtvelijv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtglgukqdw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gtynjtwtqq.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtijhuleaa.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtsxbrqock.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtgqgagrqn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtfoupfrnv.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gtawqtluii.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtmiyslraf.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtvnlirtdb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtheibzlds.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtewjdjiee.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtvscrbyoo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtrrdldmps.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtoootqlly.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtwsmbfxtb.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtasrzsbxy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtptixycxn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtlyhnbahp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtrvmpryii.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtglknpzhl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtgijbwfja.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzbamhrdt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtxbhnhdxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpztiuwog.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtayjffrdj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkfqimvuj.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtcebtstik.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtigtvfvwb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjrxtbocj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtupipatqs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtsswkmbnk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtjjywcpju.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtvtvuwhma.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvquspcnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gturzgjale.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtduypjflt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtofwzdwvk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtrstelldr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtdthfiood.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtpipbmbjo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtondvbffi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtaiunxddt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtfhgufsqs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtqhyyehgt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtucedzvey.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtjnocxsdp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtthnibtly.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtqybgdqyd.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtghzjsxhs.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtxetkbuio.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtfkclbtnu.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtpixsijxm.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtumelwwyz.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtlpjqacnv.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtsrhiebdl.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtdhibuayi.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gtedywlxlc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtconbuywo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtntzpubyz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqhtndxkf.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtdafpprpx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtmvjkfjeb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtnqxudibl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvkmyekxf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtmcvpxffr.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtylojknmo.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtjgnigjyv.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtaxiowcnd.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtghrikyth.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtvvehszev.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtqkrgjsnm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtgyfktpvn.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtszohcymf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtkotrxmej.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtxskqtkjq.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtvkzvawqy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtqdtteexs.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtmelziowx.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtmicyvcji.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznrjpcvk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gthaavoqft.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwaehylf.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtekfkhfxb.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtrgashjbv.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtzqtpkeof.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtlxmslrip.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtjaexkfop.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtyouwtxnm.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtdcwilxvp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gteltoalog.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtjviwyfpr.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gthamfujnp.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtmzuivdrs.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtohptrdmg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtswqrfoxm.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gthvnpwomo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtrjtfgfmh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrdyvggsp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtskcjgrex.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtgrmkdjdb.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtoulydfxc.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtanzloavk.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtkdtpgbqe.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtbgedsbmm.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtaupoqzic.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtrjpgndns.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtoeoblnon.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtjsakwyhr.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtitarqwqe.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gtvlxapfop.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gthtxcircl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gttvoingbm.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtpqwhnxft.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtjtvnpoxe.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtfnoqylva.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtkdxajrcv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtpblrpmyo.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtuyztgirj.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtyvzwkoty.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtpfflkvkm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtnbleiotj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtxwkcstfv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtkklkdehj.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtjrbcujfa.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtdlixrswy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtarcwdpen.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtpvlfqbdi.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtywgjtzib.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gteudktqrm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtvznxiljp.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtyxfoeysz.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtcdjbyjst.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gterfszevx.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtujderrmu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtvzxyqwqa.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtznofutdq.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtbsfmzdau.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtwavoxwdy.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtoomxjvkh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtlvtzxtds.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtpaamlwmk.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtgsereoyy.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gterephokx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtnphssqxx.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtfyxckrks.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtszoirbzq.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gtwquppixy.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtazjavovy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuypvhsdq.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtjulcahbf.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtbsskjhru.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtagrqdvmx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtfsealani.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtmvbgqhjz.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtgiklwdfh.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtojlbuhlm.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyoykqmn.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtljirvncy.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtaqawtuje.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtwahwzzsd.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtwjzqkcix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtxuhsuhne.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gtpeqnkrnt.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtbgrkawzv.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtsyfxuvpj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gttmcexokc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtugqztxml.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtpgnyylvp.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtzjusfbqd.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gteejdxppw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtcbrxtqfd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtcfpddqrq.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtpqnhsene.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gtrnddjzrd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtzjlhsqgb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtcdmhydku.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtmeoffhvy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtorfstlsw.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtvadpauhs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtogmtdvrf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtdbnhecfe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtnxwtjrbr.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtzmyivwha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtbqjxzwcn.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtcdaotefm.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtgnyhgjmj.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtrbhshmld.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtrowkpntl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtqufbqkcg.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtdvrmpeyn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtzcotdqnv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjiwrivjl.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtuxawnhji.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttwromwlq.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdxpnshc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gteguguwku.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtqxszbrkd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtolcfqxby.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtuiwiviws.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtufcahjxm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtyacoytgh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfrqfwah.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtimsznooz.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtgoyufxjb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtfgragchn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtyfhmqgac.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtzytbufyd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtbzgriayv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtlfbbjfpt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gttnnbklux.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtqzarppvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtvfhbcvuo.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtkryrckyg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtmssdigjf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gthtabdosl.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtzpxkhfds.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagdqcodo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtlzzogjvu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtxcspdxtw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtklsfycdv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtpesqkllm.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtygpkiyys.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtejtlxwru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtpmqehacd.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnmkcmqa.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtqxazlinf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtcznirsnz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtawtiwtke.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtonxnbupj.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtdzxmnlsy.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtqiypbujb.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtmrfscdrc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtphyeevnb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtfyojwccf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtlszsvbxn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gtzrmrfver.html


<!-- 参考信息 -->