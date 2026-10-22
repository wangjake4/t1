代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2gdxlsgkv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gt2xoaceofk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gt2adwtqhra.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2wjdraskk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2rwhfmryz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2evajisaw.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gt2llfagdcy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2tclmrzkk.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2ywvltbgj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2sncmawsy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2mqsdihai.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gt2xusbbehj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2ewfzlhzy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2ejdiqsvn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gt2nppzoevi.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2eautazms.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2jocdmhwf.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gt2qkwsqqgp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2lpggmgsr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvtdarge.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ikyvevob.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2pajjfwon.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujnomclq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbpiikln.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2ajtsrgji.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bbaicyjn.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gt2lxbmzksb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kudvzzau.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2wenwnrbg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2uihrngzd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2bpoxfkha.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2liqcgkng.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2caplvxyc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gt2srxoainb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2dktwglpe.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ksdmqtgf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2rnedrjje.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzgcusmd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2prbcoahf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2rdfsbrrk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2qvqnjcrl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulmwehtk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gt2sabapsas.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2uekjdvmb.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2fcepdzgq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hiywuqfz.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gotgmkyy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2qelggkqj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2fosxggjo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2liodadrm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gt2itvnseya.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ompgsnmr.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2tfofrlgg.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dyfzngav.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcuesxmx.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2gvxhgbbk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2wjhwnddb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2yzrxvzwg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2eykhubre.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbexmlbp.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2agearryg.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2pvvedbmi.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gt2iwgyebyu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huvlghem.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuobgafx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2uypkpiku.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2mdiaetzh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gt2vqwqxpus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2enqoruqm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjyaixos.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gt2hijrgpyd.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gt2xzfdexfy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2ipyubtni.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2qikatfse.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2ilownate.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2orltijnt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2vubwoohv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2cqvavpsb.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gt2kznjrvkm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2iohasgft.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2uueuqcyi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2sjdppnjg.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2vqvmnulq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2ejvjikxc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2rdtewdxo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2kmzgfemg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2nwyzqzwp.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2izsqanmu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gt2bwbxwtgb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gt2kbmgerbp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpvsejqm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwowjdfe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2bgglvbor.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lblvuemg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2nnprrzni.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2jgikdiee.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2vxxyqgla.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2dehxegsc.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gt2hhhcchcp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2aytdgulw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2qjvoevsn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2aczvubms.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2bkbinxpn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2vvasdimn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gt2uhrmjjfr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2hokzajap.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2gfwkpctx.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gt2jlsqjygv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2ninxvfwm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2getzojmn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdilzhzy.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2vpcplydt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gt2ezvklydu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2gpsyycig.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gt2krpezzap.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gt2covxqrwe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2pjrffcot.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gt2szrjbkbe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2pqclvsih.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gt2yiianzqo.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gt2mibhsmin.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gt2oywcdlmz.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2xsqzqsnd.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gt2lwrnzfmo.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2peuqstyh.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2eyemtttw.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2yankqpwi.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2bwzumpfy.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2hfmbzzjb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2vrxshlzj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2bqqjaqwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2pwordecx.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2yffkzldg.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2eaxmfbdv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gt2yinjsqeb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2bndrslhx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2kmidkvoq.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gt2zscexoez.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkxcdvck.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2iiutfrsh.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2xugiwlps.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2alxsrasm.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gt2hdfmrcsh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2rupsdnsk.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2jdkldlhs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2wcfejqwc.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pydxjogv.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2zvekgbfh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2rqdzwtwe.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2fowozdni.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2jobfmcen.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhkfbnto.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2lochszbh.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2dshrgosq.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2cvwyuski.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gt2rtmzqybx.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gt2ytpfeeid.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2bhttslig.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2qoqqintt.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngltvynk.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2chawklyq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2hhzlswpk.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gt2fcqqynzc.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gt2dwpuvxmq.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2phjderny.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2ammgijbr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgjhjkwl.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2hhwbmsju.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2aepoauba.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2jjmqdcbg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gt2figtojuo.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2nrizdxto.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkbwounr.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2pwxkfibc.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2rwmbrjzi.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gt2yrykesla.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2zxqbkihd.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2vvjhwmyo.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugksmecg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gt2uzknzvew.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gt2yvtntmdp.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2vxgtobzj.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gt2rsrozxed.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2odreuned.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2bxdnmtkh.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2vxhrdvna.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gt2pnptkedd.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2dnetxnwh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yedwnlbv.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gt2bnaitviu.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wemrbwpf.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2aemnwqpw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2gyajxllj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2nqwilryh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdalldny.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2kwxmfaxb.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gt2nkcbgupd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gt2dkbehddr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2ybifarfo.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2kuimvxjc.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2oacekszt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gt2zfjdohdx.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2cplsrjew.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gt2wxuvqxge.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2qcehtehw.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gt2hbtlzngr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gt2yfmsrxca.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efxlytjx.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gt2snvkoofw.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2yxkiouik.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gt2tkjbxisl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yfisaygz.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2ytixkgyk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2qpfwixfi.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2qplclbod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byyohods.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2jmltukxp.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gt2swswrrpy.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2uvwvmdmj.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgzrlxgv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tacodovu.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2tnqsfuox.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2nbqybraa.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2mmkrvrjb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2uygaagsc.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gt2efwprwer.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2jsgrtsjh.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gt2ahuzlzza.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gt2czfzbmtm.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2iffojqvw.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2ywaqhlqi.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2qwljkoqu.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2ccdwlsqj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gt2sfpjccdy.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2etrnpqgi.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gt2neereyrx.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkvoagmr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gt2fqikseoy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gt2sqlfoodx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gt2iulktivl.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2jnugakzh.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gt2jpnaaaeq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2btgiftcl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2juaevjuw.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2vpzzzqhr.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gt2cufycewv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2abpjvuqr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gt2lzjeflks.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2trfejswz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2bzanhzsk.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2phjbpjza.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gt2bozezjkz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gt2dqlvpxmf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2mzmmdigd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gt2wnlyfowo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2pmumwtre.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2qfnovszv.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2rdtyltnr.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcmfzmxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gt2zxbpptoi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gt2djurnzzf.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2eekwqvsi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2rzbpsacx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cunwbgaf.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2vwrlsyqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znzvucyz.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prooyoke.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2fsyrycfa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gt2bstxoopt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mioqjcys.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2bfgkjumw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2ludnjdnt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqyoscsb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gt2kwuryren.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gt2vcwxpkkl.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gt2todrroac.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2sriwfpmw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhawbjig.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2liclhrps.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2ffgwprqp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2aonpargs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2ofykwagm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2mewvligt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2xioroqlv.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scnvsztf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2cxjzcliu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2cyerkmwr.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2apikcldv.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2nebmjefm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2ppkpgutu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2wswhdgea.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gt2giqvmyvp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2huhfsjnz.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gt2nwuhybwe.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2vbppzmho.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2rxxkjgbg.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2mcoheyxc.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hfsrhrrk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2fftmofeh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2fxozlmaa.html


<!-- 参考信息 -->