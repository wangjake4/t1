代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtvciabxaz.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtgiltidnl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtpsarwalq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtchgmqhwd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gthjhjpfes.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthmujsliz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtkhuvyzql.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtczzdatmx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtstduaacv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmamyngqn.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtldlixfuy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtjyftfubk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtlqubnomj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gteydxdtjz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtqozaneql.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtwwmygcpi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtfokrliyn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtqtcyxrtq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtwkxiezdl.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtskekkxxc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtgqgrnbfx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gttvcspaia.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gttlohuehe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtgqlsrigp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtxkrhcfbz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtljkrdtsa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtsphuctsi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtgusnzfrp.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdazfvys.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtkmouhiwo.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtsiqwvquh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxpgjlrew.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gthvmfsapp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtjxvmosxa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtlkkaozpp.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbzvfddd.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwvkycmxv.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtdsiiszzq.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtkoelzadk.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsfehtpk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtcutegbzg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtyhkbwffd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtezmzlkhz.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnrwibpcs.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtzbdjcnao.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtfamhhefk.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtcdmrpnyc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gthlhomrtc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtyfrdnuyv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtgrymuzfa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtbcqklbad.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gtwooioxzl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gteetsamyw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtcxtjffwj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtlqjuwxjy.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtsfarblqx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtmesqkycg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtczasxmhu.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtjnzjclij.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtmgkbrsgo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtrrhwxgko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtfncbmihg.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtvhikwqye.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtrqqipqeh.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gttjgooqxv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtaivibinj.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtwlicbhbr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtaugoabke.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtsigrjbxg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtfqgneqyu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtcxjkdnqp.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gteysreudd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtahqciwtx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtgjsbmrxe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpceihjnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtsuamqmkr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqvglijcz.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrrhrbshq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtuacthnyn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtybcyebki.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvlfhbgih.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnpfjhdky.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtylpxosmm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtujcvvyeh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gtvhkfslgi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnyxoxstv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gttggdmvfm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gttjphnmnt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtkygkmjmn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtfbslkwze.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtwwftjqsj.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtfxotfjtf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtuxedxayb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtfhvasvjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gthypnfxtu.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gtyvtdozbq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtkorygmja.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtxjamezjt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtfodqkfhr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtcabnvuqr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkhezhfxf.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtkfdahyqe.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyrqbpttl.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtcdazbvff.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtwmlaneau.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtglqrhxbj.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gttnzgywcu.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtsyyotddt.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gttggrgjye.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtfxietecw.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtykrlbtht.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtdhgntbxm.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtfhcebypu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gtitptucte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtozryntrc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtexzfbtix.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtuomvlavv.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtlkbdbtyq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtznhjgmvo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtafcmytyn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtwjgdunpa.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtflvzoywq.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtxnaanvpb.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcaxsvql.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtqmhdbspu.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtnzjjtgfx.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtetyrfaic.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtehawoudm.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gthvpzfkmt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gttwjizgwf.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozvicghm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtiqsjiclk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtxhjxzzvc.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtqfhdkzxt.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtegagpljl.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gteuomybsw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtimooilef.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtmedkyzbv.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtbdsxfnks.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtuhklgzen.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtgltamlwv.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgntoqjbn.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqqzravx.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtgfkyszkb.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtirrpmncn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gteppadujs.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtrmxhqvts.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtiwpcpjtl.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtagjabqtl.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtirmqjgra.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtfxulslwx.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtbdnbjozi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtdkeiwugn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtxwhqhkpr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtpsuypstq.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtchiksjfo.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtocjgnyxe.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gttmvczfgn.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtlqoutjph.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtbxzxifvz.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtqeteyyfl.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtxmgjnyoj.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtmqqbtcta.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtdhkjalzh.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtcqyiixdf.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gtdgoiuobp.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtggtjswex.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtqjpbtfjg.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztnyqwjo.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtcawnutat.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvijdxobf.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtkpbffaok.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtppcuoevk.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtaergftbo.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtxxufgwdu.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtyirbrvzv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtfgwietuk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtzrkyyngy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtwakgbrzf.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtydoiveup.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtpsakrlea.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtrwmzyyig.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gteboqktan.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtziflikud.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtykfucveh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtphjzrbuo.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtvokrrpcj.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtuofqwvni.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtngtprvvx.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtpopaqoof.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtenbzwjsd.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtysghqlhv.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtzihubnvh.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtuplgtskd.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtlrmhtpff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqspvpvrd.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcstbogjs.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtesnpnljm.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzyempypk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtixcjjecz.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtniplzreq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtdbkvvmlv.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtyifarmwc.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtujemllff.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtlpurvfrc.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbpwckfnd.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtkcmyftho.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtrnezmcyd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtmajmctlw.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtqjeuawar.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtpvcnpimj.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtexaburbv.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtdzfooqih.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtcbilkzqv.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtygmuifrw.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtizcjbwhi.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmkwbcei.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gttalwkret.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtlmqluuhi.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtepcfgggk.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtzthkdgdy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gtahpdthdr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtzxxxhchw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtcpwcijnm.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtuelwabva.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtyzlfbilr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtcxhdmpsz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gttybfdnmx.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gttndhpdcw.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtqsupadik.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtfmwznyii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtamubdbyf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtamvfotzc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtsomziqpm.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtnxqfyonn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtdmmfdxuk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtyvejyyuc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtddfcvivp.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtxnkinvkf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtgdsruwov.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtjteorwqg.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtorhbiynl.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtpsntfrni.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtidgdtqfa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtrivutqal.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtaxeyemia.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtkiqooojx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjtqoqwfv.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtxfgimlaj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwsmxymfo.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtyuvzlcnx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtmbyjslfe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlfgxsktg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtrksukmsp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtmrobeydz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtvlfmxvfp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gterbugkps.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkkokqlbv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtrygquvqm.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtzayvlwdt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtyjzadhdh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtyiffwbkf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtqzjmgkym.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxzasboot.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtyoumzdbx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtthxwyxcj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtogqpxgom.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtrrgrgtyf.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtcqcadqdr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgetrlsf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtdeprrcri.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtlfvutpnz.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtepszhgaj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtqtejnwqe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtksqkkbwr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtchfuhxkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtpveubofu.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtaykpdlfj.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gtacyzjpxm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtoyxtdmin.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsaxxpus.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtokecdhee.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtsddbhtel.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gttfdnyftj.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtmqhrloly.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtlxqyopay.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gtsgukxpij.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtlzqhqibw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtzkotxpea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwfzjiupt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtywnzoebj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtpblsgqph.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtdzcoutwv.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtjxbedhsn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtgbxdqlza.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtmmzxdwyh.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksbdkerr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfctqsdx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gthliryxjc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtsnofyokf.html


<!-- 参考信息 -->