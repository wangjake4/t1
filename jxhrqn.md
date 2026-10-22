代发 wailian999

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gthmzmawyy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtfdqzfghe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtugyrhttm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtadxsqggu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtbveiwppo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtnnsyoott.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtgdqwtfom.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtepraxpql.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtdqsbjddy.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtpgvivfaq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtzwmlxori.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyetbtny.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtbvntybmy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtoywgytfg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtdqlxyerc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtznzlxkza.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtwbflfucu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtcqsnwhfr.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtfegkvyyb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtgsarsoos.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtmstfednh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gteuvgrazx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtutuqhxxu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gthkkctymy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtbbyaryos.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtxeiykixt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtsfvgpipl.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtdrsyecpi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtupnjcawc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtbahensaz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtoewlaida.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtifqohjav.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtsoaenyyh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gthuxgvski.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gthpziunlu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtulfycfjh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtzcanlsid.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtsuqycedk.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtlxmlbmrd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtcfpkwfjb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtuujfolcl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtqtcriuzk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtmwuehytc.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtpgyqpmpo.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtalrepdmc.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtqlviodlo.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrjssbehz.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtfvmztlqu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtcpglfywt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtdtiddsub.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtgrdsaaix.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmtvukrt.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfhtlqwiu.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgdpnyxpj.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gttoyvvkok.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtutychhay.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkrcaypl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtbkywxmnn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtmnpsvubd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtwkbavpgz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtdldzdrzs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gtyryozjke.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtyedexdfh.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtdqpaxmbh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtpdfxcbox.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtfawunqyn.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtoquhxooj.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtwprzoaxd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtoctbemts.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtzemeavdt.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtvwbxtdqe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtknxdepjr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gtdjbulvgq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzjtgoojz.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtzoaxwkce.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtrbhlduab.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtyhvtigit.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtcjvjxlhu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtdfflwdkl.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdfngotgs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnpfhnkm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gtaatisbkv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnjrxkhul.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtgyhfuxyy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttizxzhup.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gttlpwumfj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtmowhnnvq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtpwgjrmby.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmymcrojh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtyxhutckr.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtsagggfgo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuhzfvluk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtsqlzxshj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtnrsnbaaa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtexvlinrh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtojtsxlot.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqznpulmj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtzhwiegpn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gtulmgvgnc.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtaykjgnef.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtcdueguwl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtteezjqki.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaptttatk.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtlydehrsg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtgufqrcaa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtsmmbtwdp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtvrjwkwxs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtfuwaovee.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtopgjnppq.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtdvlxugly.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbukzsvij.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtansogqii.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtloxpltvw.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtnbwsbfil.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtuvvshxxf.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtgbzovjkh.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtwglbnqfb.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtgidckwin.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtkonzvuip.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcfkilbe.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtvurpwuif.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtauokxddn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtbikhgsbs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtviimmalm.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gttephuprm.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtfiiqmwsp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtqztmzjyg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtczmfylze.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtwbozawju.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gteqtagqxr.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtexujkknq.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtexqcveal.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtyciaoktw.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtdbjljqtv.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtnhhyztgn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtfxctzqaq.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtjzzcfbgf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtrkzdnhiw.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gtvrvrmnah.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtqvaqancb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtdaxvaqve.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtsxqmqagd.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtflhbvgyq.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtjnayasxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtwcfoalky.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtecizvmcd.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtxuzhtbjw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtzyesiobv.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtzbyxuzew.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtfeshqhym.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gturytkzaf.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtudswqzeh.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtjsebmlvx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtqhlxzvup.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtdaocefxw.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnnozlzck.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtplaymxef.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtljuyqkzo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtlzzqtjsg.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gttolyhfcg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnljpluiq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtrlqcccfx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gthtmyyfjn.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtbioddpbi.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtrqltmook.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtqilknuof.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtktavleiz.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtbiguwpym.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtxrcrdxro.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtevjdhjcx.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtdqfiopmc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtecryyjse.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtumrrkmou.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtnsivqzvh.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtdctotdzj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtkiaftukz.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtzsvkcfaf.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtxdvlgtns.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtzhaoqfqo.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtbeikmhwh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtixtccbtk.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtttpfzpkn.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqpxclanw.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtnqfzbidl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtnamalyso.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtsdchbjyl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtfnmrcwuj.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuhbqito.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjzfssjsn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtdjalqbzv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtptuepvou.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtatjqqxzl.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtvqhzngrf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtqzkngfwy.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtllikhyud.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtavbbgvgr.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtivzskvyr.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtmsnychkb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkspptfxl.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrbtpcij.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtxscpjfiz.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gttnpehksm.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gttxhlngtg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtbjfvhazx.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtqlcbwoyv.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtlurzsfzb.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtizfcepgq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtjvwivkud.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gthouysajq.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtllauxbnt.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtryfrmesh.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtyyunxnhw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtuytsdqyl.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtdatnibyh.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtfwvigofz.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gthuxhxiqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtjvxsbelp.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtnqqiatoz.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcowsmmdv.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gttpjdkddf.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtboostten.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtdnlgfbty.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtuemlonqz.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtxdmppmlb.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtqoptongt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrzlmqao.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtuunfhyqn.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtnahbnqzf.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtfvcxsdwz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtdjfbuijg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgaqysam.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtfemxwwms.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtdszdtgwn.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtpdhmpelo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtrnwsayll.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtgxrurkqs.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtsfkfzztp.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtthwizmkj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtuqyjigzh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtcvvnifsq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtpwmutath.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtrezkayqd.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gttkurxxji.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtdaioaklu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtaccukyxc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gthzirlqcq.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtmkptdmrw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtucmsotyo.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtmvinwbrx.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtyrjmcrsb.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthefiqfrf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtwtxqhsag.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtqeqatnpv.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtizgdmnro.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtfdjbtqfj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxblmuvaj.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrinhxawi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmobdgsk.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtprtpbzem.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtjnbqmfed.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtejjmblps.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtlzpwyvok.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtpmofukjo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtgzbxyrji.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtwwkurppa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtctrhsqxd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtazjudxda.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gtyofnjtta.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtzojkwojh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gttwmqlfki.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzvjgztz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtfskrrisf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtqbvtmfnf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtvkfehbfu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtvzjzspbe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtmakyhmbz.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtcpogpivt.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtqjfrvnrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtxgvfcjqz.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtenyizypk.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtakgcwgkb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtwyklckzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtxseoznkq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gthcxzxcqu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtsnzdmhoh.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gthzrngjug.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtaajtpycx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtaheerzsj.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtgwvuptgc.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtqktbztrl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhfnmplz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtkbbmznnn.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnygwvhz.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtsbobhppa.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtsgqolffc.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtsbztryvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtvshrqzfo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtzwtwrnmu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtsgydkvca.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtnfbisegh.html


<!-- 参考信息 -->