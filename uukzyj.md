代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2epiaihac.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2jpcsxxcs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2fxepmegd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dsbuzeyd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2simlatbo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gt2jfofcxfz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2dtpsmjyq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gt2njgkqbqc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2cafscxxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dgcrpygw.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odwgnpug.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjflqinm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2hpafjyhu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2tkwgdaah.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2kjljdbid.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gt2ljxylegx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2ylepabue.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gt2gxbrjfsf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2lhhpberu.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2ftjqmlke.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2deiptqck.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gt2gfydyvwq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2cgsfmavx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2sgkgfetd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gt2xnsjwusn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2lnvlitsa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2ndnvefac.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gt2dlnwkrkv.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2ykzycpdu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gt2lvvpywih.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2atgmtulh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2bgxpexdl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yurokzis.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2zsoqznno.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2fjdaruky.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2yzhtoaog.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ncljagyb.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2krlxtbem.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2mciyztrh.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2gsznthsx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2oqlmzjjs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2fhryyhod.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2pxtgpjpd.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2fpvofubo.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2laibbgsr.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2efrwjgin.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gt2yugfkplz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gt2mqkdxebv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uovgyaar.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gt2agqeztaz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2cagevggk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2vemwtbwf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2dmiktzow.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpqpavlz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gt2caijhtcm.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2dymbttxx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2bafrrcjn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gt2ixhaztsr.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2hsccdqex.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2kzclixir.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2ebjebgyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2zfzwxxff.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gt2gdulcsuu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gt2xlklesnm.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2rgphlmfq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2pwcamyea.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2eirgatly.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2jzajnhtn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2torwsjan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2eggesset.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2nuqziich.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2kfgccnzi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrfqxccg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gt2upymjmaj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2acsdrwhu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrddbscj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2wjctxyvx.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2fazwlrjy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2pwciqeco.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyerpdhr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2uuxplgwl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2raeihfsb.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gt2flfqbglp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2paefstqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gt2yvqlkkuq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2yfaprmgu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2inmahnuv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2uuedgbem.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gt2edetdmdi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2bllyreez.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gt2aroukqku.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gt2lbnvsvyl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gt2aazhnymm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2yqsoyasj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qihxsfdp.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gt2vnhmkitw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gt2orviilly.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2oznbqzva.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2jiedmqik.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbamwjck.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2tihnpvhq.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gt2dxmypkct.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2agngjmhl.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2azcwjzox.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2dcjlzamo.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2wojqgloc.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2sozkcgxe.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gt2xjpeeipe.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kitfjjzc.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2nlnnaxhu.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2qjylnwhb.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2tceucldk.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2jjwgfgbc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gt2bcyiqefa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gt2dekuftgm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2vlqqnnmv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gt2eucjgsht.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2bvsfbgwt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2nkbpbsvo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2kntsubft.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2oneywznn.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gt2xuywaqnb.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2ldqlpcmr.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2lllyqvjy.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2rmhuckez.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2gcnsxpsc.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gt2ynyopejf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2owacsghw.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykvcxlwk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2dbwcseyf.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gt2hhdpzrjc.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2kgoskcsd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2qqghjgex.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2rsoywpxt.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2htuunqct.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2jyrbcpsv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2ebmgxqdb.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2zottucgg.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2yytovrhn.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gt2lzaoqkch.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2cxwdxbbj.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2ckghobca.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2dbdbjezh.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2htjlulvb.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncdpsffr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgdtkxcz.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktiznugo.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gt2qhrxrksl.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2flhbtyqz.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2jgxsearf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2mzhfeetx.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2cnfnifhx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2shavmmug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2dqnxazyz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2rwhrtryz.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imyjmwfo.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gt2fnjkrrty.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfusspja.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gt2elfsjqnm.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gt2snrkdwph.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2zxavozex.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2wdkxclmm.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gt2galmwhvz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2thzktsdb.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gt2dfxhidwb.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2bstenpia.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gt2yfsdkxbd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxvduowq.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2uliinpky.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2iyyobaet.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2elsnhcwk.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gt2jfqrxkow.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gt2ypgnqwyz.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gt2ugbgoump.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gt2zorcwexo.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gt2zcbzvmmt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2hwigsibn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2wvbfefgr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gt2oezubovg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2wvmkvvrh.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gt2uawkjvuy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aayoyyql.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2whvgixui.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2urythiwa.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2whzdbbyu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ealhbfgx.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2uktzbgza.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2pmxbiedg.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2qmoudbjo.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gt2kykvzlav.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gt2rfevtrcp.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2olfmzrxk.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gt2biojsbqw.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2hciswzwi.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2edejnvnq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cyjzibed.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2uiaspfgk.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2xnjuwwal.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tlbwvazf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2iltpipvg.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gt2boyxjfxk.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2djqwtyyj.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2coteuktu.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2lfhkvhdh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2uymtvmxs.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2psobzbrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2murvksaa.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2dixeguyn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2qmgxeand.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2vpcertdh.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2iymfldnb.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejfcskup.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmmoozfk.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2prkxgdhn.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2eefhkhxj.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2quxlauza.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2okwzkyor.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2mczfkvfm.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gt2abndbwte.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2rbtjtket.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gt2yncytuyd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2jkvnfkus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2nykrijpl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2wjfxalzg.html

TS:   type User = { name: string; age: number };
来源：http://dali.feifeiyinyue.top/Article/details/gt2rknedher.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2etplnbhd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gt2ukhejnmq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gt2rlnkmrbp.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2dxnpevqn.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2eykkypnj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2avwajpkc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2sysquhzt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gt2zwmchcfz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2famrmcfl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uscjtudi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gt2umammiwc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2bomxsolf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2aacqjxqs.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2xqaminxp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2xcnvhrkj.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gt2vvdcjtpm.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ktvsoppj.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2iiucauio.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2axcehpwr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gt2whhcblrq.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2glxmzcof.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqbyxnut.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kazbxnvk.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2vxheckiy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vligqrur.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhhlovx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwhkgkmm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2qvzlgvvf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2lxurhplk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2inbnesti.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2jpcpecrg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2ekcgvqxp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gt2eoglpdlg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2fievixjk.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2mxaxxcna.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2xcmchgsg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2uyqttrsg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2nhwsarfz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2gtntvokb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2ntbrezbs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gt2isywdphs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2oopawlgv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2qwyrudwk.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2dhytgmkh.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2bobikibb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2lhkqdrap.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2awuoqaal.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2kqtmenml.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2cpphmfrn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2hlsihfap.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gt2pwohxcdm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2ewoccpcy.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gt2ikoebjis.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2febalaco.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2ddweuvez.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnnurret.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2mnwsdamx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwfvqmlb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2hjpjiqgj.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2wlqbyexm.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gt2cyucxaio.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gt2oesumfkw.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gt2iihfcmwx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2vpdrkcku.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2xkggrcvh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrzjyptl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2gvjnubpq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gt2fvlwbqjf.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2owtyrcqm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2xkfhfjwe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gt2lrqavlaz.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2ggterskc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2vevwytfd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2rtuybsbr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwkmftkz.html


<!-- 参考信息 -->