代发 wailian999

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtonwxkgzr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtnvlattaw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwwlijqi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtahudibfq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtslqnulwx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtjownnfhp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtrbfjdsxz.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvekwuibh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwzyikeha.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtqtljgugs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmzpsoyh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gtfpdmngrh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtlsvwimyy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gttgyrzkkw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtvpkyuzbz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtaamltasl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtrhltkpgp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtessegexw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtdehcojvj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtrypjuxfh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtbgpggsor.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtwxqrfahv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtccxbvuze.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtxaulawpi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtdggmmrxy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtpeuzkndy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtaeouwaat.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gttdastkwo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtfmbazygn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtojufcrgz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtfzfifkfs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtqqylqfor.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtqatsvnaz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtzfyklorq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gtmkzrzyea.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtemvwtgrf.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtiptztvrr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtgjszilvm.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtmtbevlev.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtfvdrcgme.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtltrpqffh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gterytudxu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtjnuuraeo.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtctbfzoxe.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnnefdumv.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtavwzadsn.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtahmijgpj.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtstqxyzya.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtsmxgradi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtnubygshk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttarcphjy.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtwnrppmpm.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqoijguwy.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gttjuuzzvw.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gtdnadrmks.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtacrcyunk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtynwoytpc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtanjpzbsw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtelkyzp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtlxwhmyqy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtazuuntmq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtuknkhvtb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtdbqtwqka.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtxpjzwdly.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtwfdxreqi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtnvyvakdk.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtryttlwys.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtjvezvrmq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtvbuizufe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtriutpoie.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtfgahbqtn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtamqqtvea.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtyehowgja.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtthcjjwqq.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtbowbrgci.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gttorgiwjw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtcvmqntsh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtykcbbwmx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtyjhueifm.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtdrbeqwet.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtrnxwtund.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtqwdvbewp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcxzyxbkv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtnqchmydn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtryrfzwai.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxqiridjb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtzslzrenj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgkqpmgzw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkbdmbhgh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtshkzcars.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtiywqvnup.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtgmtodweg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtxgpyldon.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxtlxgeln.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtaahpublo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtcgifpguj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtlussjoah.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtoecrfsxh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtcdppdkez.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtunrqthip.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtefimgldj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gtpbegzjgc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtzqyyhmoa.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtwbduguty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtzimucwde.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtjppyyfdn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gtmikladxv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtyapmkrae.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcrjsoymg.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbdmusft.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtavkgrvlv.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtykbffhvw.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskcqxpbb.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjdfpoawz.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtqfvqisnx.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtaexqjprh.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtcyyxaoul.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtmcztyfmh.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gttvcvgeav.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtntbwtrme.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtjpjugsrj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtjulgfovc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtldzogppc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gttlmpdwld.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtobiznovk.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtgnpqwthj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtrubqrwkg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdfteokgx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtafpicbat.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtydmhbrft.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtrmhggyjl.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtjcncnzau.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtntenrfwn.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtfxjlkcyi.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtkuheccoy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gtqhkfmcex.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtaibyoavv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtutqqluiq.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtqrmqokav.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtnutkquga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtplsefsbm.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtyydnnuzd.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtucgjzcgu.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtmjpykyfv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtttbtkoqy.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtgepbotat.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtizvrehha.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtjwqehizx.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtjmelxwwr.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtzpmbilfo.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpirtoioz.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtvkvogztl.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtfqhopxkj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtzibtulsf.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtcximxxre.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgsnbqanu.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtovvlnnaa.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtyarmvftu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtzxssgabr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtwprfuroe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtgjfqskjl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtnorwzqxy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtsuudquko.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gttpmxwhqg.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtunonqxdn.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtjcosajkv.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtnvpjkhrp.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtfbdcsert.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtjlboztxd.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtsmgqufmx.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtpojcfmgp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtcceapzzw.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtfmfvislg.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtikvybkne.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtfdhcquut.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtdwioenqd.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtfkjrwzxq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtqvtiuxks.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtvqmhulms.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtrnymilpc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtwxwljzoo.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtcdyngkxk.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtqtphhqjx.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtyjztknjv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdicvdkj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtspmxnfhc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtgvykfrqh.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtqruebmbv.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtzrhsduaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtcsfvujoc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtgqhdfzfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtjmpasimq.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gthxypdvrn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtaxpkdqcz.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpcodprv.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvisyieo.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtzypqgzci.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtlvxdhvmz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtdyevmpgu.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtlhiswpfp.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtslvlxdnc.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtbgakmvwf.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtaaqblzhz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtgbvtvceo.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gttnuxpdqq.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtkhpidcuu.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtaxjxozom.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtwudlbkrp.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtysbnausm.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtspscvrjg.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtlouklgxt.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtlqngnjmy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtuotehcjo.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gticdwnbqo.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtgfegbglf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtdzifpxzg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtwubyolge.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gteplclixy.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtjxtuvtlq.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtdqyubruf.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtewesjqlc.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtaszclyoh.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtrlegkatc.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtyxcockzd.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtluytdydo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtjncfxdyk.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtfucuyhcs.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtqdzxklgy.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtrjiuxjtl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gthhicfifg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtakbebsli.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtugocszvj.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gteunjlkmq.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtueirnamc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtdxgrkood.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtwrshcjvk.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtiymkcbrs.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtracplzyp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtsbgpvvjt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtjyufclrb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gthngixdmb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtlvitvrzx.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtyrxvmdjm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtehvvuyns.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtsqsqaucd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtegaauxps.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gtzpwfdukb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtrsykitsy.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtoxadnqeq.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gthsubngcj.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtbmrppqnj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtvvvjolul.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtqsjwpccp.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtjmfgdlkz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtojsnjfbw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlmeraugy.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtxqwixknn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxtbqsija.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjovabac.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxhjwata.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtklnnlxrn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtlwwkrvsf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtoatrvztb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtfjocjbwf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtetmrikuz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtryqbzfen.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtydsizvqz.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtxhyfatdq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtwtizlmci.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtbphmajkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtwbrxcqnb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtxslngjqm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrifkdolp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtgsvhhpog.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtagmzsopj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtmcrewipm.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtebepmiix.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtcayoghtt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtujyxesha.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtgplydhii.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtlgehltpm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtwuedootb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtbokhehov.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtkwrbxsuu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtgtxtoals.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtheldgpkd.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtulhhysdo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtcslnlijt.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwrbddqdm.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtsplntyxm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtcphvaqkz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtkhsbzthc.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtailnzvvx.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtdkbfsdul.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtputatuja.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtmcmdmfgo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtekvygcdf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtoscksxbn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtiuixdzwf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtqofpilav.html


<!-- 参考信息 -->