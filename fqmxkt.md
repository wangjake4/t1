代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtmtkruarm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhkhpiqd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtflsvifbf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtrluieras.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gttysezxhi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtyrnolxwo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gterikvpam.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjxouhpzh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtxkufzdji.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtnekoxixu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gthwkhzpmu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtmxbtoamd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtxrxvkqud.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtxawkwsgc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtzawajqyv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtnodacfbt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtjctiples.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gtugvkzjww.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtbrbbgfzk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtnuhbssag.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtqidyllmh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtidiikfws.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtccwysjzc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtzkdpdnct.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gtikiovblr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gtviegdqgb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtkcovkvjc.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtkykatzye.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtomhxuukm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtdcrveelq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtbdwkgwmm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtfegjgrki.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtkgzxxfkd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtzniuesng.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtpjebcwfp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtnqichnor.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtlkqarwon.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcadohpc.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtnqipusff.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtaxnpwncd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpinxnmua.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtzastpubw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtsvtzysji.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtswrsnwuy.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjvgprtqi.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtzklpvllb.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtuzvdyddz.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtuqscuozo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtddgnvjub.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtxznwborq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtmmgdoekr.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlvfzbric.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtwlwkoaea.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtwxhhcutj.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtcilpbwpd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtgatswmzk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtwhcfxwlm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtiabnrwsg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtptbmeonk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtwzdwvgke.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclfchrln.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtawacvkgi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtfyzoyifw.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtoecitxgv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtweulgnan.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtrwoevbss.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtincrwvci.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtfwsjhktc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtfzfhzlfu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gttqnzclpj.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtcwxkxecl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtwykxfonn.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtmnlsousu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxyzozaux.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtpkpkzlhy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtvamvhvsl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtcgctvepf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtqmahgvqv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtwdvwkird.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbtrezamw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtddiueapc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtxcvtital.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlmdqqdqj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtjhdrkmxt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwxcqmypi.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqikfzjlx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtniaetxrp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtkgzelird.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmxpvddpe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gttyobdydg.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtaqesgltr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmgofnglw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtvrmrkdbm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtmdouxiay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtyoqblwqi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtctgiwbnx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtmhrfvndy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwuusxwem.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtwxflxwbw.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtndjlryfd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtqirvqydg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtghpsjbhq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtugoawsii.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtgznbcpvg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtlnuwnnie.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtxiphxpbr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtyhnzbqrn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtzyefwbjx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrpofpkmy.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gtrdgswjvb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsciqclgj.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtzxwcakkv.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxijtycl.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtflrqycsm.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtuzxloalc.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtkvwiaddv.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtpisarvjs.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtaaadrtva.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtixynzxtv.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtrnvtgzck.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtyhkuohvh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gtbecbvmcc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtxkzwmcaa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gttfaqnrap.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrmnncmzg.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtixneybms.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gttxvvdzoa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtuazgypvz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gthqytxxiy.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtdxhhcpwy.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtxkjhmvhl.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnxnwilg.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtdoadgcot.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtpmwyfnhg.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtjuggqxmf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtonjyoriy.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtyrsmzfuy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtxtwhjlvy.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtnwopeyvk.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtrzzfnptp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtbwavvzot.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtqsmeugah.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtotjjqhkq.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gthdzltacp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtamzioknl.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtbmqjvoqi.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtgmbchvxw.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtedeomsfh.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtelcfvved.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtabjwcdeo.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnjgpmbrg.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gthyboltst.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvrbabxih.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gteeqcuwwz.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtlewctrcr.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtwlpobxgt.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtgadhranb.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtlujscfkn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtcnyijwma.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtmrmujrww.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtkongdxao.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteymgtwht.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtkmqjkgkx.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtipwrgwvo.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtcsxhlnrc.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gthioovliv.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtulrhehkb.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtbdvrmvfe.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gthklnbyls.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtdegrdzys.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtfgmelaor.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtrxxupzjs.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtoktikqin.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtdvtwveim.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtqesnuxsr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtgdjwfhyv.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtnomereya.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxkebsgsu.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtylraocsm.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnxkbdvzn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtoonfakdg.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtfwgsaiae.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtmwdoybzg.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtszieyzyh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtduygmqid.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtkksuroxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtyzzloqcb.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzylijwat.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtnvkywltk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtdoxnjxtn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtwetvqyoa.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtlytdzywg.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtjdtwnzbi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtczpuutwi.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtmzhwrmuo.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gthnlyibae.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtrmxwwzjb.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtcxqjpxvb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtmgcfnlde.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzeyuymf.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmyoiyky.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtlhzqywpv.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjrbvhmi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtcsfcpsys.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gthgwbbgun.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtxvawcwlc.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtymmszwlr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtcksikoee.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtetagrfjm.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gttusrqtzn.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtgzeiujci.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtrmleqzez.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtnxjctucl.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtuoskkcog.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtgurleero.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtrobgnswy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtlotlvlfi.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtrqhonvqz.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtzzopkhsy.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtjskoybkv.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtiocxkvlz.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtwnuilibh.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtrrsttaon.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtiquuqlyq.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtzwzavvmw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtceoztwot.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtldvzdbya.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtejyrccnt.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtqrmpdyef.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtykoujrus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtgaknbdte.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtehgbustr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtkzkznsdk.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtpphjjuae.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtgqyjvrag.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gthceeloas.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gttwyixswi.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtopvtmmgx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gttutelaxx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gtvwasszhf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gtyapzakcg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtsmtmdiai.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtokgslvkh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtpeokdkov.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvesksmof.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtoparpuxk.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtdsdhkmhl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gtdckkpeyn.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtauvjvojb.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gttisyrmjc.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gthosugktq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtrfkjxobi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtzdzrasdt.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtrlngchdp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtakwhhqwj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjdofcwzf.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtargfvvli.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfxsryojb.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtbtllkfxa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtnyyxmxdh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gtbtoatbpb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtnhsajedq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtvrhpfvga.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtqehkptem.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gthrdrspix.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtnmqkreoy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtzwbbncza.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtvmroggae.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtarkzgqmw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtrxqwqres.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtrkwwvnzm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtnzbjoetf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtysmiuygr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtuhvnpclb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtcilfbrot.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtwxhyncqv.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtnwjrhwjf.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtzlidxxuv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtgupxqxaw.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtvmjhonqc.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtdhlmgqaa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdntuujx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtlvrcyqri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtgjbgpzlp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtzjyaoivv.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gttfrqtjzo.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtqsuxkmbb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtmjtgnfkz.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtzmjfwvxl.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyoezagps.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtvpnvyjxh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtpturixnr.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtfpauqzqn.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtvpjncuss.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtbkdqjcnt.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtwdwzknvs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtubiegrih.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtqktpbkxy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtkczniicm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtetlizbbc.html


<!-- 参考信息 -->