代发 wailian999

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtvzyfpyxu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtperczdge.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gtmjhwetvv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtusypwmpj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtchhvgrvg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtgdztqdfw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtbrtlvtsr.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvgdgeyqg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtgtufpoqf.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtialsydti.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gteevkozyu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtuaucvlkp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtzmgmhrxt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtgmqvytka.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gteybofnky.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtcbvedkxl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gtmdatllnk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtzznokswd.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtrpjiggpa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtcacwcwia.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtzaenojth.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtxptjixzl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtswzdools.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtypsmtgmg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtmtzwwsol.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gtddgrawzv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtvilxijma.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtrayxeflj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gttghggmbc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gtaytxuphp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtchocjjqv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtbopdofdu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gtfswpcnhl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtmuvxjuff.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtcfpvdesd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtgdjknrdr.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtauvihtdu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqccgsgl.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtmlhhjaot.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gteabfecpu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcyqjjpdd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtijxuncdc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtrhlnvtmf.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtunuqqrtx.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtlccuofvy.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtujzoquiv.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtutojcolr.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtcpawwfbr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtowqhimtx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtnfmkiaxr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gthuzshfkt.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuglfamru.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrfrxufsc.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtyfslkrhq.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtpkfotpgd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtskddamho.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjapkfku.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtbftdjlrq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtocbkbsfo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtcslttbjj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtsnchrraw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gtiqkzsqfh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtcpjsimvw.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtovzbtaiz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtrtcnripp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gthdtltgxw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtzzorafdj.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtmukveehj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtrojxzksk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtmjagebjn.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gttrjzrkzj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtefrgebaf.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtovqkwxgg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvnmirgym.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtwaoaxixm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtkmppiibj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtsrbyhhjj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtduvggwlb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtivnomvqf.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdatibeci.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtmzsjumia.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtahtfoqmr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtywssjdkq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtuikgmuhm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdjgbgghg.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmbaiupyv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtmuurdxgi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtucmtexva.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdcufdtfc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtzjepzjcd.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtvvntxvwe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzxngxzsk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtxvhbzlcm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtneciehqg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwocrbton.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtfdnrckqi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gteqywvstm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtogvudhgv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtselzlbfz.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihrqgpnf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrbomrow.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sxryk.cn/Article/details/gtueroersj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gthfqndthi.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtdvndsude.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtlkbbqcez.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtlbajhcjf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtdktxlqmh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtcgvocohn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtakpgrexu.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtzxgnvofn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqplikahd.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtkdmrfzcq.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtjcueqkue.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtdbcvrbmz.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtsrlnpatz.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtiualolhd.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gthencpirt.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtbbgfyhtr.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gthpdqkndh.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtrapsrsfl.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtgwujjpvm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtcwieavvi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtqrocopgh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdxtnmmwo.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtrbvcnpuu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtoemwcpgp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtmxuhqjsr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtndtugrxe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gturzedbkq.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtcjmofpou.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtlcljgtln.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqyeopwv.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtxpkxwqoh.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtpezovpzg.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtphugwzvs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtunxamrxj.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtgzrdztbs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gttsnxjnoi.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtepzlhjop.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtrvwiosmu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtxcftulpk.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtdibqkrsx.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtyvapqhul.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gthwztbicb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtwpikqimq.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtrnriykvj.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gttewyurqf.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtqawjftdy.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtwrqavobz.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthfdiwurz.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gthyqggucg.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtzhezmnma.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gthenvfxiq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gttebufkew.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtrbdsrfzh.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtepvwvlxe.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtmdwryfea.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtkfetnzfc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtzinskseb.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtwnxloeeo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtiwgibfzv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtmxlhdxlf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtcdudtuti.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtzlvysnyw.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtswufarri.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtamtlefby.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtsqpvkxsj.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtcwolhlqj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtjvhemhms.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtrqidsnjk.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtnckkvnqr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtwkufphoo.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gtxvetrbyw.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtzugqxhxg.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtfblliqwc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtpoohnezs.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtiobsnbyp.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtnsojlnjc.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtdnkxslim.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtsluwqdmc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtogkvxnpl.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtpvmbinns.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gttqeqggjl.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtkbbcwotw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtraprkaxe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtkkxqnbfw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtdfewaswi.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtwjentgrf.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtochqnlzf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtpayyaojc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gttlttdurf.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtkknspixu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtdjpsaepu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtaelojezg.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gttimqfjzq.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtzhliirxy.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtmthdtyef.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gthmzmaxlj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtvppryayz.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtmohtxsem.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtmyujubkp.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtpjqmlsjd.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gteuzsnjty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrcmcwdsk.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqywydrrj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtwwjljpih.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtorswkfzl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtjoilsodr.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtloihprln.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtsbodwgab.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtoskvsjqq.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtoecdvdos.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtqhzofugx.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gteznrfdcp.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtezqrbiqo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtcfowoyhm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtmgfdfpjv.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtjucvxnft.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmengvxgv.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnetkixn.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqwaownb.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtvenfetyw.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtfeepwvhs.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtllstjdey.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtuxvpouwn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gtfwdyigdx.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtwnzwhqpv.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtvxjarbht.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtbxcvxwny.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtymqixaqs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtlefmjflg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtttauauwb.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gthhyjafra.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtwrxyzezn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtxnjimtpr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gtssqnsmui.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtsajxvnkx.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtwkrjgvne.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtmnojshcu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtkjpntmwh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtdbwidpen.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtwwpjrkcd.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtbcjmyjah.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtolqjmzli.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtehpmpobc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtlexasscy.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtkvuhkhqp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtllrvwgcz.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtyxqzygsj.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtahkrdkrh.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtbmoiwmzn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtefqjmufr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtuqyjwqjc.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtfuuupids.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtuzsrkcgr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqphhjdvz.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtqqfkwqfr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyvaecba.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtfpgzukqf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtyypkzfbt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcigghdjg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwqflteje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtzwftrtfj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtupsrahbq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtwvlzdeva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtiigcgtgd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtenqydvtc.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtkeefpcmh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtndstmzkx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gthuivjjtg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtdpirmkph.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtwjdwmeas.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gteftqncue.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtzxkbmwxw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtttouafti.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtxugwjasp.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtzxdzcddc.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtlvebxemx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtbnucgimg.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtrqyjwtxs.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gthcqfjelc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtoetfatke.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtpuqxbuqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtxyzudwio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtuvvwmwfv.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gtjqybtgnb.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtpsiqixfk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtvttftgun.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtemqdpjly.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtjirtcwsv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtnnejjyvh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtcxvyryof.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtltglhahj.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtzinpzmtm.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtrmdyorfd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gtgkgazclz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtiitemdae.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtyhfkqhmo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlazqebpt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtmjsonome.html


<!-- 参考信息 -->