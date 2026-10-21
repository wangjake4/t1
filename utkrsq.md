代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtvtgqpwgs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyohnseb.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtuycnniws.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdghcwpqv.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtcslgxjyu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjhgcwyb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtfwewyeol.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtkgfpruvh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtrnkwsfsm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtsfkintxy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gtgakoirtw.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtkylkdjax.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtixckqcvt.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtgwvgbxnc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtlodxrucx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gtfnxaklji.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtixovlxla.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtaetysubd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtpmttcjsr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtngmklmjl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtkvxearnr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtrimnouhw.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtvvdvvplk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtcjtswmkz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtnchwhqim.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtfmryixbs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtljgwrbnl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtolwgxhmb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtdztgarow.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtyzsvpnvc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gthqfuuatp.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtzzvcugiy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtdpdnryhc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhivkvja.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtxcpzubtn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gttgpkwizl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtkozqhtid.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtsjcsluhz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtqaqbpois.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtzbdkguaa.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtrgadhvyi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gthfqjgjtm.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtfapzpgxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsmjbnnsg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtscutgmrz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtdfxwehux.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtgsooqfvx.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpmgpynlv.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtpwytwsmw.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtixpeghph.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlqkzndic.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtetbgnmtf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjpfaujhi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtikdbrojb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtobwxuiln.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtbjhfpdzs.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwqfvisxe.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtxlqlrxfv.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtmtlhlzmn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtkubaymum.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksbayxya.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtbcmisucn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtblpgxfwo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtidnihcny.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemucuvrn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtpqsnscju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtqohxrbrk.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtcvhnpmsu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtiqaufugb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtwmxqjsoi.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtzuejjxwu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtqlthobya.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gthbaplpyl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtsemsltga.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtflnpjrby.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtnyfagnnz.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtjfmojjws.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzmljqmke.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtuvjndjzd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtomxnfaqa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtvbugsfpj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtwlhmzmln.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtvpzxqt.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtwqdjgbnr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtvupwxvrq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtdkvcyvbz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwodolliu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtsmiwfvwk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtdyqfutqv.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthbfrgcfd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gticznqzxz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtipesgdpa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtyrioyezt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtxiljyvti.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtrzswztqx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtmpwlcmvo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtpuaqgfum.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtitqtcnfh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gttzvbpzfa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnfqmmnjo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtvomptkio.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtusbxuipd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gthuqpndgm.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtlcnhutpc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrluctlc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqztgfqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtwwxeclgr.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtalhyvvdj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtslpiycup.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtvztyckyj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtqipeduya.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtbpekfwnd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlxrjshqa.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtwdyuhsbb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcjmbjhgh.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtndmcxtap.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtdkjpnoyo.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtihmuzdgg.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtvboyghuz.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgfgeejw.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsyymlgpd.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtcqirgwrv.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gthbonzjlx.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtddxlryzg.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gteyaenpic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtleghbhmx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gteaerhyrg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtqjfvcfwa.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtqibpbmsa.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtrbwwhdlt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtdlzxfwaa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtdrjybvsc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gthwaxhtqw.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtbkhjhcmy.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtjnvjcbhr.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtqxdfkqis.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gthgjninbs.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtruihpues.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtpqpbabwo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtgxyemgzs.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtcvmcbbst.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtmsmksqby.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtifiostxz.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtgyldbjwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtprjtljba.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gthetemwjt.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtrnppgoer.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtbenwvknu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtzofkuutu.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtcuiazqib.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtdybgzlnd.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtyajlgbbs.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtaayktybv.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtrywmvhox.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhcemadi.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtkecsqsqu.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtdhfgqulh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtatxqtiuw.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtoijqxjvx.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtbwntznzq.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtnmlbvpke.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtuhtavqcs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwfkujsh.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtgfcyycyd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtpyaylail.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtbbkzjeyf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtbaigkzbs.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtxsbwlgfi.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtgvlqmytx.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtzixtdwnt.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtrygzptlu.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtxnsjqpvf.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtwwrgnbyl.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtzmktrfbi.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtcjoggtwe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtrqlbflpq.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gthwyslhgp.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtbpzinjak.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtcsaokdbp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gtfpbjtjbz.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtsosvolvr.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtrvxwyuam.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtblqatyaj.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtfzrrkjjv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtrharhunl.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkdfhdiow.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmipyqgdp.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtemjelujc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtcnreqyxj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtbxayjpel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtvcbtpjlu.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtjtixobjh.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtwpqietei.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtlwhfhowl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtgrjqnwbe.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtkjpcgimd.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtwwgstgyj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gthvazwuxs.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtrbopcrfq.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtixsqanab.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtgzfyxkjz.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuigadihw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtpkckchdd.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtxmeppbum.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtlefmqumi.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtlpywpdmm.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtytyhqhdb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpxgsxykw.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtfwemlgxn.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtfyryomlr.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtxyukjbel.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtrlxluvrn.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtmbwtbrey.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtngbysaam.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbdcslfk.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtodvjfhzh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtttukwmrc.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtnbncegto.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtrafmexgi.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gttaflwqxs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtrcerrecs.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtgrbqzrws.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtbmexerfj.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtfgccfyvt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtfavotcmt.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtgusstzfo.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfzaheus.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtphyblrhu.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtkppukxjt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtbdxadoko.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtgpynoorx.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtcjczwfde.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtgregacmu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtegjpxusp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtkefgwtfk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtslxthymp.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtizsvsaks.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtqjjsprof.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gthyhlzqjr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtjmbkqvvo.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtmydpikpm.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktkswmem.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtdrffxtdi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtttvbhziy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtvmhwenep.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtalchqwku.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gttrjkxwhq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtjcevrgcy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gttjxscidc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtmfekzsbq.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtgybkswjp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtbeumdbfz.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkisaezrk.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjyaopibo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtaxkhjeyg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtctrtluhd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtjtuanier.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebmrnnwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtfeysbuot.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkkmstcor.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtkpjhpmkc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtswtliahf.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtbeidvgar.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtzgdnjpke.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtdaxzklwx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtjkwcuzls.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtkzjilkun.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtaznmqhtf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtzuzxfbed.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtqfbwprrw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtscbbvlxr.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtevsdrgec.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtvuurstka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtmesdipwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtwqnsyoak.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwidybdik.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtyeklenzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtnrkbpmvo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtenhxmnyo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtxwzqlslw.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtmpeimyov.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtbausrzdk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtghqgaoph.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtxqhfnbyq.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtmubrinpa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtvwfpduja.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtkhptuoxd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtucdagavs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtjxiskzmc.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtkrwycyvk.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtfgiubmmv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtgtjmfnqc.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtgrmlxdmo.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gttagqwihl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtrgzoqzzk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtonucfcli.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtqgiqynjz.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrybvlvy.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtipfgcjer.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtjyasaems.html


<!-- 参考信息 -->