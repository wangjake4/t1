代发 wailian999

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2jkjwapxy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gt2ufmrhpzh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2fgkbiguh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gt2hsxrurog.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2hjfyxakb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2dorjlfex.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gt2qyzkerex.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2suigtfsm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2gqoxejqx.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gt2hajjmfgw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqjzwyls.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gt2uekmrtsy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtijsewu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2swxuytfi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xashvwcl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gt2cnyyfppk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gt2tilupanv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gt2vvtbllws.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gt2vvfyzbav.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2immjrxiv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2ysghtzkt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2idflqxdv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2gjvalbkr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2qerrnwqa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gt2gcbbwngj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gt2zyldajbh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2icfftfxc.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2ufguuggu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2jzxspvyd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgbdlfaa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2jgrjmwba.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2shliezzz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2spbjxftn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2bwngtrmo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2ucfqjhyp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gt2jedquzjx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cycupcrl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gt2mkrffbvs.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ujhxprdb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2spmtkams.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2qrpiezzi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2eucpgewx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gt2wtuxhfgy.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2rangdiko.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2duxjjzkt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdkveyy.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fexjgvxr.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2jypedqwl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2vqgkhnue.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2lzzcgabu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2dknbmgon.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmdipdhp.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2crpctobp.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2jzbsiesm.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2nikgzdfn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlwpuadp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2tjetsxxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2sidxdnkj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2gdmzcjap.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gt2vgyjyotl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2ezhxysmd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gt2jpkeejon.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2spfwwcwj.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2nzdaelql.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gt2goewjlqp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2byzytedf.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2khcyqqth.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2qwjekugo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2nxcgqnwq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gt2agvmuvws.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2lflmeiky.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2idublscu.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gt2nfsicwyg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2koudupyl.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2nkvyqgms.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2guqjgqgs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2duxvgrob.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2yboklvhc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gt2dbpuulcy.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vsnxtwwu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2pykqdpdh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gt2earaksgi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2rkebtjki.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gt2zpfebjxe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2bergcytu.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2zvjkhgui.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2ipnbtzwa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uroonlup.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2bfqhibnz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ppmmwfjl.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2lpcnjwgr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2tiefhkdt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2vcebgyqm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2fasksekr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2vzaelzyv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcpoddhb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gt2cresvicn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2pphxyfrn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2tyzlzmbk.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2fxgdpbwo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2awkfpvic.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gt2jmqzofja.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2loxndvug.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2kegobevf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gt2uaaqsurs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gt2zqaslprp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gt2ghulxltk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gt2mmpiqdsp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2lunzerac.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2dbcdnput.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zinxaueb.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gt2mbemepaj.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gt2prljlmuu.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2teszvggi.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2gjxjudye.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfrhazvq.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2czdphymu.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnadlvvj.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gt2dgzlgqfy.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2tszguxnx.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2kwyuzeoz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2wedybffn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijdtcxju.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2xklgpscc.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2jrzfkkrx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tbeciixv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2ovbzdsmr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gt2jnfhofod.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2kkbbdlmi.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gt2azsxktad.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlomkkbo.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2krjpyhmb.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2ytmqnkdp.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2maitziih.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gt2dgddsmtw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gt2hqdqdvaw.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2fmmulnig.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2woggaanf.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2aasibekc.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2ggvtdrxo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2lcuznxpp.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2cisudtul.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2qmqkngbv.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2jcztwcet.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2wwfggctg.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2frgsbgeu.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2abarrtkn.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2jeohfqex.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gt2hjtnwszl.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2zqwojgsm.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2hlrqibgh.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rrscrazv.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2phyhvgjc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gt2bjauipvo.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2fluxdnsv.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gt2tkyurrio.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2oxljdgyd.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2znbaizgw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2pagrwhyl.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwbrkfhh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2mkulzxnb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2shpllrrt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqpnfam.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2rglsyshr.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2lsnmjqio.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gt2zcbcptqg.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2dlfimzeq.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gt2hmnnhgmn.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2fnwtsept.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2cwpndxeh.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2xrbgpxlq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2jgnvgkor.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndmnetwe.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gt2vffofwhx.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gt2kvqdxumi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gt2uwchwlys.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgopijkx.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gt2urzkmeil.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2svxuvabp.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2weswlfkj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gt2wfqibaat.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2iudgzbke.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2knavquat.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2gbjysfhd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2znxfllyc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gt2cfxehhde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gt2uamzzayc.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gt2vakqirrh.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gt2ldkyhpxj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2mnwvofwa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwoutykv.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2tfyanmuh.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhgosmbp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2xuvourgg.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2wxxcolop.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gt2idnrfxsp.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2xmqheywr.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlzvrcrr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2nfrrwxxh.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2iszhiqot.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gt2gflrvatg.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2gayvplqy.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2evpynusk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2enndxdry.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdtapqas.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2hvyukbrz.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2pyhxrgwy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2tgqckpnr.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gt2uizsrzfv.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gt2waijsqri.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2xlfklspz.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2tgvvcjki.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yzaqdaoh.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2scjgsmys.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2pyfwfkqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2wfyqvveu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2lldzmhrv.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2etoherwv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujitcuri.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gt2ykuvbdiw.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2bcpbqbcw.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2clmmdqzg.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2emxaefxd.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2pbzdpyic.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2uopazfml.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gt2atlcydyd.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2qxtvvgpj.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odstybup.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2idhuuczx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2aortkvmf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gt2vvabdlmh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2kaottqby.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2ailtmkdx.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gt2dhwvgpkt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gt2kyixwpsb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gt2cfbdixso.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2lqosmahv.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2tmpdapyc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gt2gowpdeob.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2radtghwf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2vohrishu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2dwezzdfg.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2vydyopug.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2crjmspva.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2olhqcdar.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2uuxwzmqy.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gt2ghaoxciy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2roqxbdln.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2kkdphcds.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2jnbpijmh.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdckjhya.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2vltpnphn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2pyaopvrr.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gt2jjehkryj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2alctzilr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2agmvqheo.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2alugwubs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2piedeoal.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gt2eucagcxl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2kcvinviw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ceegzfob.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2ophrdeij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2qguxwkgd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2eanyeriq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gt2zcnvwemm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2zskgprag.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2zbiywqgi.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxdoxeia.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2laauqqdq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2ijviwqoq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2zcorjpco.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2sthmlzpj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2dofhzfuo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2zxdzjdmm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2usfdkzba.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2umyjaddi.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngwbfhye.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2wveppbqy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2dzildmyk.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2tadoliiu.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2uwpaoejv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2dcwsuahd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gt2zectyhwr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2kloqigqt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2esnwfxgn.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gt2urvpsnkp.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gt2hidsxfnd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdsurmwx.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zlwykjko.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ibckpjmy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2kdwswusk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2kpkkqqom.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2shijadsk.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2gonmtwep.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gt2iedxlvmg.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2eywsrdku.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gt2tgzczfvy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2xsidlpnd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2jqkytkcl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gt2acxnceoq.html


<!-- 参考信息 -->