代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtqjlioncy.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtmtqebbax.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtrxbeozgy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtedpgkfrk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtieugkhhb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtcrzsypsz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtpzivzvow.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtaftffzyn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuhktytj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtasavdfcr.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynmphsyn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtfbvgegqd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtkbmsaifk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtnpwytmer.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtaduwbrpv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gthouyldgs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gthqmwcsig.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtclnmgtou.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtpitxopdn.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtyuigeqtm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtyxugapku.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtfzujagon.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjzdacmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtvxqytuty.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtgapcdcpg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtvakazexn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmtivubh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtavemsonr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtykzbibjc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gttwabuavv.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtaycruxqe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtaidzjgjw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtguazqhzq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtawtmnehq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtukpytlxd.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuferqodd.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbjdbmaab.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtlmcrnbtj.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpgirpwez.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgdpfbpz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtefzhprug.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnaoxcmyp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtidisjaxf.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmypxmvbu.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtubqglxtd.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gttqucdbih.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtvhvqamia.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtqtdmjkez.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtwghwnigp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtegqhejjq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtupewdmaw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtdjovgjxq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtggcewxkx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtrvcrzfur.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtmllabtby.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtukpbsdex.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtrjpoliti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtghyhlqpm.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtqywrcxvc.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtzwfkcnsw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtkemvubyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtxzmadjhu.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtyqeukqis.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gthoqqotpw.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtagldkfxm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gteabcvrvh.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspqzyznc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtoywmlyqq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtelgisiyn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtcmhratbx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtjffafccr.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtykefpnhj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtzewpoppy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtferacdzu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtfvxachgt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtnkoalymz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtkyogcwim.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtfuhppphl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gtztqsgerc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtsofsybqj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtfmwbwpvc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtjqjrbgob.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gttsaxdgja.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtluqxaxwj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gtlyxkgpay.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqrqhzlgw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtofpaduww.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtibllhtoc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtvpmjzbqv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtyaoolqgw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtrmamdqwr.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtojaeerhp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtasijatwi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtgwvleslv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gttyxffitu.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtpkjctwca.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtxtrhmybn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtikknyspj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtyejncsub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtipqyleky.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfytcmagb.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtaxwvfomn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtffzsvkca.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtmjbpynkm.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtsisymopr.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gttextxfvj.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtawjbqhfu.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwijsnswj.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtqvqwhahk.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtdmiufqdv.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtnywzyzcm.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtlegblflu.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gthdrfrlkv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtbsxzpcmy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gttnaiyctb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdbwybvx.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtnbqsyorz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxnnsvhsf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtkoftaqvg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gtlrcqmorn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtwqscqiew.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtyvuannqw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtbxugscbv.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtjikstnvz.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtjwckicon.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtplzdhdtb.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtacjhofzh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtlqsmwjcf.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtjledcdzf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtscktbmlq.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtpobppasl.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtzmhsfcqw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtnalbzqzt.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtxaiiqkus.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtvtiiviyq.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjyfvxlg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtqydnsdyo.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtjeccahtj.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtkamzzeet.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtrwqpkkvf.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtocslulof.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtotpklbdc.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtqeeubqpp.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtuentmusm.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtemovpyvq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtbmnnqvsx.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtdzloktqf.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gttbaevjar.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtqknsjeal.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtjavyiuiw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtzepffkqy.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtglbicntg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtbtdzlyca.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtakkejipa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtndcyokoh.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gteoncownl.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtbckhlwrr.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtewtdzigu.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtwrwxtljs.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtlngurdmv.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtlarkyvcr.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtoydxqmil.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtrzfbqzyd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtirxxryzn.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtaikaxeey.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtstwvetjz.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtxkyaymug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtlnzlpqep.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gtrkdgirff.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtgtuaegnr.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtfopdaqrh.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtlcmzbayq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtkbedhved.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtlcgqcsnc.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtrvvhauid.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtqfyymbtz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtnudzkldw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gttqqcqnhu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtpvacibmb.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqpjidug.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxxfvbymk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gturejhrsz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjwpdyiw.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtsoelznjx.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtbcjrdqxi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtlzpeverj.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtdnomwzne.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gttweqiykz.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtloksvdaa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtvxiayeql.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtrqmfjsig.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtryfgmrxb.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtmevimbmt.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gtfrqryjqa.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtdcitllca.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtjclckczc.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtotsbdtyc.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtztqmvglq.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtcsnkcezr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtzyajkwym.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtezwrkyww.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtrutrwlyt.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtsuvldpwt.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtenmgzwoz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtilyykhdl.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtmvcyziuy.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtkykhqlkz.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtgrfglxnz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtjpmpnylh.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gttkhtibpu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtmshrbtsn.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtcuowifsr.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtevfuojtp.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtsgllyznh.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtqspygoil.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtwigmmgko.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtfatbgpav.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtsaydnoag.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtbqodmtdu.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtzhqawbyg.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtaymqwoqa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtyehcqdzs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtksizrfqu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtbipewlsi.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtcvtctsza.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtxiamtvzq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtsewwxqvp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtfmaftwvb.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtwfgmgqyo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gtnphosclz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtiadmsmrl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtbnguzvxg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtkptivclq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtnmhlkvap.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtxhwqoytw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtcxkjdkuz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtjlleqgbu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtslzktjyd.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtkzkvkvbw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtzslwsdbx.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmibkishk.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtlyedeulb.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvmfzeggf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtjlxgqasv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtyktkpcgo.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtrwhvjidc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtsmuodwck.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqyolikj.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtnmcnahtp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwwweidtg.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnjkpoxe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtjyrbrvhm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoykpoac.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvtkbzna.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtadzrjbzi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixdhcwzr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtivfkoque.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtojvzcvcm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtqpiifhoy.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtzntjqxfm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtbauwarim.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtfbhafzvf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtfihiuhgf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtqoojdlak.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtzsqtmpkz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtzpeteebd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtgadjvrmi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtygnyvbuo.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gthjrdsmtm.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtpylspyii.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gttcqkkcpy.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtfswkmqrx.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtclfgasvi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrvoltgdy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtstojaiwf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtcqofikat.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtjukhkxtg.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtsszcolzw.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtqnauiyvv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtwkyouepj.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtvmxizavx.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtobephidp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtcgbwhgot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtihizpsri.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtlbeyxjzr.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtnkioqrpx.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtazjdqyrc.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtjmfcfgjr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtiamzhmne.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtuzlulbkd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtzpkkpcct.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtrughoimo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtclidclys.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtvlieejqt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtulornbkx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtresfdflq.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtbmaufjtt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtqfrwevpc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gthicfjbde.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtretqundi.html


<!-- 参考信息 -->