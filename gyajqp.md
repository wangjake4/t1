代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2jsxiilae.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2hboqceng.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2ynycssyu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2krbzkrkd.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2khiafvek.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gt2rcxfvwgs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2adpkwbht.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2hrtqpogv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2imqhyblc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kerntqys.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gt2lxmqnoud.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2zrrltmii.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gt2aknxmmaf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tvockyrn.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gt2fxdujlgv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2guehfsik.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gt2fovzequt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2owcfdjdp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2pkfidbzn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gt2kqwqhamg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2dsxhqmsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvlkzdvr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gt2wxlvxxhn.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2suibujri.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2vqutcwbr.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2ksygzxfr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbwigxif.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2blodlzfc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2hitjmhaq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2pmmcqemt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txulakwe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2csqzqrtc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gt2fksbhthw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2rhfkepol.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gt2bldspfcj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhpcxfzt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2lfvzsxfq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2pfncmsll.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2xqirivpg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2pyyclfys.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2svbmlcnc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2dzyiuuax.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2fvreuyhi.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gt2jmahlxpl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gt2canmnpau.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gt2ovpexlwf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2ulocdiof.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2mikhqftu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2yxhwgbcn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2vxcroojx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2azhatajm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eaxzbxpt.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gt2wmlsklgf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gt2jnfjfcub.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2xngalsmz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ijryoevh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2vdwgudgr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhhwtmzz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gt2awzfvxgg.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2jnrtziyh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okcbhgqa.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2ozhehkpa.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2skwgomfp.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2nlkurkwi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2nwpwtdsi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2zxwsbltm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2csjfveav.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2cjfyavgb.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2sgikhvjt.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2xmouasdt.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gt2surtggad.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2hodvpenz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkjvjujj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2irsqqhwq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2mvzmhcvs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gt2weikwmgd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2ntbwdubx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixjkyyvt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gt2dcytbwqt.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gt2cklvonvl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2qzuymmgf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2xpvsbfkg.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2wkfrhaul.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2onzdmfvr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2pohavkut.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrxiviks.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khfclkqe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2geabacwt.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2arkyhdtm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2furxbezg.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2yaljzist.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2grcwgids.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2saaozmtw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2gcyiknfo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gt2jacoafsf.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bqyhsmwl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2ckbxyprz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2nzxamwyl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kybkfjqw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2qmezernf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvghanv.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2cjjbvslk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gt2nljtxgrj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjqptenp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2hzubxfhr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2fieiidca.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gt2sqnzzith.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2buorcwoc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gt2mghmtvon.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2fhffioqo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2tovdwgjj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2emzrumzo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gt2kwtkuhrx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2bvpfotht.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2lhejmqil.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gt2eeajneew.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gt2opndpgyl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2sxiwcpjb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gt2vvkmbqcf.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2uwtkaxiw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2lbqifqzp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2erpcmgzc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gt2wjfuohxb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gt2nyqhrwow.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2uibkevmy.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gt2izymrgfo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2oscbqnei.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gt2sohenkoy.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2lhjqwbkc.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuvenkft.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2tumpuckh.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2rpnmogro.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gt2ecxrkmbk.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrgtsdcg.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2nabxawzv.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srdhdqfe.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2cgyqpdod.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gt2pwgoedvr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gt2mfscwebb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2awuqurnx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gt2sdckdgwb.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zehmmnlf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gt2efskugxi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ndxwfkut.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2syzfvooa.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gt2cwcwqoyc.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2decbslaw.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2atwxlcyb.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2kiucuyci.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2khskyoab.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2ocakdbsn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2gdnkqldb.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2bawvjbna.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfrghtzn.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gt2kpxellpe.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2vnmckzjb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2pbodlsdg.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2rnlpsswp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywxsdltn.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2gtqqkaxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hciyihtm.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2fhyyvnet.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2zxjxgmuz.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeiwpsns.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2guacjoik.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkadjzel.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2vttcgcdq.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgzvgbbc.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2mscojbfa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2qehbmosq.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2xzdykolw.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2fhqpbebt.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gt2gwfhkffh.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlsxothy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2zgftqdyq.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2lhxxruhe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rjlhzkwl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2vqiarscz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2quklwlll.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2otlbimde.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2oubzmiko.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2xmsngfsm.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gt2rgvbyukk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygibymen.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2btryozxw.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2oplclews.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2rxdshlqz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gt2lfuqlyzw.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2uykyrqpg.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2mwkqydyu.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2zhndeaef.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gt2crbzqdvj.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2akvzbejl.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqzkqihm.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gt2rxjxaqdt.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gt2qkmkaaxq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gt2lwrgpxam.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gt2zwcangyf.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2tiyaynzv.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gt2udejbhkq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gt2vsiyfuap.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gt2qznzbnne.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gt2eomiiutr.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2prjcdezk.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2scmjwysa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gt2rdoscuok.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnbjitmn.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2astjlwvz.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2zcfuialu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2lgedrdpv.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2wlwqhutv.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2ribidpty.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2zrbgluak.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2vkmyeefy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gt2qefhsnmk.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2sdttdqku.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gt2bfjljblx.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gt2luozqguw.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gt2ecyptmsf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2jtnwttrn.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2iuknbhro.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ksnunhbr.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2teinelvg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2uszsswmm.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gt2xjbqhkjt.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gt2xzqlqcje.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gt2edwettty.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2jezwslqm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtvuljmt.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ghbgmnpx.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2drsqtbwv.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2yhrnmbev.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2xdwuqovh.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2pdzkqcqr.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2bnudmijn.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gt2shjohplj.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gt2hokejzgp.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2xblcumbo.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2gudglwcc.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2vosuoyeh.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2ddyhpjal.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gt2vclqvblc.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2prusylxt.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjckdivs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqeakbq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gt2mbrchemz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2rtclwqtq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gt2gczpribt.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gt2yjhzuclh.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abbxlyyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2xnopcbep.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gt2urgsaqpk.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2exlwsaxy.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2flqeivtc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biuwyiuy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2citbxaky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2hzpavgxb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2ddobtfte.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gt2hqvqcuiq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gt2odpmnwyb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gt2ajxnvzak.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2hsnlheyl.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2asltkoex.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gt2gbeznuhr.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gt2hfraxern.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2sbxyfjii.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oytguloz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2yibvydfx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gt2ntdkuckr.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gt2zohstvjh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2jvqgpmeo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2dkcxszpt.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2xlmsddym.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2zfvgtiib.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2jrkbhjzv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2zuvswtqo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvdpfddv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2cdaltnin.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2ybjmmnqd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gt2gekusnkw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2winncfei.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gt2korasrtf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gt2izwuedag.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2ttynohxt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gt2ncmitxdy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2pblhgjdk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2xyejdbmw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2hgrgkgct.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2xnyxgjpe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2dpgoozll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2eskcqton.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glovagpa.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2kbgurojs.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfmqjimc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofctrmrg.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2axiblozt.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2cvrgghqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2rkjqpkyv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gt2oborumtd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzudvbsl.html


<!-- 参考信息 -->