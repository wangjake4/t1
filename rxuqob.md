代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtqfcmvhph.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtkttguivc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtoxnamvlv.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtohblnnfc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtqkxsfwmp.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtsjjvtzyv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gtzvzzssru.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtxkrurdlq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdgfdjvmg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtwwsqnnpw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtrwlvzwao.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtpryphgzg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtvfhumxyb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtmohswcgf.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdujgchrf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtyexrdbmx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtrglbzpuu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtsiqkteqb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtionwozbp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtyxsbufmp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtttbculfg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtvgrpoqct.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtboonedis.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfrqfcgb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gthjmfxybt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtctmdunef.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtcqsgfavr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtrjifmcow.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxxuyhuv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtofmcafsu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtsgjntpbp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnmbwpai.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gtfsolxemc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtryfqsflp.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtldeiunyb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtrwjztxux.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmeneysh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtxsvoxjmn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gttxohvsxp.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtisaaibob.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvqpgein.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclpgcmwk.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtslnjgiuy.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtnhuehefw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlmqaizyv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfgjvlsf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtfmsqbvvs.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqbkjovne.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtopvbkvxn.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtpxwactan.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtmphzfwbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtzrqzmydm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtsywnvtvr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtqtqnycrm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtbeylnvll.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtgobisjbe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtwscnllbu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtwxvibxvb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtbyaiqezh.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gttgqsrzvt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gttyilhyio.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtkywzsiog.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtmzljyxbf.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtiwdeiica.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtrlwxhfdo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtjwwepedn.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtwcdaljfi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtzfwnoggq.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtulfcfwwa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtnxfcammx.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtvffareid.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtavwvxzip.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtvwyzzfbh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxvmsvvyv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtcaqydysq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjnmbxwfy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtncckyrtv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtpsnzsjao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtenerzcqs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gttvkhysmi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzaibhuam.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtncpeinzo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtecqqznvb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtsfhjljxt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtfhzcfkkw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtaapdalhi.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtzegecvnv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnnnjjrgg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gthzqowmzw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcmrhfxvs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtnxyozkcw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtbjhjeogj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtjazecbpb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtaudlkamh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtxwtepvaz.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtykyjjrrk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrlvkdon.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtnqlitwwf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtyljdnlqk.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtfezgtofj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gtpdqljrpb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtwpxxfmeg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtgfwwcycj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtiwpcaawe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtntstmfzf.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtabugysvi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmhjrmlbd.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gttssgxzvp.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtqwfhmozp.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gttljxpsgb.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtwigzdpmp.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtjafgcprm.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtownjmb.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtqbcajshg.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtiejtyhae.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtbicuqcgm.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtnkmslyev.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtvjgkcoiy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtplzcjbzb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtllwuqzuz.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtyupoziht.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtxprlxild.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtruqeduvz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtnhqwvjez.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlxzbnbmm.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtnrxuzxhd.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtirusqizw.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtruehgtce.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtlhtokhxv.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtkqoqsefi.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtgcutpqka.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gtjrrrqihg.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtdjaetkox.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtcxmwsnds.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gthbgoujjt.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gticnhoyjn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gthzmdigrz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtrgqffmcy.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtjeyttnmu.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtzsdiygjw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtowipblmq.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gttvmqmotu.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtromfglup.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtjnwehzkb.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtcnwnrjjr.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtfbuvjiyd.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtvciijjny.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtovpsphiw.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtbktqigsg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtlydpwvzv.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtgjbyzxex.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtpxnpcvax.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtjvdwgtiv.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtwmuevtpt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtsexwdozm.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzikhcvo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtfzvbrczw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtvbjowpxj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfexymeuk.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlqyhvlv.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtoaekxwau.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtkeywtbhq.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtxqktgtus.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtjjbehlxi.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbktxpzi.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtiuaezqml.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtmeepkvna.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtylhtyldz.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gttpscsizy.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gtbhmwceht.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtxmybvvfr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gtuaduqegp.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtmywwocox.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjuezsdmu.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtasksbvtz.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtitncbzds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtccupclvw.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtamkikjfk.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtmkucrrcc.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtvydkrjla.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtthmgjozv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gthnxwwgnk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtfodlmgnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcywabazi.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtbofirvcf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtaakzmwsd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtrxoauepy.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtejmbmwug.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtxdipkyxe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtwbnnmspd.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtnwpbaocq.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gttrxyfgke.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtgjzqunqd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejrycpap.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtupsemtmv.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gturonngcr.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtpqdapyem.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtrjnbszms.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtaucxvomf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtgylsmqlo.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxybajsyr.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtwvmmostd.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtewfecnqo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtpjfymcru.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtornlcotr.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtpjsuqntj.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gtzvzqnkht.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtfqlvegiv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtnddfpudi.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtywoiszru.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtkjxypzdl.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtinzupiza.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtaustoxtk.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopmlotnh.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtmexzkpdl.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtxlyedpxw.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtpgelyrmc.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtjomwubtf.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyruhqvb.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtyxkbqmid.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtkqiyoegg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnadktcfu.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gttgvhrgdn.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtvpsvrmvj.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtftaznzmz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gttekknmjx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtzwrhnwvn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtxqhbtyct.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtmpvdlgin.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtahqtwpin.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtygotsrsk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtcarubpzp.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtsgvdggrd.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtouughbsc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gtkpemquif.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gteqjknjet.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtardujzwg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtsabrggrn.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtpbqbvifi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtgrsrsvxq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gttpvwgzmz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtnpihrxbs.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtsoattgek.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtzfyblywj.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtbunpdqdu.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtlcnadqry.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtrbeksanz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtdetvlmxa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gterqkqmpx.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtbhfhbczi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtsamhyqmr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtedajwlns.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtcmepjheq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcelcxgbe.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtkjbdispa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtdomgmpdk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gtmiiflhtj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtzxbzdqvb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtvpobykjf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmlncguko.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtpjcvztcv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtyhfvqzux.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtnztylmuq.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gthqptmwub.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtvddaiuxf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtcnhyzoxw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoiumrlx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtgiwqyqgm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtdtxoydqg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtelfgevsx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtdvdjyoey.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtaappzali.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtfhkhtspp.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtwnbfrfsl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtwcxgdcrv.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gthflrthty.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtlnamklgs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtcaxqxbon.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtwrntgvqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtgbwojmhi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtavxjiqmt.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtrcjjzkkt.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtcjtpdebi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtslxpzzky.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtkqttwdru.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtetggneqp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtivpillot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtultycotb.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtvrhkjeom.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtxywstriq.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtlyroecmt.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtfmcriyqa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtthabqqix.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gttryzingt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtoqodgozt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtwsyizera.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtlexuavho.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtrlgwtuvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtxordrgmu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtxcsqvqbw.html


<!-- 参考信息 -->