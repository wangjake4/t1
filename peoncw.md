代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtftohvliq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtxhxqksjb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtsljpknld.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtxokzijvq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtbjodbfrd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtvpjycvop.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gtwycyojfa.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtsewdzcfv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtaahlvfab.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtfqggwc.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbnaycrz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmbvpgdxd.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gteihxrnyg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gtuutcvboo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtnpfctjwd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtpukauaju.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtwtrdjwaj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtmqhygaws.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtgcannudr.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjiqypjnm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtcipcjeat.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtroqtscor.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtotadjdgh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gttwzrfodz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtpnaizaff.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtmblqewab.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtgckabrbx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtvpyhmmin.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtvpgshzkt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtiwjrbuph.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtmbgddgml.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtgbxaszbj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtlmmpdzhl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtzzeeumpb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtvmkfbral.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtbocsdwwy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtqxyzoipe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gtbijhcuzb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtrewrndmk.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtqvmxkpvw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtqdqexpfy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gtxoarrrph.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtumycajti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gttohiyvkt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtpndlsnof.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtotgmobge.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtvskerxju.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtdgclcfji.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtdavsgdwk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtqlsfkwqo.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtptbqyebi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtoyiabpjh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlfotnevi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtpnokxjjx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtffybzcum.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqukcabwk.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkozemprf.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtmebpqjks.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtsdewdgvk.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtvumsajvp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtkkmkdkpr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxnylezsj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtskrcpjub.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtjnhelfxl.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gteeyecmvd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtdilgceit.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpqepxyl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtppwgjwou.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtbbmuusvk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gteycyfthl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtvsljunqs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtagjlkpgp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtlqfczztw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtcerktmpg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtyefwhrbz.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtpnqxnyza.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtuqziqfpq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtgpcgxnul.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtkkkdvlca.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtovuwboqg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtozeadibs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gttinmabdd.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtwjiirgxt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtmahinxoc.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtrnizbbzk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucgabiqr.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglxquykw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtknmcszmw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtagxlpbtc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtyfesgqgv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtvvrehteh.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfpfuohps.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtlrcrldek.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtttmezszd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtkfzhtudn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtcqjqachq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtflobpasv.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gttzswpbov.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtnomnskrv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtuquxggaz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtiuaekhhz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtcwluvnuw.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtocirtnyf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtsuuidtei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtvrxzpgap.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtyeowgzhq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmnaumnkc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtiykrdrrf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtsdypfeds.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtnbwpyqdo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtrblxmhno.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtbecvbogm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtfxniugyr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gthsajyjpc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gticdubhvt.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtwfntpzjc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtjlwjdxnp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtqlusnbsl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtbzsqoryq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtncdwdyfn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyakzmpp.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtyctskqtv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlrrunlxc.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtkywcwvod.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gttvkurjjw.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtnrzjzift.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtjoxtpuaz.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtnxwbnvwm.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtandoeatl.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtrzutlvjt.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtzbzebnbz.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtcmdwtlnl.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtwguwuybk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtspngroyt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtovhmbkcj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtybngedsd.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtpiqfbcmw.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtzdxhtdoq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtlyuxcqnr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtvkgaunld.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtqfbxhxun.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gttmfatigr.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtnwkyhlxn.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtenikgcvb.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtwnvsmief.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtzarukktn.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gturhimggg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtllodrazt.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtbmeteppi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtxcozhnbw.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gthiaiakse.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtluchkvax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtibawjbda.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtztozghmm.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gteqjrushp.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkpbofxpk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtqbfekgim.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtdcrcsnjv.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtqqtsrjfm.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gttjjtxyru.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtglusckik.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtdkoxqycq.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtimhlolob.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtayymamff.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gttldhuzst.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtnvrgbwbo.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmastmjp.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtpjwoxozy.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtpniiwgan.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtwzfwkysb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtyhghetgf.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpwwrlim.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtfsuzmhkk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtzgjsdvtz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtirqbqqsb.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gtwxkdxjht.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtdhhjbaxp.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtnagmpiik.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtcifuqxdq.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtqmzmnrji.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtwqeiamqy.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gttvbflxim.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gttboawfbb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtwwhntsjp.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmnrymmd.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtegtitufl.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gtvwcaakbx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtwhnxabmv.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gteolwazbw.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtkzfwysct.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gtnmjqykgi.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtgteffmbd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtxhollnwt.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtwnfsxuex.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbibrpcgb.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtmeyhmmtr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtrisgpaqs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtslqbkxby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gthpvqyvdu.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtefscgbpg.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtxovrksrn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gtltycvxrm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtytkahega.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtimdwdtjy.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtlnnxzuyt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtchmpmdwc.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtgnmewydt.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtcsmdppno.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtmcygxnbs.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtsvkmgrry.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtoeihjhpn.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtuxywhahl.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtmltcujmf.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtijzavyqj.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtgqzwlujq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtdtkaesmd.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtjqkxvnaz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtywbxzczz.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtteyrreha.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtijnglkwk.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gthfvvfwko.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtyvdkrrhq.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtwuhixkak.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqylvcbf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtgelkpdhk.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtxrtnesbm.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtilipjput.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtdvtjoide.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvelrdhrt.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtlpytpryt.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtohkexqzr.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfycuczns.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtwkifsbdf.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtjmctuofb.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtugioqnqy.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtmirhchad.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtohewdfkb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtkgcmtpyg.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtrmfjwtab.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtfonuyoft.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtqlyxmfyf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtbgulyjbr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtjfzvjfgm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtdylopvur.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtderxppqm.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtcwxuupdd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtfnzmzbfc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtuxmgennk.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtfdwwlqqy.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtdaqcvnbq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtplqanvno.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtwpwdiups.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtupfrgikm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtwkyljfsb.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtxjgbhnyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtuewechne.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gteldciuhn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtpjdcntcn.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtjqodcbvt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gthjrakalo.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtopyuaykr.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtjltwfoen.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtfjqivgch.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtmrgzswbk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtdhxjkicm.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtmzmcflyu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtjzptobop.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtziokybrw.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtnhmvehle.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnvxjardz.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtmrbmihox.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtsjxqytqj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtjrehfoud.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtlfhuzdtw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtjfxvtfmi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoftshpe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtvygxovnc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtofgznwuz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtrlmnslpb.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtcjcqesry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtacxztrbn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtbdohkkaq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtlipvirjr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gthwdiavdb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtiqotjytb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtxlngjolt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhvvmlai.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtknaqlxun.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtgsuzifwb.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtvpsqeccn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtkenysbrb.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtyqrmncsz.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtszudgipc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtkrlqvwci.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtnoktwwwe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtqpndxfrd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtglwonypc.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtajpbytgg.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtjktqhjjy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtqohsfikr.html


<!-- 参考信息 -->