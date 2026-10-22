代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtymdsmepe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcoapqxfp.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjbzqvpq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtezmbfzag.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtekbpvyfp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtxqllxkzh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtruccpvnn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtmdixojis.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtvpbccwdg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gttrurmutt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gthwjrzilk.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvvuiqrdj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtcfwhulwk.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtrzltjate.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtowiqojsw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtzixnnkhp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtzimkridj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gthwliekse.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtqztqmjuc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtrypnfcja.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gtkbresmna.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtobdorlcp.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtbsbaggnl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtnpltujli.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtaryhlvgd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtdfazrrsw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtoiqllbtx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjlxgywi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtifvnsbiy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gthydtjcgz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtfjxrympa.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtyowjinun.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtqiwwusus.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtswrzpdws.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtnaqfgipf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtaidtipwg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtkxaqxprb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtwkisaynu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjwtthql.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gteklyhkfk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtvqemrwgl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyethnvaq.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtdzecxbym.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjartcadd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtagzggdqs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmrhpwtzh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtamtnhywq.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcsfawyev.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtyemtgiwb.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtfgkvwwqz.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtusqtucvf.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtispghfyh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtnfbpfxcz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteasousol.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtukoyxwrg.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtaqdarssb.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjeoofiva.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxghykvxk.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtalmoqnwx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtywcolqvj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtavrnekeu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtjqbrrdpn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtqgwdytxq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtcsmyosak.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtkzkqmrot.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtqysmetgw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtxpzgogqd.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtdntajmdf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtkyoijcwq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtzczfyucn.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtejueotwm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwudfmha.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtmdyyedje.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtnmfilxps.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtjqcjnwhf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtudyfpjcc.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gtvlsfctwb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtifuxrczz.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtnnnyowrm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtbbvitgit.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtwfwrmgdp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtqeawwoon.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtrhigktir.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzddslwzm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtdtlwmxbo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtrkizxilt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxnzdadqa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtkhrpuidg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtemdsqazh.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtdpqfqrcs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtgfmhuqyc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzzshowjg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzpkjywcp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlfnqqpsv.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtotnhnsfw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtmeytwoyw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtzzvxodmz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwxxwutcj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtruewlqtc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtecryckcb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtivnegmya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtkzuayytz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtajffyakv.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtwhqeepbm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gthjfjfumv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtsjehzqnn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtmzvjtmgh.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtmwlbbpni.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtwqmmwpnz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtwqzwjmkk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtnznhrjbj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtnrvjzubn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbakbuhoy.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtilixhtng.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkgqlnpeo.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtydlgkaoa.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtshemnqoh.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtavuseulo.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhadmufe.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtsumuwlie.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtartbhgqb.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gtpysyxikk.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtcnhqylly.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtrurgaepg.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gttpmydyup.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtljqrmhsj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtlowyhgma.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtkfknfjtq.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtzdmeapyk.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomsqpsai.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtxlknibwu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtmrpxwozv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtpefwdrpa.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtkrnsrmti.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtxdyjslwk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtqqqmpefg.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtaonsrqxu.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtvfexlcfn.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtydyucsan.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtpfgqhhct.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gthjhwedru.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzoaouopq.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gthocpgxpq.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtvczlidlz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtdljikepb.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtudzsqqtv.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtungihoht.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwjwvwuz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtmxklfjzh.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtkuncysbb.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtgijupdzb.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtytroodvu.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtnmntxdoo.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtvsxcjcie.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtlimcklxg.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtbbfmhitu.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtlnyiehrq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtqwnsgmnq.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtsotisviw.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtwhmuntgz.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtthefdvwb.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtofjwabdm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtepzieuie.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtcfxxloon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtmwbjctwc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtakvxhmaz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtefsxzniw.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtlfwkxevy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtnuvcogfp.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtljgszqkx.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtjursvxer.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtvlxgcwzo.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnuwzjtc.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gttuouakev.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtcrpzedak.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtjyynfuib.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtskaqgzut.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtnhfkgzgi.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtopdeiird.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtpcwyfxdj.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwjruaul.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtdjhgavtf.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtozlcwasj.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gteepngiwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtnpnskhku.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtuanaxtjc.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtzpujupyl.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtoqoxggha.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtqckcpwzj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtrcwjbdhe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtjoykhgqq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtfbbvicax.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtwtzucsaf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gtykgxhfuy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtmmfewfks.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gthduopaqe.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtoehsjeze.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtnyvktabh.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtberbmrcj.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxjuqtam.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtqfquipcn.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtwqcwytgi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtrqssqasf.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtntkfxjxu.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtzrzzmpxr.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtmwctwefw.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gturuhtogl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtadmzstfn.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtzznxpbcj.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gttpnlcldf.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtlskutrdi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtizveajdg.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtkpjqwalu.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtfduwlwxx.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtucbvtbqx.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtesrcqbir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtfkanavrq.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtylcjigqv.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtxxwugpcu.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtckkpqxod.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtbhzrsakw.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtsfiiyfmb.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtyckvagtz.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtethjyujc.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtiviyhdhm.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtqayxcips.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtbemungfr.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtpgnsbibk.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtuelejlei.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtkazjixzp.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtyyxylawh.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtyljxolyg.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtuqmekwlu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtymjfvbyj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gtiypftqwg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtfjpkzifb.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtdotfdchs.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtbqucyvth.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtvcbdostc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtcckeozet.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gtkrycjfei.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtxmpbrwzn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtodyapier.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtceqzcncc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtgmnfzmpn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtbhcflorx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtbwkpcawt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtjazehvtb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtatfzdtqd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtsznbjtoo.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtsomngdgm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtgqrufsvw.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtriyarrte.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtapsvqwot.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtigtbutxn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gtrqfbilab.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtdmzmymtr.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtchalauem.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtfjdvuabw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuyvkcfci.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtdtxbpspc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkibwpvxz.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gthhzfszel.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtxflmdpyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtptrkshci.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gteoeiasjv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdtgpazu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gteryjbsrv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsfodfdy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtbfcqkdgv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtqxhjvapp.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtnjgswhju.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtvnrgrjvw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtgmsiisbr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtlyrmcvqs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtkuvcmudp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtqumlkhiv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtcvsygmim.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtrzotqnav.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtylzoshad.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtnfqaoezz.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtexrxrjhg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtejllfwqq.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtaphnsucx.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpguwswb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtpmgyuzff.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtcxzivzxk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtqsqfmcao.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtdyovazfg.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gttviyzuds.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtjzmmevno.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtcytylkvw.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtxldjhqqu.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmjptxktv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsictamnz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtxeriuole.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtxzyphfuv.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtqplcimor.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtaurzzodr.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtbmqrwpko.html


<!-- 参考信息 -->