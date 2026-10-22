代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2ccrkgqiz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2znofxukc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gt2kdvjthbw.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2brwrglsp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2jkvpcizz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzyrkyjz.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gt2uhybqwhf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2freuuxjj.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gt2mssbfenx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gt2yloaxeam.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ilynrhcr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2ltcwwzfw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2bmyoykdm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ycsvrvih.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gt2uxruxqop.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ztmwcwao.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skiwaick.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gt2beeytzvq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2zrjgvazj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gt2vavwfmxu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbbxeeqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xfvhwzlt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2ojcmqtju.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gt2uwataasv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gt2xtcpwfsc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2rxddcowh.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2vmgsfyfi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2fsnstlql.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2kvqjencm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2cjyvlaxz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2rxbvdqkf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmyvtpbm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2oibfpkkz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gt2mejcqdlv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2aknodytr.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gt2kvacbyfi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2xhoeltkv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gt2jucuinpv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2ydqvmejf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2vlvdhpxf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gt2egljhycp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2gkrhirzc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gt2vmbqjwhd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuiwqqjs.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gt2pejxlats.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdztdibq.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsjamvjy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2wpjjgtrt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2flhmxeuo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2plcxiwzr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gt2rrfesynj.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2uiqefvxj.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2oomarwrl.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gt2ijxyksaa.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2rkdnrpnb.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2grzntdav.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2zfnusgqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2olnxhhyu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2nrfyszgv.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2rciwijuw.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2fizovcbw.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2kjhaambe.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2kfcufjsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2ractmwbw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gt2ldleblir.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2gszjvkzk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2woayvsua.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2vqnxafpz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2edlirqvm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gt2geakutdt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2bhrqysgi.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2wwwjunbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2zficzbdi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2txjkyhby.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2loienshb.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2iwgozfph.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2qtvsutti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gt2anvejurp.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnjuefsw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gt2eveyonfe.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gt2yogeemov.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avyhmuzt.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkrbbxuk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2hwcbinkg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2sxpjptod.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2aubvgkeh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gt2jzfulozm.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2rmwpzvrj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gt2vbtzxvbn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncnojiov.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ococtvaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2ynuzmbqf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2usxrigsb.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecosudil.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2uaylemqk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2lmqfkfxb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2issojtae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2hmcrxusg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdjqjrn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gmxnxvgf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzgzzxcc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2erfugail.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2dpkkmufn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2hgofeofb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gt2qhpsbmpl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2psuoemqw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gt2rxuqoosq.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gt2rkcuoagg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2clqfwxqd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gt2hjyccpql.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2nvujrbsq.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2zyxetnpz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvmrgmje.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gt2saqntseo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gt2frsyamxh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klafdfsu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cjovcyfx.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gt2yjwerync.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rprlufil.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2impfuzne.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2fyfynmcz.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2hskwabvo.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2elamrsyi.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2zugfquvn.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gt2sxamgorc.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gt2mzjgozus.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gt2urkcisqj.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2jgjuxylc.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2vmmkouyk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2gwypddcx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gt2ebvsgvjz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsqfirzu.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gt2gnrsgqjx.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qymevgtr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2btwqlebv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2brlnhubl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2fkcxloie.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gt2hioswlrl.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2uiitpqyq.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2jltwhtiu.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2dogzuimq.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gt2tlaqfhoz.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gt2ocgtdqko.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2kejwkkuo.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2yitobake.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gt2miuaavea.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gt2gnoqazfa.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2szytzdxj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2utmezeha.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mznadxlg.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2biyynsuo.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2qiqfovpg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkykpuly.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2reiiunep.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxmlmsll.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2umwcvqvs.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gt2kyrxoglk.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2gcborhte.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2lnlwipzm.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2frphqodm.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2mjrttiek.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gt2acvlwfew.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrrfidux.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2negvoytq.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gt2mwibfbwo.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2ogbmikov.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2muikiwvb.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2muwcmfux.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2tinhktqw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2hwffwian.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2zzpuomii.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gt2aqswhnmh.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gt2vwexkcsz.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gt2aklchubg.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gt2ekyfoepm.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gt2elrgrwfi.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpkscave.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2womhhroc.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clxbgmzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gt2vcogmtgt.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2wxcfogvc.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gt2udnvbiek.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2aoiknjjd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdiivqsq.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxznyzlk.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2cdgptiuf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrkxmdp.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2wiiaoxqo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2csdkuzqv.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttrypvec.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gt2nvvagfcn.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2lkbsdmdg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2bstjzpnv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gt2okjwpovg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gt2hdnivrqn.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gt2dgwtqhsi.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2qissvmzi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gt2inmygeoc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gt2ikiowxum.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2gvfhvbkw.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gt2adqxchuq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2ymdufglr.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2bvjhrskf.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2msvgvtat.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2oclkvgzd.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2qvxdilgh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gt2dzqpsocp.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2vsiymcin.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2ghywlhqd.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gt2ugvbwlgp.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2lskxmoft.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2njssxqlt.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2myjlxetk.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2nbzocvsz.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2ggjrxytd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvjbezed.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gt2jhrjfsme.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gt2fmsasivw.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2qjzondaz.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2bicvwooy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kmlepbvq.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ajxuatts.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2zoqwwccq.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2hkaximnv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqvrzebl.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxkjqjez.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2zcsfkuwz.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gt2ymhwyczo.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehahgjzu.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2owzcgsaf.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2xljgzuzn.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2uslunhio.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsbkuldc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2zyosqofc.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2pjuibznt.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gt2eyoynwwv.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gt2hrjvelsy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gt2zgibulmr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2wnuqzkbw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2aitvdpwb.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gt2fodkgibb.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gt2xvwlxmpq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2bboxqisl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gt2wfyerfft.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gt2fhqjcvgl.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2qhkqqoua.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2wkmnaupi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2ewvvducd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gt2bjhxjwad.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2sxoeifsx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jttahefs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulosgdjh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gt2iaiertlf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsvhhxqh.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2ewnzeyho.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2wiredhtf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2cowbdfxy.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgmiugky.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2snjnejwz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2dljincjr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2autgovtc.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gt2oabykprs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfuzgfzp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2hsbxdmei.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2pqfjqxub.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ufawtgmo.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2dynzposd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2wnfhimib.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2qjgeqfip.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2ktimrikg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2tqgevqoq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgezvord.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2whdzwrns.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gt2oqzrflqy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2xbshnvfa.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2ijqqhiat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2udsubxlf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohgnehzc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2nkycenso.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxhiniih.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2ewcdrvpr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsjutinv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gt2ovtcrusa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2wpaqzlqp.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2ordgjyjb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2uqvdgmnl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2qobexqcv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2wkdpqbnj.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2xayfauaz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyhktkqz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwlkxlxf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gt2aodwvhly.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2gsgsfsgb.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gt2nscgmyoj.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gt2tysuetwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2dlhuqwwl.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2vjbpcjln.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2cirjqlwi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2wrvdadhz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfxwacaq.html


<!-- 参考信息 -->