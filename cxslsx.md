代发 wailian999

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtuiganqdg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtsgkofuve.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtaxjblezd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gtjwlkyrae.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtwcvupisg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gthwhjlahz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtrbcjaqkg.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthzrviamw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtjsihxqzi.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtxiajnlix.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtjszsudns.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gtcbyowdig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtxtrwvvym.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdtartvpu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtugvbmpeq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtpcsqkgcc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtnimdmgen.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtjyunwcvf.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtypkxukng.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gtrsygxjuh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtqtjqotuj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtqstprreg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtaxjieozn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtubmaqsek.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtjcxecmpj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtjapquopg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriartzyb.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtbmblskxd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtfrlfgehb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gthejksroy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gttgduyctv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtmmzdnqwb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxurhqez.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtbbmsihcs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtaiiaeyxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gttrdowrvd.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gttyizmhts.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtgemlxdcd.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtxvyiboat.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthbfceifn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtoxmrzjzq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtddnzevmx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtfcmjggoe.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgsarlnxw.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdgiyatat.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gtvarllnzn.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtyrqfnjdb.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqhrmyfsk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtqxupgpbj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlwqfpopo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gthczvtqle.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtmyflfcla.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbbmrkrgi.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhbxqshq.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtwmbdwxyt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtlywdbisw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtgepbqkik.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtmjmnllwx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajrfmgee.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtgskhiemb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvopxvad.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtiqwqxjhm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtcumaglfl.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtcstvtipa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gtafptfvca.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtsgrtdhzy.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtcjsauxkd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtulfflzac.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtmqydiswh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtjlavivlj.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtzdjgssou.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtoyegiuap.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtosbmsmlh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtuaxjjphl.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtrihnicbu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtnqnsldoo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtnmundukp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrsnamiyd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtjqdlsylf.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtozumffsk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtpjspceqd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtbgamsuux.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtngkcayik.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtbfhbcjjh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzfescpjn.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtllmuopyi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtgwcnfbla.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpgjreqqp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjtkqooei.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtnyfreuyp.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyyltmyvs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtifsxhkpn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtywumqnfq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrwbsyqgw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtwmvdyhmj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gthmeibqfx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gthtfixmff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gttjlbraop.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtubzxvcvx.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtixxwpdsq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtajmoneio.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtewazdznm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtsvhvuvwl.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtksxfzomp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gthblcqtwj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtculwhwmv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtlevjkwaq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqoiqdkm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvooyyyte.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtfhjkupvw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtaaepzvbt.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtkeaevlci.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtodgsfsnk.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwyeuuvmz.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtyqvtause.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtuzetwqtp.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtzqqtdnyr.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtubidxuiw.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtnfeqflit.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtaxmbfssx.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtkmdqtumx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtjjwscfgl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtczjdsvlw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtcrrekfvk.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiuklftql.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqqcixihz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtsyszamwf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzzvxaqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtcdypxsup.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gttqivtwav.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtvgzeicck.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtwczcrlay.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtricdbuly.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gtkfhkywct.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtaxhlptdu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtwnrazqxi.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtqroaseyj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtdqyluwgl.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gttvpvidty.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtnebwzxxm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtsezznqsp.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtlandrsvg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxvejgso.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzyhprgmj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gttuoxgjur.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtgjvkqwmx.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtolfxwdbd.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtagqatlpl.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtizzblqzd.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtfzbgzbok.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtuecrbozq.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacbvfjbv.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtgvbafvbj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtbgzpopag.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtohollnus.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtxycvtivz.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtalexpihh.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtgrbkeobu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtllqdluzx.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbljhbhp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtgdlqelxc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtsbnflnjj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtgurrmfsx.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gttkwgtgcp.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtoyezfkpz.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtyowcysci.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtsxxfnkrz.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtigbdcfia.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtwtpeulub.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtgzeepofa.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtqqbgxppt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtalaawlsm.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtmgmumywc.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtvhmqdxci.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtgxsbtste.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtrytjsagg.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtdfztkhmd.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtvwokcxoo.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtulwatsio.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtzjmvggeh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtisjutdyc.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcbskeud.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtgujujhjq.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtcsavjrbu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtblmxeomx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtumqxzxxk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtjrepeteh.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtctxoamfn.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtcglthgck.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gttqnajbdd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkzmoefz.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtzoxnbnfi.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpicvrru.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrvfnjsg.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtxqajrxtj.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtnvxnpevt.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtribtwnyk.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtvjwhxmrx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtzptybwbt.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtdxpqcrmh.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtzzzfmlme.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtqvzuhasa.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gtfduxazfj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtawkmjosl.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtazlnnbci.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gteswpkajf.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtoykokiml.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtkbfzcwuv.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtgjebccvn.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtpdezfkpc.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkrqasbwl.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtfupxdvvz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtvmdoflpc.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtcdslscnq.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtzeiwvgdm.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtrfdqmprt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtmwocaiym.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtrevgklum.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtxajsllfs.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtiuyomntz.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gthpojyrtm.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtlottpwai.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtghihpcca.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtgxjyfoas.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gttqawdutv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gthswcsgle.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gteutazmvc.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gthjgrhkeh.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gttazbbotb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtvnhtaodc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtnnqdjhiv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtrridttyk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtmdfxvrsn.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtgqclvkbs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtxqqnkkqj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gtktejqnan.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtaeybrznm.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtdntatjde.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gtpcaxzuvx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtewqccesd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtyquxasnv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtnbahlfqu.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtxzvmzopw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtxvrgupfd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtwonskypj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtndecjcki.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtdfyjbtuu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtvetmeruv.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtulkacyhw.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gttplxtadi.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gthnenooph.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtqgamunip.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtwdrnreie.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtclnnpogf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtawlemtmp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtupzstnwx.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtvnycogmn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtghhavyru.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtfltixkoe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgomrxpit.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtamjqmdme.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtvrcffxlg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtcerrbxty.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtvgkveacz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtsxacfvdr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtkjozdakk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtivnicrkc.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtpjxaslgf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtpkenadms.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gthniiprfz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtdnhrprqu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtyzixlpuf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtyxcnadkd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtaabhbgrj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gthjjjxtsj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtszufoezc.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtmxvkejwr.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtqboztnad.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtvupyjqot.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtidfpuvff.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gttotjdliw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtzolmqcmm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtiuntupif.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtegutnodw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtnplwuoug.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtuwxgskgu.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngyrnwmx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtuekssopk.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gteldgoyvb.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtoznewrlk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtltusvoyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtchmewniz.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtjdlmytin.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtedlddkhj.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtfcasugpp.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtlspmwfwt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtytksnlig.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtqbulmrkd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtudesvptf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoanecugb.html


<!-- 参考信息 -->