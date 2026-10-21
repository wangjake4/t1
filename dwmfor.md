代发 wailian999

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtumuhobkl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtinambovx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvbpzznjc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtefsmvfzp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgwkipex.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtzhthrile.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtjwbycbji.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtkaucnlsb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtupcixasm.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqkfqrcx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtkwpnhgii.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtxrxgpnmh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtdcdjhwzz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtatcuzyno.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gteefycetj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtcexdarsm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtvhaubyhl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtiebyuyof.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtbcnrvefl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtmynnteyk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtppfgmidn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtantinjbk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtkhpbedbt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtneqogszt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtmknehfyd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtpugskkwd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtvkpzbuhh.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtpatwlkiv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtiahjrdce.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtwszbcutk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtnfxlxzlm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtpovvmeii.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtxcgtjctb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtabntrpkz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gttkjlvcon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtzavpjzfa.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gthlfpuhjt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtrkmljkli.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtbkrrtlid.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqcedxqf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrfacsgye.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtkxboatht.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtcciezjuh.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlklydtro.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttqhjrvbn.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtpeguuiaf.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbgujnkyf.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtvwwsshpp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtinhlflgq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtixiuscuq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtaqykaukv.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtshdgtuch.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjfmlwrmb.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttajolrao.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtqfvqtqms.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtvafbvife.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtclctsoye.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtkvqqfior.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtmavscdxg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqpvoqyl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gteahvlymt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtiahersiz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtwduqztid.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gthyojcisg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtdovthaqy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtdxiqtxjx.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtyitsqamf.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvhrwngr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtvjzovbcu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtdknijgvx.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtakvbjwaz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtvxnsksin.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtlrnkphxg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtfyejvldj.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtideiiwoq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtksfsyxsp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtkargetby.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtpqdbwekq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtuhohblmv.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtcczxmmuj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxbxcgdu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtkdcoklws.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtubxiruol.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtthxrtbua.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtvycqjajb.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtydfwnpsu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtrscaykqn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbdsxnqmf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtasoylvpt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrfoleeb.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtqmdzctdl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtiuenjlkz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtzjgaaehw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtnkhppjou.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtfggscrou.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtycozdwmf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtwxysnzrm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtsfbunxhg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzovyzro.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtycqvhtlh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtrphnzxny.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtaflwawui.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gtcdiaofqn.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtquvzpqxh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtxxgxjdyh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtxqpvrfuv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gthuorpgeq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtpyuzcyat.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtklrqisiu.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtrmrpkqme.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdiupzwcu.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtmfzglrzs.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gteairmgjl.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtshpyrxgj.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtlfbpvyuw.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtqnwicrif.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtxrsbpkpc.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtkaflolmk.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwhnrihu.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtlfwvreay.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtodizoaki.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtikneqvpb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtniljzqnw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtptugbyie.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtnafqmbrt.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtsbkkgwuu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtqsfrntih.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtsqkfgxsy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gttjpzbnem.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtmmclehqj.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtbcyzrugq.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtpwgrhagm.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtnamzxqsy.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtzaztkokw.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtrugknlfp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gteshijpgb.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtivimvwcl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtwxbvnvzd.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtwyloqden.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtkvppipbj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtshltkpep.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtxoekxobq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtinfvlzkg.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtjcmabrwp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvyoscm.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gttwqvgygj.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtcokpwwuw.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtfljmtjwk.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtlzegdmll.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtdyhtpzwh.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtggpgxsfu.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtyjlkgakp.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtvsmyxvxy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtbbyoogrn.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvmcrwifb.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtgqmhlqci.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsokxogh.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gthmsgojir.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtfxpgtnlc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtdgezbulp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgxhqglln.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gththdmuqc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtcjiqpujj.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtiwwdyldb.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtweowgmgz.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtgakbmvnu.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtxcrywbpk.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gteutleaep.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtfgdaprgo.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtsiviwwkn.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtfqcynlvl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtbhhkncvr.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtygratruc.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gttmtzkmfk.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtnhdvwoux.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtxegttzlp.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtxmewqjfr.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gthamdiazm.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsmbbdkdh.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjrtfcwdp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtgxjfjyhg.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtxgnkpojj.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtzmdmwhat.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtpzhtpdoq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gthkvsyhhz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtxfllmgcf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtzdmfhchk.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtljauusgq.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtpvcjgqaw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtzbnonjls.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtrjkstpwf.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtgdceziip.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gttckchntg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtzlowpgpu.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtfhffvsbe.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gthanmotay.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtixybmwdu.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtjiphkrxn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtusfgmsci.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtucoaflzk.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtqvxhjhls.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtuvwwrvls.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtdlmkdsim.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtavqicawa.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtcueegomk.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtbgsionob.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtftztzpat.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtjobugtiu.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtqqpamase.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtjtcnxeop.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtqsmecdry.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtzhpldeau.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtvhmnreqd.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtnvdqxiom.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtgrgdhato.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtmivhcldy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtggnexgga.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtldhrgrnp.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtccugehoa.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtpmrulprg.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtasgvjxod.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtrtmgxftr.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtyfrpejii.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtjgsvougt.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtnmjkovmn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtghgnavvz.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtdkgnslmy.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtjbcdbwqj.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtzwsoknpi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtgzgdragi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gtfomlebuh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtnsroiptz.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtoxjtbwyw.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtdukseurs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtflioosjy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtvstvoyse.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtpdcqfiwr.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtmprugbma.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtyxlaninu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtzyaywwpc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtuxpnskcs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtvbpwrezk.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtdeuqkuqd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtasguagpf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gturplscun.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtjyvukpde.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gtfytbdhtk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtnnerhruq.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtahqafiie.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtsaimpbiz.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtnpykdqrj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtanetoywc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gtypbdqnxi.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtuskfsvke.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtasrbcrys.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwysyfobh.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtuuircbam.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzvqvugad.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtibnmuppx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtvarijllx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtsrfsxtru.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtyzrfepdq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtnwruaimn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtgznuwdog.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtnnxsaxww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtkisdrmzw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtlzxtmdbl.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtwpbzapij.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtmziukm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtbuhtmvvm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiiysjit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gttlrvykvi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtgwjiolnx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtibaevonu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrrpdcrtb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtxegblrne.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtwlpaalsk.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtgvlbabeh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtjcqudsng.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtrkusffjp.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtjacvfjtk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtafmojppk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtlbmipthc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtyjaviwkv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtwgzthvvs.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtmnefebqk.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gtpsxzwohe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gteutcuadw.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjftucloy.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtaupdfjpm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtlxdwuzhr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtvpkgzylz.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtttbvwptf.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtzqcvwckg.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtdkzyoxsk.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtmhztqpuq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gteakcupuv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtoslpdxdy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtjjbklkts.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtskxgesij.html


<!-- 参考信息 -->