代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtgwvbkeew.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtkxmpijnx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtgtgvaxju.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gttjmtheij.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtybihktol.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtedrynytq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtjukysglr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtivnrdgtw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtgjhwuf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtfhohqcbu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtieiyyzxl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtmukjasjz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtomddllqt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtoovjwaqs.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtspietgok.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtrbdlpnkq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtarktbvww.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtcyygezpq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtzuyzmqew.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpdeqjwh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gttiqkuttf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtwnmyuzeo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtcizlwwis.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtqygmgvjy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtlvkolpbr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtvalztjon.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtycujakph.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtgfklebxi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtgshejcxe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtuevyxmte.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gthwzgfhid.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtdwxoobps.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gtylthbjfb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gtaydivxfj.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfbbwghqy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gteyweqpsa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtcfncgkvj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtcrcpkepj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtorexdznd.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcodmaowu.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzxkinqow.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtaaagjdrc.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtylqyjnpk.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtzgeyqvas.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxtqkzowq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtybdjkzrr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtltavyrcw.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdreutygp.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gthvobzdjo.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtwiyvwldn.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtqrvzlwfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtsaubbugh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtdvsoapsk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gttbwcycnj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtdktfifmq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtnqpgrhcp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gtbwsnwlak.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtzhlmeivs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtlmsxulzv.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtngjilpiw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gthcvorrup.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtyjabowih.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtpgeblqup.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtlqbxiiop.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtpnrqscjc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtmihmewpj.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtrmvoyvch.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gtewvtiirh.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtfneqhalp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtsbnrsuzo.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthioyfxsr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtclzfzffw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtrgaeenmc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtspibekam.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtbgcsbzil.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthwmitynb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtkysnrdpv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtsflfjsto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqeroacqu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtajtpmmbb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttykwfadf.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtobopwguj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtbghiuoxb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjyhdpkmj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmonxzscf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtppreeixp.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gtygbnamgk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtbryfuyoz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruatjwqt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtopvppqjv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtzcirtyrg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtdbxsbqyu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtifciwjzs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyrxeldkc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtyriqdeyf.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtbwmzdvzh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtruukesui.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtghgvyoah.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtvurwdkau.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gthlqvocmb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtptiavuov.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gtsbnmhgxg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gtjxioezct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtpcetzltv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtduywxlib.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtwijzneft.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpiysyvns.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gtlgqcofuk.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gtslvgkots.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gtvzuifzdr.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtypekroue.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtfuayskjt.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtgjmiofis.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gthhjktcbf.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtjvfpebro.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarupecei.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroeaocuw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtqwztsots.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtgzieotyh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiueixjg.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtnvszgglj.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtykreadnu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtdnngwswc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtqjltxwuc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpnfujoge.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtmfczgfon.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtfqhzotot.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtwiyhuhoy.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtvzpstoev.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gttolvbush.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtkpzxdchu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtjzhuapsv.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtzngyvifd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gtslzmymzf.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtidqyewmu.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtwspgufmk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gthlepuipg.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtowpvjagd.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtsyshuixj.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtcqonndvs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gthaopijxb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtxsylwfdg.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtwgombbna.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtrvdaurqq.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtldrqxbdy.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtbvwjmxrk.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtgklefobb.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtpdvbshgu.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gttgategzr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtbgmvimdi.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtjwlxknjq.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtzjmmuwbf.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtqtazzlve.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtcgfzhhhx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtwnjqsdig.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gttdhkptkr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiaxocwti.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcfpranns.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtoapzrqzu.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtaiaptrln.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtkscobsxr.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gteedukemv.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gthfdjxcpz.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtlxyiqeij.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtwyfojdvh.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtotllryrm.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtzhkgrkwo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtovltnnpz.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtqvfudjku.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtorgqizuj.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtgaeciuwo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtyyovwgil.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtjwktxgbe.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtjgwrrfci.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtkmdhaymp.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtkqmdldys.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtkfrxriat.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gturrjsroh.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtcqrodltc.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtvxbzxjmb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtmqulmcxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtckqvdwzk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtayyuoaeb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gttyjimbxf.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtchfjejde.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gttpadcwro.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtcvptgxkk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gteztcgejl.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtwddxuttc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtfvnjyheb.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtsawspjyb.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtlmqsdysg.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtxqbvzrsv.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtbfvgxnqm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtogovqpgx.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtbevvwluv.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtwaxdixxh.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtwcnrqlux.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtgyrhoewl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtmakgfyze.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtaucvfszb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdmcbundc.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtkoztrchh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtsjwjmzmd.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtcamlnjdu.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtyelrsmej.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtwnacjkrv.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtjejsxbak.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtffffmovt.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtkaiaprwj.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrxlmbxmc.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfgtzuzwq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtwtdsgrmr.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtfmcbeyrk.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtwtdjqqig.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtexrfuevf.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtxkwoenwy.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitmyegav.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtkllegcbu.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtykbvvwps.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtvgatdlsk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtyfnwwvrr.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtwskdzwqo.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtehmkbcyf.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtjksyudxy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtagpktpbd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtyqmatbdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtpstzxyds.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtopegrfag.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtvcunwjsl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtjjpbcbic.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtrvnhpixs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtgkgihjtt.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtemvtqyht.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gthfnpgxej.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtmpdqkuoh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtlfneaaog.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtgsuvcnpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtowypwfcr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtzdddyiyg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtjfrxgwew.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtymxoemgq.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtlfgxwawd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtcodjiaud.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtqxqyzlyr.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtkaehyfhr.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkkcnsjv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtyozzelsa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtwndiapyv.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gttgbftbdx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gttsxkkrng.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlkpiuupo.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtylnwuzku.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnqbfdogq.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtxaugzwpz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtkqqmfqmi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtoaehqoxy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gticnmgjrt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtccozroge.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnesexvxh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtvnujyvdh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gthsrwdigs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtqqkyeaiw.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtseigjeqs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqmdirwc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtvhawnezp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtlnkyqgeo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtysbrhtau.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgpwcfmvi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtxhufsrbb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtwxqedxvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtmveoaaku.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtwgcaludq.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtlyazltlj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtolnphpbb.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtjuzokumh.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtavxyfgcm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtosgpnedl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtncgfxnsq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtcavwxgln.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxvwigff.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtmtrzvwgw.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtxdudrtmr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtnchjfygd.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtmmwybpew.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsshgwrfg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtzquzjddb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtdxkedatf.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqxefcje.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtbjaebqvd.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtfgqyqhpr.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtldhxlrja.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtevoitnnc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtwrxunpmm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtubwsknap.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtyosnoiyk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtejtfjsgm.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtgombayin.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtfhjvblfk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtwytzktgc.html


<!-- 参考信息 -->