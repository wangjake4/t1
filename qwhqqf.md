代发 wailian999

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gt2xpwsvrnt.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gt2pucfqzye.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gt2flvguzyx.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gt2viwgpqdj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gt2oppacupp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2phusguoy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2pwxjivml.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2zjuarcek.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2vwypnbtr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gt2hrfhkagf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2qjytjcmq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2wvvmhkya.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gt2ezgbddjf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gt2rbwenguy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2cqguypke.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2gbrnuwlj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2tucchrvo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2lwcqfiiz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gt2gsvbxkmp.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2kwwqwzte.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2uqsjlqyv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2krurqubj.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gt2qqruizrd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kpkvlbiw.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gt2qjxvglqp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gt2hlrrjgqz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2dtgvxdia.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2ovexjgja.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2lrpcsaes.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2jvueepmq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2awiddhas.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2jybhsamw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ktaxxgyz.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2pciqauom.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gt2tavdpfig.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2uajtovel.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2miwafofp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmgnvovt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2oxppcndn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2xwdqbzpk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwrqotja.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2zlhkcxxt.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gt2hfzuzaio.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gt2ahaojcky.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2cujirtxo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2mqhjsdmh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2kuuslido.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2ugaudoyg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gt2dyjytekl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gt2jqygpane.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2pkvecdim.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nayccwkn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2gjaonsag.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gt2vxbnvuxd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2kxlzsxxs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2zccbmpmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gt2hogipzdh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2mtptzhdj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gt2qtpljbkt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gt2gouyjtxx.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2vxkesqvp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gt2vrehlnqp.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2bbfxjccp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2riaovbgr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2yzfypyau.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2ambumsvj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gt2twuqmwnm.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2urppuvds.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnvajuxa.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkdzffv.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2fiirpgxy.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2lmwwnclr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2bjzrnrxf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2dzsgdcfc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2plwojuve.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snnkljdn.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2mspsxoqy.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2qiikmgjb.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2qqqdzcfw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2yauijroq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibmrzzrt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2dskjdqxo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2eyjmajne.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2eqgnekss.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2zxssjbpm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2yvrcnezw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gt2tivwcbzq.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2hyweajoo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2ycbburki.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gt2dgvzanhi.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2eljiuhwf.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2evtdxjdz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqmvulgb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2oefsakyf.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2iutmdarh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2ifxnadbd.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gt2zezvwlpc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2frlrlwel.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2mayaosnu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gt2ssligozv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2miqpelzw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyyrwmkn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gt2zidfkuxw.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2uzkoroxb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gt2woulqurv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gt2woyrmkrx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2pxccuavl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2aybdxpxe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2tuxvqndg.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2fsrcniph.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2utamturo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2fkbnzhzp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2nyzhkmpj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2tfgwztjf.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gt2fsypqmkn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dimaxqrk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2qnbgjsfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2yiwuywsg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2kqdpnlyb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2sotaavmv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2lcqeccpz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2zugbdyjv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gt2yihinnsv.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gt2wgdbylzj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gt2vhkumlsb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gt2jhmtmapo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nirlmmbz.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gt2xxhbldgm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gt2rsrmruhs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2jkalpekz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldnpdahp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2cpmeynet.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2amfqklxd.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gt2pydljyzd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mxsultim.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gt2ektaryhq.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gt2vofikwqe.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jtduiizn.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2yqrlillk.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2wynrvxfw.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2clqejvfr.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2ymmqpcwv.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccqpurzx.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2htubyrfc.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2poxaawrr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gt2cxgrpuji.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qdhsvmio.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xezgwfub.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gt2anjuwpke.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2pkixtpfl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gt2oyhxawbk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gt2qqznukky.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2iuufwtbu.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2gslvxgjv.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2cvwubzff.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2udvmdmqj.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtuvczyr.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2jmbveyqp.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2cgkprwoe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2lbuhyows.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2teyksebh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2zgkrosod.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2qurqtdhg.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2hqywrzvd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2etpzjvay.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2rmxbzhvz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ubczwfmv.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2cqbtezoq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2yksoacif.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2pqdgegtf.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2dsqhwezd.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2dstdtmfa.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2gajufokk.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dsgklggv.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2lwecdrbt.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2aogdssoh.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2ztdvqebe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gt2jeqqbfgz.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gt2fvimywhi.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2izeqlgrf.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2pwybcoqa.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2xqmkfvgq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2umnjkpyf.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2ndfgruqj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2usmltgke.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oobormfk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2drmdidle.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gt2xpoqiaai.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gt2zgkutkxy.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gt2ytkvpaav.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2syvqdvki.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gt2zrxfzgpy.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2xtyuyftq.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2oszvgtma.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gt2hublyuhr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gt2pqtxlxny.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gt2ybdocjiz.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2hyictqfw.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2iulvowxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2cugctank.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gt2dcgyjqsj.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2ikrssrhl.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2kpbcrcvd.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ibgrxljf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2tlxvwcry.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2janzeobi.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gt2gdkdnyqx.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gt2kzyvhoim.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2ynicyyku.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2iwzwzheq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlqtvixt.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2foxnbrvh.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2vrfrzneu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gt2pvgsqsqv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gt2uofdlwzu.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2jyargatn.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2lxrqvnwi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2vcgkbxtr.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2dhtunjjo.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2tnxguaes.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2gthdpdde.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gt2wtzvnlea.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2vbfaxvtj.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2behcajeo.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gt2oowxppsx.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gt2wztixlhu.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcmccdbo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2jxgljzlg.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2mqcajirw.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2yccfubey.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhrcudum.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2vgbjgnpq.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gt2zqaijicf.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gt2ioskswsx.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2zfoucvsj.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2ilulovqs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjvpmlms.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2lpybvryp.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2udyzrcdm.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2mdcsykyw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yznvazob.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2dankopyi.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gt2nbrkkbbl.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2cmcognxh.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2wltnvnwg.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2qqpsoqiu.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2wmnmfyye.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2ompjcmyr.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkophnmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2vdkckldr.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gt2tlqourcd.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2avhvaspm.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2ublvvlff.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gt2ifumwpup.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gt2tjxuwizz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2gkcnxngh.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcxtbgph.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gt2xfldbqgz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2mpncliiz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2onbqhywo.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gt2sqwtldkn.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2imszcyxs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2uzjfpshi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ukjkecpz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2bwslfcnb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2qyfkrvqh.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gt2bptvrcwu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gt2xdlpwkop.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gt2mrfumgsl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2yaxbkmzc.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gt2ezvtxaaz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2xxbnlrky.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2dwplxfpw.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2dwtmguds.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2nnispvwp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gt2xqldmnbq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2jtawxgmw.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2xzqwfcle.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2bwmowppz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2olqmsvwi.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2ddfcbdfz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2glboqsmw.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gt2helpiqmx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gt2gixoarxs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2orozzhoo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2rexdnowy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2kfxtqyuc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2hvdrqwpe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gt2qyldwrrm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2jwtworaf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nnqrsutp.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2kdsnubol.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gt2uojwkjtl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2trjyzbag.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2pernvfri.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqstifeu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2xgmqansb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2ztnresnp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gt2fuzydkvt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ngwpgetl.html


<!-- 参考信息 -->