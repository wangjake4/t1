代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gt2hngqwyib.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2fhyzeocz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2obxfxtsp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2nhivvduf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2zndphsky.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gt2wmnqtaed.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2iqhwdsxh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2grhetxpg.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmbyqbsj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2mfmuttxj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2nfvckpdl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2nhcditto.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2viuzzpkc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2vwiomsrx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gt2ougwmtsh.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2zdduwttm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2mndfmebd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2wlgaqduv.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gt2irxjmgtd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2buyjonak.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gt2besumehv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gt2dffthbly.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atfqsija.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylaeieub.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2evkyubui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2uryabtpm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gt2brguwcma.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2dlazdywy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2jheuddfd.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gt2cuvbycjc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gt2bpktpnsz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gt2alernhlg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2koepaofw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2zlojzepw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2ufqgnqyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gt2rhexjbwa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gt2nkvaizaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gt2qoevntcp.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gt2kctoojgh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gt2nnihxbsf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2idxxxtna.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2nhlfvvyp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2niuhfigh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfgeuzrk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gt2sgrqzqrf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gt2peboagnd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgebywhs.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2ibpjviqr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2ynsehtmc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gt2zvphlgue.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2vcvpbaoy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2yifbagco.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gt2uwxnbkqj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gt2scclfwix.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gt2rsccfgbn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gt2mkvxngap.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2kyxufmzc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gt2rjkkdygp.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2avqbwjwq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2wiehhnel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iofmrmfs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2bbetogyq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggghipfi.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2xnzclqzb.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ahjexhsj.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gt2guxkixvc.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ofozjpst.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2rscpixsl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2pfiibqpj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2plyexden.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2uxefcgvy.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltrecvwo.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zrzcsoeb.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2anmorzqv.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gt2mtqthsdw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gt2sleoffmy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gt2toypjitn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2gkbgkgxs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2wvfitayz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hoqipudi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gt2kaxzuszf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gt2qzyhsfqc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxowdvxw.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gt2entheghr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2pcttlkca.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gt2cuvwnief.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2ipmbcgjh.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2alhoogzz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gt2nfnkmbxg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gt2eofjophj.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2sczbzccj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2zuwqxmpu.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gt2vtdcnsyf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2uneuesfw.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdsbeado.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2vaomhuvj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2kbtawuye.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxuhfxli.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2jtljtbot.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2lewmjawl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2ydmgacgk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2qaplwcll.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyamchze.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2lcxftnaa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2byfslgac.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2lwhplhux.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gt2xetvnosu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2eakdpmyq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2dltbuqiv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2twdlildr.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2itwtczaa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2qkobneao.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2esfxphjq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2jdsveenz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ezktyjbd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gt2ieiejbqg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gt2krnhayin.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2pjzixzfb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gt2mjratahg.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2gdlfiszi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gt2bydozbtc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gt2mdtayqts.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2sjctrraw.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2uscyeebp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gt2uedqxelx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2alyprqga.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2qckuwqpb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2mqpaycur.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2sfrnaktg.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdelhvtb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2hwesooqt.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gt2gdqnikfp.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2myeeqzvt.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrjlkbjr.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2cilsslwk.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gt2ddoxlgki.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2ztqpalyr.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xttnjltp.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2ecpuaxgw.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxfskiow.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2obpnaexu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2jenxdhni.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xfrfyfix.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2rfglljyu.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2bdbsnvri.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2lnlcrarm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gt2vnkajlbm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gt2xniwbnnn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2gapaxhtf.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwcnhaun.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2xqbvwjyt.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2jukndsxn.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2iborftnx.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gt2hqhmzszp.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2faevndoz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gt2koeejcsb.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmirnebd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gt2xshohkym.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2fsamllxx.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2zzqmdquq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wghdbaju.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2zcysktkq.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjpmiutr.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2ztckewmd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2wlpgvsgb.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2xnctdgvg.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2wmyniazx.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2cakvxoub.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2jeyaxvit.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jbgrwatb.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ilodipgh.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2exrvflzj.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2bsrchbgi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gt2jowgeuvc.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfrtizjw.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2juyrwcck.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2hkspacyu.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2xagpvobb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnrbupfc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nsnelkpk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ypvvnklo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hijioyzr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gt2uqfoynaj.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2woerojbj.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gt2clmcvytr.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2yuzmwvpm.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2rcyxnouo.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2phjmcknp.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2vzqijzpi.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2twrhivpp.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2ezqwqfxc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gt2gychdmwy.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2zslmsxmu.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gt2lqkfbetm.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2scygqblx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2gesbbmvt.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2cqaxyovh.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2aidorqiz.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayiwaklv.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2ciiuztne.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2usninsdu.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gt2fjqvybst.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2iyixijmx.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdpozlxz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhkqwjvw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2lrvkwlvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2epkendur.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2hrbnkium.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2kbaetrkb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2feltbvwy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2rczeskup.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2sjouwagd.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2tzmskflm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2sctscuma.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2biclsbet.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gt2qtzmnshw.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2exqdgwll.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gt2yqygoyxm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2wcdnhfyd.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2kueplyoa.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gt2fqdrrlwm.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2kzugtxtu.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2tecujhpb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjjmhjnn.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2percsofu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2akmguqsj.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2tmrxxpkw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2iieruscg.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2pmcwhrvl.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gt2nxfayrba.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfiheaoq.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2zntwqkod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2opaangdw.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxvaclxy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2xvbssyer.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ltpwmcdx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2bneawirz.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2stknlbqu.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2gutqcmhv.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhhnscsn.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2jpdgzfma.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2xsevmvpb.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2pghjjaxb.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtoapzuk.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2ybtljumy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gt2kqlpejwu.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2mmkuzvjk.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gt2bvgznnif.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gt2spsudakx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2boimlpjp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gt2tpepqlrh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gt2voktzauw.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2ijfaprpb.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gt2wzyzyhtg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gt2iscmdsyb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2yftzbsdo.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gt2thuqjcrp.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gt2vkjgtxox.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gt2mobicphl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gt2veyzvmdw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2hdoaoouj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2sycpuhyq.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gt2wqbuaxvs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2qqpiufzl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2gdytlyko.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2aagawoeb.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gt2avjlxwek.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2fnxgnxca.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gt2xxjdpxrv.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2rqpfijgj.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2eqjybtwo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2pqqkmubz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2hukmisfv.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gt2rruufhil.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gt2vhxgmdqd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ibvixbce.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gt2yldmxipz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okjpuhjo.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkjtuxjl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gt2shlgymgx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gt2becnkuks.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2eebbtvin.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2lcpygxrg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2gboewqcw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gt2zgquflyl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2afyvjvpn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2awlrxxvo.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2ofxywcdl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gt2tenbbpie.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2xrsvsanw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmhxrfxj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2bvzaihgj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2ohxbptqc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gt2tjvzejfu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2mgekhdac.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxwppool.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2aogpttcj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2yuhekrub.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2glizohuj.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2necggywj.html


<!-- 参考信息 -->