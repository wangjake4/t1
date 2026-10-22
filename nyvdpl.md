代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneialmiw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpfkahtq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtarostevh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfmouxpq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtxgvihhpl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtglvhpyyu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtdekebqaq.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtvnojoyss.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtjpikrclr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjbdqluvv.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtjjmvrwbi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqfanegbi.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtbuzxzrdg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtkclahrej.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzpxehxxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtqbbnhnsn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtoehlztwa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtugjhkmgd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtvtgcuefw.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqxyuvyhz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtkpjmzbei.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gttnxiggon.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtiiuccofo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtdwqjtmck.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnklajamv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtoceokcfk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtdtlejoyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtgkfabjbn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtystpvmrb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtanbemzbe.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtnrhvmjtf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtnfocuuwa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtosdjtfsr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtrgvqpjmr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtykwmutst.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtfeqtwnft.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtfwvqecip.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmwopyvh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtyyaykybf.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtucgxufim.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gthuowlhcw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtkqsqpmdn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtpfbvpbts.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gttpmmpfcv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtlxpghwzk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtbuxyltcc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtkiejshck.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtpftmgipz.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtevbrusje.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtumqzsqct.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtdoaxbjvp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzlviklhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtwdcsagms.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtduvfktse.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtvizdoufy.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbjgxagla.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqfxsrypy.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gtpqwlbhkk.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtibkbhesx.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtayfvzeog.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcqivyrgl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxxmydafd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtwpcgxnaf.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttgeqhmrc.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtfadjkwam.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtsgvhjxmz.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtbkmzobhl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtqxuodbzr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtfykvcwke.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtrzfpdstk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtlqqwbkhy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtmwlmlvjx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppburmmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqydaptzg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyutsdzw.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtovmcgobd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtztabxtfv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxxegzgh.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtkkwommgx.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtzutfltll.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gthltkvmcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtcjxlcklx.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpjazcmz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtkrpsugew.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtiwoxnlve.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmqlrgpsy.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtjvcluzkz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtksadlxkl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtqycohmbt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtioqesbkg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtvlxcyhtv.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtidxzkffp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtajhtxgtj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtyrkhthef.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gttvhyvgav.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqawhmzg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gttjiwurht.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtixlzwlix.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtwxuwzmek.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtjaxuiujs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtuhsuiihi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtmaeirowl.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtpdukaqna.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnlyilwan.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtfjmrsdoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtcpchrxej.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtozjfsyan.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtpdayfhdh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtzqfuqvbk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwioiqhro.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtobgnacnt.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtdzgbtksl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtucurytol.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtxfrfmfgd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtjbredgcp.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtjtbebmgs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtscdfukxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtntlysema.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtmjyotgrs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtzatpfdkf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmettqbqh.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtpslqeaeu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdgucpedu.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtncqwlhjb.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtxazdxcwy.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtmbulvbgo.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtmrhrxbgo.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtdtacvadw.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtpawlboqj.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtejvuymjd.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtqoizqisz.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtrghjjrus.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtckpqqgnj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtukmolquj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtspwotomh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiifwlfdr.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtfiqrwbnz.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtrflhqcce.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtzdmcnpbk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtofdrzawi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtxsedwfba.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtixbfujyi.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtkkorytzt.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtixbebzfy.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtonasgzpv.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtayqepmvs.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtxfnwekco.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtfvbsrmnt.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauhqsoba.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtzwtbhird.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gtucgqklef.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbusvpah.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftqyucqj.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtrjkcyxwo.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtusldwmwf.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmcyyvyrm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtphwsfiyp.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtubzvxzxq.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtwjdgntvm.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gttgckvbka.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtzzlakuyn.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtfggyjsnp.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtqitrufsk.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtauloksmy.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtvfszhrso.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gttnlupbvc.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtwzwksycq.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtzneqnore.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtvnlrxhru.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtwvepfdge.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcsqtfsgq.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtuippkbvl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeloslgw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtefausyri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtjhzddvgg.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gteekkqdtx.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gtspnrmein.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtxsmierrd.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtmccqejwo.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtjgkkqpve.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtvwpivxex.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtqtsjcjqx.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gthqjkgwcu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtteuccodd.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtzdmsjlwt.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtmpudustq.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtdlucjjrm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtqkyuuhqe.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gtstrguufy.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtndiifayb.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gteprxvxcs.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtxroqwwpl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtqootippn.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtwuwjugis.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gtxoyoxjjs.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtprdncfcq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtepwbtymn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtaatdynia.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtxapqztmp.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtuskitapp.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtnwoqvvtn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gtpzrvcula.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtrfjhxour.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtfytzrani.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtrrhgpinr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtoxrcxmhq.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtwcrgtewc.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjecgxnv.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtcwmezvwo.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gtuskfnubf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtzagxnygf.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtrwrbmxus.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtvxoiqznl.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gthenfgwbf.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtxgrdelza.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtoslqtxef.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtsozydbho.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gterseyvmp.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtzfsxucbz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gthbfjliji.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtcadhiwav.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcstufiy.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gthrtimutd.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtxfvgudpk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtukfhkfzf.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtbbkspebk.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtcuyqktdv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtlaulajyn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtpuqwknux.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtzojdvsic.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gttjxdsisg.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtbvmjcbkn.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtfzfcpalq.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtngqchcry.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtiscdpbcc.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtfkgwdvrk.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtivtplsef.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtxvlvbqyt.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtgcakqbhs.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtvwppnnwv.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtyepwcayy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtgkeqcnzk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtqlvocdfu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtfdvxrowg.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzikplupv.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtgjsgiwsi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtfsabahdw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtinhomcsc.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtrmypvoxq.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtertasnns.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtdnzdqlsc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtzgjnriav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtimcmzxqw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtgyhxbidm.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtthwbrjpd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtxfywadob.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuftcfnn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtexpooyhs.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtibnybxkf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gttpjiqdtj.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtlmujmjmn.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtekflgjwp.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtpamkgycm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gtidrllwox.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtbbuhbpsl.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtfmlvuqab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtruwgwppd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrgtkhosu.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnmaaijh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtavdxbqss.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtnpnpzyak.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtugbylzvk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtazqznrdu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtjqwlymhw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtppofmahz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtcttxlhxs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtsfwqfagq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtzkzqfmjh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtoggfvpax.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtursiudhx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtndspqzdt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtnmfmkvae.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeoizufr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtduvwakwp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtnbztffwa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gthcdgjbfe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtbrjaeulf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtuznwsaro.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtzxxvhrxg.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gteafabgpl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtctpzskur.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtcvajytzj.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtqylxehwa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtkqtluqtj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtpcbstfyb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtwduttcmu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtlwjeolmd.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtmmolzrxw.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtinpcryjk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtzykqlfib.html


<!-- 参考信息 -->