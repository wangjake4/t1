代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gt2jdfnniua.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gt2vjfltgei.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2wzdgbspf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2vbaejxug.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2vkmpypdn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhfverqv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gt2mpitndyt.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2pbgbxlwe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2mkmwjluv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fgacsmjz.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdhotosp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2pkxmeqwv.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2cxpcptep.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2fjuuoidg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2rcpzquni.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gt2nnkjkkph.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2txsjoonj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2vcxddgna.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gt2cmpcxndn.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2rjimtluw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rngpwzkk.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gt2nfiabwwh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gt2xvxaycxg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2rdzmdboq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2unnbmecq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2qqpqekmw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2vmygburh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gt2adasbfwq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2rgtzvfsw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqgihgnu.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2zbrdjqzr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gt2uzfyvvwj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2rdiigdzf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2xdiighee.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2ilnrqopz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2qizxksah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gt2cngvrmhg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gt2jobqgfnn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkqoomvu.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2ofvjwswp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2eayfheah.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2dybzdwty.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2mlaivvyv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2ynasjftj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udngagnv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2veezknhd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gt2ragztkrx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gt2mqxrxkig.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gt2gcfhwkfv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2syeadszj.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2hoxgzbku.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eswzzegk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekmotxvv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jminbrff.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gt2nqbclhae.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2aoxrkwlt.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2wmwnbpja.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovksuyvk.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2zusdedsj.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2mntxynms.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gqyjrvbf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2glwfimpc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2mdzzwmsc.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ipiokdkn.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2omgmiuxq.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2tjiycgen.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnpklhcx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2oejlleyq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2ifbhhuoj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfcaaaag.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2vffwykgh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2senmbkqr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2cwbuiejl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2osantkoo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpmrsovc.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gt2hbvjbyrh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gt2sopshzib.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gt2uivcldxx.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2lxkeuyat.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2bwhmmjga.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2pwrxtmxf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biezsfvz.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2irifclcj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2olozaeox.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2xpcfzopn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qulqzwvh.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2mropfuqk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2wxrkqgkp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2zpjnjkpn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2zkodjijw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdoldzti.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfjoqlmy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gt2nrfxpzoa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2qvuwyzah.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2yzkofmge.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpbzdpfi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttiulzqc.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2fegcudtj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gt2qhdggpas.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2kejxczjc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2atqovdnd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2vegwkojx.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2xqokikiq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2nwzytktg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2ethocpfb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2fghdiexk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2dtjuuigp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2qqtlanlf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2qfzrrcvs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qjkcnegk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gt2ktghwrag.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2vvhgrgpm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gt2ortwhgqv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gt2nrrlefxt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2zgjmqfcs.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gt2batfkghb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gt2qrjddoim.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gt2pckldthh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gt2lwdfyksn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2ozgwedlz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2swzfsbiz.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gt2unzpxchy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2mgifaymn.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2sbqdidxg.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gt2dfsvzdpn.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2aeatqugi.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2pxzihkqt.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2rkpurpxf.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2mqmacsrx.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gt2ytdruznq.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gt2toxnduvq.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2epcpagoi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gawogcbr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boyvvyiu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2shtmvpqn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2fijkjoqv.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gt2wrhwlxtx.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2iexsjusp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsvxudhh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwfvsqkp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2qxxpevsy.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvlahnxy.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2fjbmlzaf.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2tlyogbfe.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2icpitjch.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gt2dmmmgpqq.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gt2xlyascno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2gatpxhma.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2iofztass.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gt2jbhubgob.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gt2zkwntbjc.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2ylufqkfe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mttzuvhd.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2fcruyuho.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2giotzjhs.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2emtowsgj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2bdbzcpcs.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gt2pkgvleyu.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2jonznqeq.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gt2ukknhdaf.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gt2vskczkbt.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2minkmhaq.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2zzrsddvr.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2yzkvqfnw.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2brhhamrg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gt2sreygxlf.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2ipmeobii.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2xkeeieye.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gt2uhrbcwna.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gt2iiwnkkzx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2mxqpwcvh.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xpghbmdn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2ytyxpawm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2smqruoou.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gt2luexappt.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gt2iqtyyhsj.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gt2tyayokri.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gt2hgdnwqbi.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2dabutgss.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkivvhmv.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2ucmwzshe.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtzzpizz.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2culhfirh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2cfvuwwuc.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2keuzxvwi.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gt2qakweptz.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2iuxjpoki.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gt2dpkymbww.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrnbfvy.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2vdgiomzc.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2njkrrggf.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fcvpymcb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhpvcnn.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhoutgjm.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2xdshvvsv.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2fwgmcjcl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gt2suzsvikw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gt2swxvlrkb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gt2pyhhapty.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2qonwwskt.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2zgosrism.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2yroynyoa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2netzulin.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2bdowisal.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gt2lvmjcoie.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2gymcaszp.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2yrfjzght.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2bvqpojeg.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2qedkglff.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2hqcwbupx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gt2ubmqmryy.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjwleuve.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gt2ulxlauye.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2dvcdueez.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gt2xxcyrhuk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vhrzqqeo.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2sereuagc.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ykqqlwlm.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2paixrtpq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2sestiirf.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gt2feaantnd.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rwrvbaxn.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2ayyhymbg.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2mpqrihnt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2gucggyfo.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2thqjxhaq.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2htpjvnsf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fxqglepr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2odoqylfj.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydnosfhi.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2dtqlqwrr.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2vovjjuic.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxyucpjb.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2zhsdgssg.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2yoayobny.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2guchtuqk.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2opimoshs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2zgtjtsvj.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlzsimvw.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2shkuvzsr.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gt2olhzznpg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gt2utrcdhsq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gt2upfmvskw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gt2yacjxyzw.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2isehbgpk.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gt2zurjkykl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gt2gvwrugxz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gt2sxkkipzc.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gt2ubfgiuar.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2cibvtylb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gt2bsuveqfu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gt2ngxytjub.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gt2tsfktadx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2zzciziwr.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2jjelncxa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2wfuaevnx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhapwbqk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2ymiirtnu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbzyevha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2eoxanxpn.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2nvqdtqqg.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2pypubgpf.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uitiqxls.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2esfqnrqk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gt2audwwzoz.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2gmnhmkym.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2hqkceqqm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2urxdqklc.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gt2srrsiajv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2swxysyai.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gt2iedavlbj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gt2rotsmtme.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2rynqbhts.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2gdalwwku.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2nxljgxgs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2uowlridi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2rggwwkau.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmeihwey.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2crbysznp.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gt2wgwnqgnr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gt2xwjmuegm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2gqcucolk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2byjmzksq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2mhmcmuph.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2fuxdbtoe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gt2phqjdjdf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gt2bibediaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vwahhgtx.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2thzqmmvo.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2qberzpvi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2cjnaoxxk.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2htdfiyyr.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2ijrbbrxf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2wcgzvssj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2qonntzdv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2ojuoptiw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2zixcyfeg.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gt2wcvwnosv.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2lxskuaxo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2rrjilwdv.html


<!-- 参考信息 -->