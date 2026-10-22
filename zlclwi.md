代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzfsklvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2scohchfu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2xjmgnmxz.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2dymknzci.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2flegeyyb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2vwgtpgjo.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzqkljks.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mcrthjbg.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gt2otqbvfav.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2vthzsaix.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2qjlmuwok.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gt2razrbtim.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2tkfrktip.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2xztxrjck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gt2giknsstf.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2enfjswfr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2vtuwukur.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaquogkx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnbpoocl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gt2mwjnctse.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ugghztqo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2tpzhwrwd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2odnngjma.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gt2qqwfjqxl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2sivxvylk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hsnizutc.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gt2kxthvpoo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vehukqmt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2oycvftaf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2yjkouzrt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2cvktdyvc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byupayzr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2hbmgkvoh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2qpgewjzh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2stkvjeos.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gt2coxpfcnv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gt2nclpcjff.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gt2ayfnjyys.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2nnmnttoo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2tsanexoa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gt2mtpltafs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2bqrydmlq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gt2sqzlzsbq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2aolkugbu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gt2nocwqrne.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gt2wvvbcwts.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2swiiomnx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2yvjgixuc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2yrbodpys.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2hftcamhl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gt2nthnqjxm.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2bceehbzi.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2zqjxvlkf.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2rwfrnhfu.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zpoqbfmv.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfituxqk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2tjrughcw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vglqtmtn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2wnpsdmqd.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2rnhmotog.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2mpsoigbp.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2kexisnty.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2gloeigng.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvnysxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qatripzj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2vbchoaqf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2mdwjrzsp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gt2rjokjbkt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gt2vdtsizik.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gt2jfoxecek.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gt2yfurjnzw.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gt2ldiivgvm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangdashe.top/Article/details/gt2vpwciisa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmrzszvw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2loipbytt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2bmdtofzd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2leoipjnq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2xbljpxfq.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gt2atofraga.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2qbbovsby.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2ppzryibl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbpeugxm.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2lfdsgeoa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gt2nvcxvbip.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lanibelh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2mxcgdytx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwcgihab.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2vuzcwfbo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2bmgmoflb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyokqjuk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2lvgjkyam.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2jczsfuxk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2bzngbujw.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2blwanzbh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gt2hindgjdd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ggxxadtk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xljnsbvj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2iksplbjj.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gt2cjtvgdsr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2lfhnqnhc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gt2bxaywact.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2inxkztdu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2jvhmlena.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gt2ffvihstq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2ifyzzrwf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcxsjoxq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gt2avnqnatp.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2fzlqjals.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gt2dcansfrl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtbympfn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpnoudvy.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2ufgnmcku.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gt2crtfindn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2ytqvhfwc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gt2nuiwbqez.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2edokepqz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ogvzspqd.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gt2psuszlht.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zojpmvxm.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gt2vahviusj.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2ttmrxogt.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sghtswvx.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2lsnphity.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2frtfqxki.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2hekpdxqo.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2srhkjtsh.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2hjlitifg.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gt2vqnwmpeg.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2zxzdwysu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2vlapvrok.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gt2ynttfkvl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcyehrcf.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2vfshmqzm.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2gmfywdju.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gt2lrtexgbd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2wbdzuttw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2xajaynqd.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2ydflfiti.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2anpxwany.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2xytsuspj.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2walzmcxz.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsbfvsne.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gt2xdolicjk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gt2gssxlxix.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2nptommon.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gt2htcskykj.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gt2gkrgvrxh.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2pxpzeblu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2vorvdsml.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2ycmkpkxt.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ydfyrgvz.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2kclawjma.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2ihpdksjh.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2xdihakpm.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gt2ozthquun.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucocyidi.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gt2alayofsv.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ozatfgik.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2jjzlwgsx.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2tkodgwwt.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2xmqkdidd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gt2dnuxzsgx.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ceylocjd.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2xnvmacat.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqymkdbk.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2cvnkkgtn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2xxgwpsde.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2jiimnhrw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2hykyidpu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdnydsdr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gt2azwiijvr.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2enbcmixa.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gt2zyhgdcbe.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2ocrscvpi.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gt2dmfeukuk.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gt2ozenhjhf.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2jfxvilya.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2tltvpdhy.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2wwqulsal.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2imgbettp.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gt2dzpfjaqd.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2tqphkjyy.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2uwskrfav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gt2atyoffyd.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2epdomjwf.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2eyhejoly.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2huhrocwl.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2zjsjkezf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gt2ngevikcb.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gt2jteftljm.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2bqzuyoco.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2etuiecyu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwouyvyi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gt2eylkqhor.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2czkusvbo.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gt2tuyjfkca.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2xnpwagxv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gt2kthcallq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2kvmabxip.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijeudqfx.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmugzfmt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2cydrwkql.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2efdrrmxc.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gt2saxlvytk.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2lcugtmmw.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gt2sgyvydup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gt2xspybbof.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2etxbbgjd.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gt2ggouxsip.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gt2rhwpwltu.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gt2bzjvgwjl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2jopdohgt.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xoxujxgu.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vglgmnek.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2prbrtgak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2kzqrjfvh.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2lqurlcca.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gt2lxivsoei.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2tfowqxtj.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2czjabmgp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2bmrvwwij.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2auyzsqbp.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ykrernqx.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2myduptqs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2pkobutqx.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gt2egjqsncy.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2ktnaratx.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gt2vzziyuql.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tahmygji.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2byegutwn.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqqebast.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ynlhyaty.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2tblnobtu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2svfhfaql.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2xuztzxuq.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2skmwrpay.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gt2zftvdbif.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gt2exkwqufa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gt2nromcdyt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2cqsnbyuz.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2nlrjtjab.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibqdfgrk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2hwuapfci.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gt2bcdatjdb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpwnhdcy.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2lnghhnpg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxxhdbco.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2mgmclvip.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gt2jcddptnq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2oveycfci.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gt2iovrjjaz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gt2hxcjfqvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wskvnwrp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2ihksltny.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2mbayubcj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gt2iexqnhea.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2hssuttxr.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2onrxpzew.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2dnraefth.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2xygbenao.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gt2izbiucju.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gt2cmoyegeh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2xcwrsozo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2lqnbvlwu.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2rpfbywwy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mhwdriyk.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2ptifdrle.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2nyntmygm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2toomspkp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2vbsnzrzc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckouviha.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2ymazwkun.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2kbzatoms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgbczzxk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyzfsnoz.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2jhqsrami.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2qfrbunbm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2ayxntjqt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2yduoefcl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2imnrzuid.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2qafbzjnl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2vtajfdwm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2kovlhbuz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2bkjccvqk.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2ptllkndd.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhbvplnd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiwqvprv.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2bzdwzlkk.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2vgqncwoj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2bzsrgcyz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gt2afduicwy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2bmvrlixs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2rirynreq.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gt2gsdyswmr.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2cjssobmp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2casgmwcs.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mbxreuil.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2edyixxfk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcaajksr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gt2yyzvvoqz.html


<!-- 参考信息 -->