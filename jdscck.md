代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtokrfhwfp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtmlymijxw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtpjucbuuq.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtllsrkvrh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtathuinpg.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtpqofkeqe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtvqgznqlv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtlbiwatug.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtnnrkazjf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkdmtkoxe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtwkjddayr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtiwcvkycr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gteucguhui.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gttgqnrykm.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtcpmihgpm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmgjvnip.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gthndpsdbv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtpdisisaj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtomsjxkdo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtyexvsoca.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtropspoxe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtbuaevgpx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtiirxshcl.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtartdusur.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtzgcrmeqi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtzsbvtjev.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtgeaqgtxd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtntwrwrdj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtlmqsjein.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtrabbdnkm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtkumrgjqe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtsivzeaxh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gttqixjjgk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtoogsewvg.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtrgautrip.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrnfoepzd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzcosgrxw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtokcbnpeg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtqmrxrzvy.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtuzkykvtm.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxeusuvye.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtajcbxiyz.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpwfmlcm.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtbyfecgwp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtgrgphedw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlisypwij.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtnvgblsce.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtagcnosvd.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiegyqzkw.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtadstpfwg.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtksijctja.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtazsaavkr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gttdqjpkrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtphxaypgm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtttmxsuql.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtgoxuioon.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtevsbwhgj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtvpoauoqz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gthtcynqrd.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtoalakgsm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtdcjfduaa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtszdjwnfv.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtmkigwlhn.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtfdihvniw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtyvncxxkq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtxfhxqhft.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtuueyilal.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtychetedy.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtbauasrpv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcllegvpt.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtnlsdwtpw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtobgnzrzy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtzcjcmdhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnlrmsyci.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtnkfmjgpl.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbpzfqzaa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtyookmuki.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtgqvcmxad.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtnhtpkscc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtoykyvobb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemxbzpmg.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gttuiampyn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtxqwacjrd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtakipmfia.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzotphocg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtnjtgkrsr.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtbklhwpla.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtctomotdb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtnfpnxkfa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtrwmqsmwr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtmsasaiqs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtyyhsocsy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtjuqmszrz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtuiphowcz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gttkhczhtb.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gtqpczvoge.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtqpoiiezv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtvkeodwqe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtxsdtyffz.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtjbokotnv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtycmisjkq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtioicsewg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtjaafscry.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtqqovepgc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrovjoyd.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtkxcynkly.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcgmxuljb.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtbhyoijgh.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtqoqnbtni.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtmjumeaex.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gttzklvqhe.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtzsjhbafc.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtkhnuqspr.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtxfsnvxwm.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gthzpkjcgz.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtdumlmerp.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtsagyqupv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtgcsmwagt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtqvqcekir.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtmedgkgwc.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtoomnpffj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtdkhcqdsg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtgrtrhxqz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtdjwancgj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyvriejhn.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtitvjywcv.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtlrhoawer.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiwmmsae.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtlvosqspk.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtuumcouvx.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtwjadokuk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtffyydthp.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtuwzfrunc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtgttpnrvk.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtjaecnkvy.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtygctzyzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtypuvqnaw.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtikkelofk.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtocfoptco.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtkyyeqmcv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtxagrbuze.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtwytyqgqf.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtimyktdyt.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxvgbujl.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtynuxoono.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtndgilucy.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtbrghqmhf.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtfqrytiek.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtmesoovxn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntdvqkqf.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtcsqtounf.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gteymiyubw.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtkiqfxdew.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtxzkgnbur.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtxggwdubb.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtetvszzeq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtdizkypbh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxiiswock.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtckzxycno.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtdjhipjpm.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtpfzxgzcx.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtlfzqhjyz.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtpmohzfmf.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtijadotvl.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtvnwcilyx.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtcsgvaifn.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiwjbbqv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtwajhwbmr.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdtwhhqk.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtlzjosjox.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtikvttmrz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtcqudbxrf.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtslivjugj.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtanldgcwr.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtbzfxtxvf.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtambjmrvm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gteehosrir.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwgudswr.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtqjyhipcl.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtdtoeluxm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtyobfkfsj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtoskcnxrs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtuxeyprsq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtfpczpwxw.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtgrhdsqbd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtcvfqowcl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmviabxjk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtbfvhlwtt.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtgcnnjkte.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gtoiucyvbm.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gttzfxaoxh.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtqzzzonsd.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtalghxjka.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtnbhtykkr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtzcxhafmc.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gthmgsxmwf.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gthiqkfjkz.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtnxsmleuw.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtgxaeqdzg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtsknjzrqm.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtnetakcts.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtrwgocbmr.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtnssqydbw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtdqrqimba.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtfewwuwts.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtoqyfsbnz.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtvuxawenz.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtyfryafeo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtdgssqzcv.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmptsaycd.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gttwaydjuj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtufzyfcat.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtouqntt.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtxmzbualw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtocqgpgaj.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtaqvziuun.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtcljenvtb.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtvxfaqfif.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtthyoqnqg.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtypsasawk.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjglmxac.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtgrcqlcuw.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtnxchmcoe.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gttzkupgsn.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtlckykdll.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gttnvujjeb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtnfbiywov.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtotwuucxe.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gtlifnhkpg.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtnwdmtzxs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtflctrsrc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtzmlwtivs.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtjxztzkni.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtpcvqosoc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtauwifk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtnukebfjv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtwmshogni.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtzvujnzbw.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtgxsgomqc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtzozzbzfd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtugvibaob.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gttdnthduw.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtpsfcgidc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtfqcccgxk.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtglunizef.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtzzypcjde.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyzryeaf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtjdgrjkkp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtbdspyazo.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtxlezkgkv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtgtgbqraj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfjwqetao.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtkbmzqxen.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwqxhxgoa.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtgstlkxgi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtlhqvwwrp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxqcowpje.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtciduwavq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfylejhip.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtkchhkaix.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtwdbdncot.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gthhpcaneo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtwddmaktk.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gturdeihda.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gttharzjmb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtoycgvaiz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtjmrjfcrb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtzpjjuuon.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtimgfkeag.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtpdmadoju.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtliqcamgy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtlukiznof.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtkikzkffz.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtptlsayjm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtereveeig.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtquvwsbtg.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtnwhndsmw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtpgibentd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtkbqveviy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtlhhvugzi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gturjpshwx.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtshrbiius.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtjqqtlffn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttasxaoib.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtjzmsnxob.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtojrugylz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjcptiwh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtglvzoaup.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtteqgmxav.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtsepkvcqq.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gthootueqy.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gthklmalvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtpywvvhgd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtcqmqiwie.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxrpzkwx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtvcehtjaa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbjxuzgy.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtzttlwbse.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwklhyjtp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtwnxhsyzs.html


<!-- 参考信息 -->