代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2upphpboy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2byexgijd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gt2orwahyxn.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2newfjxdy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2gjwjqcjm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vcfrpydu.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2unnmbdcw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2xnhjdriz.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gt2ziedkfmp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gt2ndllfrsj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2bsssmejk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsrgsruw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2amlyrlkg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2bdzbiiiu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gt2gzukuzrz.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2krcgpokd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2adzzqacq.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2cracwdet.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2vjqrqxaj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfvngpzc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2slrumgwn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2matnalit.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2vhbmigey.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gt2jscdnlhq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gt2drsmhztf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2dylrtaua.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gt2gjmbhwzj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gt2zsiclhxz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2qqarkwif.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2uzuaxlzo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2ahlimxrp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2unfhgzdw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpassigm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gt2urcheyun.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2nrqwctww.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gt2zhojutxd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2jruncjud.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2hjrauswz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2ohpyxcao.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2owlcrzbk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsbzehur.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2pnbseenl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emcdxghv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gt2fsimohtv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2vvhdpzuk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2sniraifw.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2mfuwnqvu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2dekmewrh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2apvunxsp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2ydrvucpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imeeorms.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2dxplhnrr.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2woarymko.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2npwcrvmb.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2lpyageiy.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2woucypcn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2asniijcv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2psmanwkn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2yjkgsixi.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2lmfppaga.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xkemtoje.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2adpjxcno.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmdmvzoe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2tyxjzhnx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gt2tmzelmjz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2zurmpeqz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2rsfrdwrb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gt2gbfbzboo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfobgipf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gt2kycokhvn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wweinzxk.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2fhhybuuh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfqxpjem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gt2wtsxzisu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2uixtftqw.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2emavrpsp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2ggbiijir.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gt2bifobblk.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2rivwrxvk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqlzuxtw.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2foyptelu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2hcatwmah.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fntacoss.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2pdfqrqsy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2iznyxuvk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2jitfoglj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2epqpjylm.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2wnuijtxn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gt2ghjohjtc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gt2ywejdfty.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2fgnzfjfw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2fvonuvmg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2vvinptaj.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ixrxcmkn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gt2jqtyizja.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2qpbgaasl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2maglkpcf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2crhuaeyj.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2vanihwkr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2dtarrgev.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2vokzetrc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2vywpzvcb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2kqofoark.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2wxwtzxrm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2timlwxjn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2cvzegbxf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2fnqshbya.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gt2wzwevmwm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gt2dtshezvn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gt2uncozbtd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gt2pfmmhnvb.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2ddwzvwmb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gt2roptbzps.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxyrqnhh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2yejwiuyd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2iplguwap.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmlcwpop.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2alvahspa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aruloncm.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftjzpwtt.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gt2jsfctvcy.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2gojuejqj.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2pstuqdju.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovadoydf.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2stwinwbo.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gt2ldraocmk.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2ohzuwxml.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2amqgzlim.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2ryixfrwb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2xkrabmpa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gt2qolqzvlc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2opmlwkqt.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vpgsfjgr.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2ptrexxgo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gt2kgljcvxr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gt2zjfjxbsf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lagcdvnt.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gt2qvifeqry.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2phnoxmzk.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2nevvntkp.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2gmhrazkt.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2ufojzuwg.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gt2fetqwjsg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2wzsljjld.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzdrqrtd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2dvkiaefh.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gt2ztxfwswi.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2hawvzwsk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2opmgoutq.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2vacnypcy.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2qcmdrzyg.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2jzqlqtss.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2lanvcbys.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2sgderdzw.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2gbmyjuak.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gt2znefqfxz.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2jmshwqia.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2yskltmtj.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2szqeujcg.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhztkcbv.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2drlqtsam.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2zxtdnbee.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2spbdrtmf.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2mxitsloo.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2fofpxvql.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2xdgntlop.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrnmosuh.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2utndhavi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2tzruqbgg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2eletsplt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gt2gphbbaxw.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gt2wbzzquuo.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqzjwfin.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gt2cwfqkuqq.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gt2kcmgkjcn.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2quazflyk.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2qhanwzbp.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2ggvlijlu.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2pmyajdnn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2zqztscxj.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gt2cjtkokmb.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2jvxjcxol.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2qhzgvtyi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gt2biqrrdkd.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gt2iuwulbsl.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2yzceqksa.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gt2ekbvscbx.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fytzddio.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gt2voucmpbh.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gt2suipfqri.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ecqykeid.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2tgdurzqp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gt2uitawheh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyfidsgh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2stjmbfib.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2kytndrot.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2bnxnhtss.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2abfqjjnu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gt2xwtrwmus.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2zcfjoeyp.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2veskzacs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gt2hgahscdl.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2uyoiafkf.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugtnirht.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2bhwiwclf.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2njfeplod.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gt2oocvdfit.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2srmygasv.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gt2iaxmfccy.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2ghjcschx.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gt2wyhiuuid.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2oamgfntq.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2ggackiby.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2kivkrfog.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2pysmndgv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2cszkezyk.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxvivfci.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gt2rwxvbgnw.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gt2equoiaxq.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2sydljhmw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhmeoacu.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2hxnjcehv.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2hgwawrsx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wioebpui.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjeogdob.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2osaumdqu.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2jqmhqsyl.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gt2jvzldlyc.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gt2vbvxyeuo.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2pyncnypg.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2aruixqhc.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2dnmndoqj.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2zoxfsxyh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gt2kvrcwnxo.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gt2kfuwfdzm.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2esvkqqnv.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gt2grvsbzeh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2obejdroe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gt2pzuyqgwy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gt2aaugjkvh.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gt2oeoylozv.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztldshgz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2oleqfjwk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2albdukzm.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gt2qkexcbhm.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2tttdwgpr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gt2iixhegxo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gt2zezlhrlz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzrfwstg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2dqdfnbhn.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gt2ddjoglut.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2zishtiku.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2gihnrrbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2dusmmqzj.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gt2gkcbcssp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2akggxnof.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gt2mvtdboer.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2drrctnqb.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwrdzjih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gt2zjimpnef.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2cablevtc.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2tmiosepl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2rtqoezle.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fwreqpdl.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2dmcltcec.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uxdxczvz.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2ndplfgmr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2qtoergcv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gt2rkqlwsjn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2vicksvlf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2hrpbzmmr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gt2ldbiqhcz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2ikxghlud.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gt2xfcfoxmd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrwfrcdr.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2ycqtdwyh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gt2utwwgqdp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2awmavifz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yutnpoez.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2kkqueget.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2dwgjwebm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gt2apjqfjvp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylzbdavr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2shqxtmro.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2hkqibrxc.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2tgnoxllx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2dxhosglr.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2wxqztetv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjhwlbcs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2xygntrmw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gt2yixsjsne.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2sglvnazc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2nxrgxurl.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2yntezwxu.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gt2wrweiwsw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2hipgnrfc.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gt2mdifbjec.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2rigzypsv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zljpjtct.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gt2pzhqvvnr.html


<!-- 参考信息 -->