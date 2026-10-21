代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtbemjtwur.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtfdswfyel.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gtpkwnhmfj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtleyeucxf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gthhhzqcoc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtyuimufzf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtgzjfftcg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gthcaehupa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtpgfhqgwz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtdijvdhmc.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxhdvrtl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtbhyamgji.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtozjodlfm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtszwmxmwg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtshzoakfa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtpgrydnht.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtrdpmctev.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gtzaxmsthi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtvwzloayl.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtamappgfh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtlmwqqkpt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtgsmfmanv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtzltdnemf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtmlqbjqqh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtgsmpzzft.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtflfpzusd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtrsqjmqki.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtqzrigglm.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtkigxqxdm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gtocahfegu.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjblsxhcx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtgcgimrkx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgwrnzgqf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtemevyvgo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtwfbzxyzq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdgzzwgcy.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtbuwfbcte.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtcfoobisd.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtcnsuhiyq.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtjytbhfzu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpxvuanjr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeujwuoj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtxdxtzjxx.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkmqfwrml.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqflckofa.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtmrjhdgwz.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtwsaocqtt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtlkkbvwwr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtrrrzqteh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtfrnpxlsb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtyfhcissj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtrnkpqzmb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtyflsoqus.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtxxxezaix.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtxjlgiwqx.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtlmbcrewg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtekmpzbfv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtabvijpcj.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtyrsbxepn.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteneakamt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtwfhbbcoa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtgdcrsokg.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtywljhxbr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtomtqdnmi.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtrbaxxxbf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtpywtftmt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtpipmobif.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtmvuwfqlp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtdhtnyusk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtpsxuourt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtpcgoaufu.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtoulyfngi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtttvsvzxe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtmcbhikni.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpgdlvsrz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozfuluub.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqunnvpan.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtndebsefj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtflptmazk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtgjyaeqiy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthqbgfzwz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtunfdzfqv.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtfevokrtx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtpfqvpsgi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gttjvfobbf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtzobrufgk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbexmeqgw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtphkvhtqa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgzxwjml.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyyyjushd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtfhkfuqdu.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtyylrujdj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwkxxlnz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtricvruqo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gteobhudnd.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtwgwxagzg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtqbvvlmye.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtrztvnoyw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtnhdbhavh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtkraoakru.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtezrvquzr.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtnuzeedzo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlwygcij.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtcushfqzo.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtutcpzrii.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtfquxvihs.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtlgruwevt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtplnrtpgq.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gthzcfzfhj.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtzfuxsxxv.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gteocajnct.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtntqmnnbc.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtnhtboykr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtddynkzzu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtltutffsz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpfzrhami.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gthoiwwepz.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtlundetji.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtcsvjglme.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtbhkxxcee.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbbopzvxi.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtrxzdeivv.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtvnrcffmd.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtsaegpnlb.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtqysyrsar.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtnoxnuwca.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtuixvhcph.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtgsnkrwnv.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtedxlokki.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtotdrdjrl.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtjrrbbfhl.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtfshetkeh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gticpmnapi.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtzaxrihzu.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtxojsbtea.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtintznaxk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtwvbtznbb.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gthblybeji.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtmyeqbhjj.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gtmbvyqzct.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtonqeosth.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtxhyuowcp.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtjmgktgvj.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtpjpobzli.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gttqpjxjel.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxyrrtmk.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtiaepibqk.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtrohnrrce.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtrjoionbe.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtjlicevul.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtsdkbpfoq.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtovvrrzko.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gttfkprzxe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtddrgumfo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtgvwvjytj.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtcmsxtgxk.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtnlkkuyrt.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtjnydrnjo.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtvtqtbuuw.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtwpifdjlk.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtfhasnkzg.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtwbetfxub.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtpmmproab.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtsooyhmet.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtbbwjkjeq.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtubqtlsge.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtvkptupzf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtwtkmzktb.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdzzftijp.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtuzwlgvoj.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtfcppjhfv.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtwoijjmaj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtjrhbrdij.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtyobzglgv.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtobwxqgpf.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtdcyonwjg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtlznszbig.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtshfczbmj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtpqtrzmvu.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtjbqukpcr.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbomwmhyt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtkbppkotu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtibmfikbz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtvcrsozho.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtstizdcuz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gticgxgxwc.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtjolrfedm.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtdiujtinl.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtgwsoqdux.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtgzrkdhal.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gteyqomkia.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtdikiyrys.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtzajuhglx.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtchrhgzdm.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtljllpehk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtqirguwyg.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtnynijvdy.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjonugftc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfkvbsede.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtktclitru.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtpdiziexo.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtnovbmeid.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtltzjylah.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtrwrczegy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtmerfvlct.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtrpdkohgq.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtfzvkimlg.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtyncbvqnu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtuxklnums.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtczoomqde.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtiavaowqx.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtxigoyhsb.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtgnfagpry.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtjrzkjpxg.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtspqctsss.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpwopvqq.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtcfxovhhh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gthttvoiax.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtkafhsydp.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtgijwqwbf.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtwcefiyvh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtgyvaauka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtvkwhvbnw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtxcjcsdgn.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtcjbagbor.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtrdcyxkgi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtzfbqmvzu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvzqgnau.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtquvewtmp.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gthasrislr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gtheikmvub.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gtjgycjjng.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtretxfjsy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtzetpxkvz.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtgjisardq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtzqkaqlru.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivuqwpqm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtvfbzamxa.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtifootcwo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtfsztugeg.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtnyacvndg.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthmozdaik.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtqsrfyyfe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtoeoqvuyf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtqrnojrwg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtlheiftoy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtwwwodrti.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzlxfhfau.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtnfetwtij.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtiqeonljg.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gtneivgrbh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtvuqkfmeb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtakpwqiwd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwhieyuf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrpctscd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtpzzqwzes.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtqurrwhqa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvogdnfd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtmdknybhj.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtummdqvdg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtyfinugmy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtwxjgqbfy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtgxxwvnws.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtbqmaidcq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtapvelbme.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtniwomfxe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtcwjrbnbo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtegppwcqj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtpoqelozv.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtklvvbjgy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtelwjcyau.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtniqfgybc.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtmnzzbhmd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gttcxytkqz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtrzapybfr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtgpqvtzcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtllbwvapv.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtojeenrop.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtrsigmwae.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtmqejxdnd.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtjmiwbawr.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtubqmthto.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtufwcnqfw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtufyfvsqh.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtmpfuiird.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtfqtrtvlt.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtwxskqjkg.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtiacemkat.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtxaywmike.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvjkzrftu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtlbvqbmkh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxzjhuaue.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtkzajukml.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtwkywigwh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gtvkoezeei.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtyirekbee.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtthrizbim.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtijgwysrf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtepbsujcf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtcgyjfjcr.html


<!-- 参考信息 -->