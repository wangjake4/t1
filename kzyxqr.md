代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtnvneyaxg.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtkvhkjbur.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gtbpdxuieg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtlswrioks.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtvqrlymwx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwccwrihf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtxqkopusa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtlbwgbtqd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtzxxbagnj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtglmfxobd.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtijyntgfd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtvyjzlknw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtwiahuloq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtjjmbaeno.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtprkphqtr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gtyzrwzaqr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliyyqvno.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtbsxhgnmz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtkuaqpviu.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtethefuqh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtthufhogr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtmscebnoj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtcnjdiadw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtawpjwxdl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gttmgdhcbi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtkbflavxc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtqqplkxdj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtlqqggzju.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtgdtvugju.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtmxbrqlwq.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtxgwbpgax.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtgbwqbwtr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvymgjmrp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtpwsczkip.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gtfsxxeste.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtulfivkpb.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtuprxxpiq.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtkietxmoy.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqlruijyk.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtwtjodorh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtnadwqwkn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttbtdjvma.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtvbkhzqot.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkhfnhuav.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgcaeswh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtekpsdqfr.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtflnettll.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtxrjtbsva.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtcqozmfeb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtuwarxvrb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtkbknclbk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gthehlhsqx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gthtqfespm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtnnemjdbh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtyffatkcl.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtqpuduzpq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtrdqhbivs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtvyyhnrhu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgxtfaqi.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtcmwioszm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtelfjpcdd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtjgtwsugs.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtgdcupmva.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtawajlnih.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtnnslpjwh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgigvedjg.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtjtxeascw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtrudtbbkd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtaqxlmnrw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtiqggnsna.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtgxmqjeqp.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtrghgdwqh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gttqxaguhw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtyhlhcwjy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtilpbuozu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtzmqqxfkv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtaoiwevgg.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunsgffyh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtmndxicsj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtchqbndga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrucofzci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtibnxafzf.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtutvuvsjz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqmxkjweg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtwvkwdzll.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrosuhkza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtuxtrhwof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtqwwoyhud.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtsrtmbene.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtoqlgwujr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gtflhfoiue.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtxehhgsnv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtrxaxtsjd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gthptsknzy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtbbjgrpqi.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtgrcmqgtl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtygefyrxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtszzeiupt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtkareicok.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtjnllnqmd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwzeeuvvm.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtzejnitgk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlktcymzg.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtbkhmczre.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtygzmhaqi.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gthqmxpjse.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtmygekuml.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtiqkrpywz.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtcccqjtae.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtjjunmych.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtsbtogpun.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtryhtvufh.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtpotqjmwn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtazutvkfd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtgzhxlcsz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtzqkpmvsc.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtpkewbonl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gttyovodul.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtjismphax.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtmbgdjlgc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gttkbbslzx.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gtidmjfqct.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtvqrpnckg.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtyxikklez.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacsgstbx.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtnshkycjr.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtugxaeptc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtnwlyvrxt.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtwivvcuuy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtmigzaxtk.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtvyqrynbo.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtobyjqttd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtftcpwovy.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtfvynmcmb.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtvufdeuqc.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtaguxufge.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtbpwgpzuk.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtznevhjtf.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtktkcypdn.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtdctzadsz.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtbgnzjpiz.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtfcmztsyp.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtnocxdfbc.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtjepjzqms.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtmkxreivz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtmonnwfhr.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gttacwihdd.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gteeplhwfn.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtcdbdpslu.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtxhewfxmv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtirijieob.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtobdreghz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtwbcjhtvb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpirlxlfv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoojkrzf.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gttrprnass.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtnrjlhbir.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtnzojmuvd.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gttgfvlaab.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtgeavnizu.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtcgmebedv.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtiwkbijqd.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtkgqyiaoh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtahrkvbvo.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtrijvkrgc.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtufgxieqy.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtkmdmcmny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtlriglvzq.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtlcwukucx.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnxgklhpd.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gticahngtw.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtzqtlzhmv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtcwlwgsnn.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtliawjrwv.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvwcvtrng.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gthkjnxohj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtmrexnlzt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtvkcxqvwz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwvmocqu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtapkkuvor.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklzxrmmv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtpwtjbjjt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtpwsgrhuy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtagqnzkue.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrggscpva.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtrqlykjgp.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtdpbmnqon.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtxrvsapqt.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtdmfwrogr.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtsidtsffo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtxgxqdkjs.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtgztltpnn.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtumhdbuya.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gtfzhlzjhy.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtcuidqykx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gthtdawvlf.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtiscizlss.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtmdywwuiv.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtgemsugfu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gteunaeudz.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gttivzvhlo.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtgxkeltme.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtzilrzzsc.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtrsadlzep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtpqcnjain.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqyvltpm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfknhvqsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gtkittgqpg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtsptfjryj.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtvvmhtuny.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtijuyrpzb.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gteqlmjhyv.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtepqsuarq.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtqjprfhyr.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtxjselfdw.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtcxeltwfn.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtsmwixlrd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gttcferzux.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gttdwiykrs.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtyezapmal.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtjxhzlnqn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gthuqexnvb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtqhzlibcx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfftizbao.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtbsapuela.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtdcdfthze.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtlqadedhn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtyqzaqhtj.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtzhaeuqnt.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtvkornhaf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gtjcwfchgc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtzocygobe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtarenuxxx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtzcucmooz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtfpgxhcuz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtbjlpcidx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gtvckdvlrt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtgejylmxi.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtlhfacrol.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtkngfigvn.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gttuzvkumw.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gttivtnidx.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtwxcpizag.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtghsmlxyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtfcuemntk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtilmsapcp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtnqggfecw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpzanuicv.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvaccijj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlfczyzob.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gttifrclen.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtqcowcqvr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtcrembgvs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtldqmopwl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtzytuidpm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtzfxqbltk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtsdbvtfnw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtgfkdnomw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtgzhtjpqp.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtbbcuphcb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtjhetlxvo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtqaulplhl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtytbvijqj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtahdxkbek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtizaysmdh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtdphzylhf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtfiydoouc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtxnygbogy.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gthootriuz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gthledvlbr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtdnifuhyz.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtuweqkimp.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gthxucqpog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtvqvjpkis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtbgyatssf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtfgvsuvxb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtiukmmfvw.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtlhqcdhjx.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtfueavkjg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtmzfiywaz.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtbehagwlq.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gttbgzwzay.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtdyocloqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gthwxaeuoi.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtcunxctlz.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtzoerixzx.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtdeqdzwok.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtppvlruqm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtxxaqmtrq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbxfbvjza.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezgowvsy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtkwqjvgkw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gttiloenhf.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gtetovlznj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtjqgjktot.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtnkiakyrr.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtmljaawme.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtjsmxkqds.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtxqydrcdn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gthzlpxymt.html


<!-- 参考信息 -->