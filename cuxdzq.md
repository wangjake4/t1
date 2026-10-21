代发 wailian999

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtavndfvqk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtjvmdykxa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gteurxslga.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtjqffuheh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnyhzxiz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtzlnmfxib.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifgbdoof.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gtzthsalpa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtkwasynto.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtqhscvxpi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtektarhow.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtkmtmebmo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtohyvtiti.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtxglholbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqvordsr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtjlttpevr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtcdimomjw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtqxyegrwt.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtxoocpbrb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtmwlbzujk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtyqogjlmr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtcudwnctu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtelqsvlms.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gthxgxjpmu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtfbbnmfdl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gtgqxykckf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gthgbcvvmk.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtsfqcvhxe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrkuvsvo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtsgxwkwut.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtliysodru.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutkvjsfk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfrhtqol.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtshenynnt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtkuagijnp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtzjboumnk.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtxcflmdcv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtaldhjwot.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtceuoasbi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjptvjxzj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtmqoadsbg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtcbiketyu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtoaewixja.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgpgcyedb.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxbvxatfr.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtloavdkip.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtmschyzzw.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtcpqngqfz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtznyuvixq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjyuhvauc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwpscajq.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkopfrjfs.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdornylus.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtzjedvnck.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtybldzbuc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gttmtudroo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtgwaogmdt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtzhonrerd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gttmhktsbv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtxaondnlt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtmchwtgql.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtgtudiomb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtbgoxvrdv.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtzclyrqwd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtnguwpgzi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtvmhpsaee.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtsjsxlaii.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtcdoioolv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtfongwtgd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtjmubzfxo.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtawprwjfe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtubjkictf.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtghvybgki.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpkpikyfy.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtcnffcwrs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfsjrfyk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtottuzqqd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtyskudjms.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtgblfgzzf.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbqetaouc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtfincocch.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxztytvth.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtzsphmmof.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtswcczplu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtyqtyhvjd.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttwcfjxpa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtyizimowf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdhkxjgqb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtiptryxit.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtvuvxhqle.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtqmtvxrsf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtcvcvvggp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtpvilgfac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtxbwwcvci.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtjyprpawd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtfrxglrlv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtcozbxwlw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqjjgeohx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtihjgntxg.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtlmiyyskh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtobwjsrwo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeilmdsr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtsqjqcmbg.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtbupdrzgn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtjswtcbcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtllbritua.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtuecytlkn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtydokdbqs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwnmqfyuc.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtqutqkqmi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpdwrfhsw.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtmmpyzfzb.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gthkkwacec.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtzkrzlhba.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkkuombqm.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfsityfmj.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtsnbgfmxz.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtdwcnxgys.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gthmrhjgzy.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gttcqxbxgu.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzckekfpg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtwehvorac.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbuggzeha.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtdwwlaxuy.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtfucregoo.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbwhervv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gtdcmyvbrx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtbkehhqqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtjtvrfsin.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtwdynrifu.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtfyahimhh.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtsbixfueg.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gthaszurev.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtjluuptvl.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtancbdrxv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtdmeqwfjk.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtozdlgdnq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtqsydlkti.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtxdncoozh.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gturfavlgn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtkccgehlz.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtjbshsdnx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtvzctuqwm.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtoegleqvb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtwghdmgwa.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtpuwksixb.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtqytnjiig.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtoxhglxpj.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtikofzypc.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtonbmogtm.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gteiepykvl.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtuozvslnk.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtspnoyuyk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtdalsincv.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtupuhewpa.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gttqrelqov.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtseojuxbu.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtfuztxrtz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtqwsjgqzv.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtdtmcwnmn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtncxxttck.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfahukswc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtsvpphbzc.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtrdsmiuoe.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtymazqbnu.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtvkiawkkb.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtxgvrtirg.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtacdfdird.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtmyexgkha.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtmqpjxzkf.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtetlfrzxs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtgpjwwooy.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtesgccaku.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtlzkcjdqv.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtqkhvakni.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtfiaatama.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtiagortns.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtcymkhlzr.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtjjzdjgjg.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtehkicldq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtqufegfjx.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqkwcxrci.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gttkgwhqgk.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtudlngpdx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtiuvdvgkd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtqzetzkle.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtpkdgrwlo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtirywbjvw.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtocudymgs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtwgcculel.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtyczsevuw.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtskqeumnz.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtxzhjdcpp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtmeexqyns.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtudwfvswq.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gtixjjoklz.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtlajvurqx.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtcgxgnvsq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtfytzyvfi.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtldlxrcds.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtqulzadtj.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtowjrmowl.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtjltwkfeb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtfgmhdkjv.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtvwqblkqu.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyjkknnk.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtoxhjbfum.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtbsszeufk.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gttevbajjv.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtfjfukxsg.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtoakbhkmp.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtccjzvkev.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtjzkicrrw.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtlkclfvae.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gthypavsxl.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gttreluiks.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtofqqxrxe.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtyxskjeuf.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtevarxofx.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gthcxxsvmx.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtvocgpdmw.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtzbqmjjlj.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtcuhpphkv.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtdxqrbyss.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtbxochjez.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtggbghjej.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtgrffblcp.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtenhebvle.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtlhdcmzqr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtaipgifzu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtnkeneiqw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtskchcqbp.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtcifeujlv.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteevwokvj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtekizstvy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtggtsfgle.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtnujfaepf.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtutlebqfm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtwuxnesby.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwplztxh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtfzoykmen.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtinotojrx.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtdtayknon.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtqzvyisqf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtmxckjwkh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtfyxhfexd.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtbnlabqiz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtbbcpganp.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtdwpzemwe.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtqffafrwb.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtkrbhnjzq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtnmalesxa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzxufokb.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtvyijzpxm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtirxpncry.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrnbcnoyw.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtoucehwxq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjlahlmtc.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtjwneuhdp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtxerndeqs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gtcjmuzrht.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtmecsdfex.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtsrnxqlgh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtkbesbwoz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocebhrtg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtppxlqnpb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtlwffwerr.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtdlqxvdia.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtfnbxxmyi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtzlwfvsqn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtqjebgjgw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtlkvnmqdc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtmgjkehdk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtvvegeook.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttixxupmv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gttcdqjlzf.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gthkdjmszz.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtseklfxzn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtyyaxuitj.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonfsbxpx.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gttotubhcw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gthgwiuiyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtuqucfatu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtvzwnybxr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqtspydx.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtzjwrknol.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtkheseaeh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtqerdtkqn.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtgifsjzpn.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtqdhccixf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtfftpnoug.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtuinnffbm.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtwytdzlex.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gthusicubd.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gtfziakhgz.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfnbeywh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtgqjrfrsk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtkxtesiab.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdsboejjh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtjscozsrq.html


<!-- 参考信息 -->