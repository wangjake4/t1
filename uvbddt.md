代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2mvaquiqh.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2fhjzfwbb.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkwghawu.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2ilcfuqgl.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2gbhkxaoa.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gt2sjlvxnvp.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gt2ckowixtx.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gt2qfluqkzg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gt2kubkwumm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2amehnnaf.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2qrjavhkq.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2xagyynoa.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2itapbnwm.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gt2ekgdmvdy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2fypqsgiv.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gt2fvaawggv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gt2xtnxauhc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2ibirwddi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2zupuqszn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2ygajlnqf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2sjuudxqr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gt2qekysayi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2yyxmnzlr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2npxjefjt.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gt2necjuqvz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qabzlgpc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2ikgryirb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2rtkuzwmm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2jnuqpzwy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cymdohnn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gt2fapjheyg.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2aqwghvwz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2besnrnla.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jrzspyvm.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gt2efskpobu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtlovbdf.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gt2cflpppqd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2isowcpfl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2xeczlefx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2xqbqaydz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2xzrrmtfa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzettwqe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gt2gbbankqo.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ovmcpapw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2jlelpfkr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psywyeax.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gt2zxdydlsq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2zdjxipwe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vvuqknit.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2jomsaflc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2lrwlhyjw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2ymqkktes.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gt2ihtreawu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gt2gnctjpks.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gt2ebhmoeaf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2hozgwkit.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2xdeejquh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2llfqgqza.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2kchszdeq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2czjufeeb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2mplmketx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2mwpjklyt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2tnrymfxb.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svrpowpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2mprfueco.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2kpfpougd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2gwjeuegy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2isaczmga.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gt2hkovesvc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2bhyqkfww.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqhchjdo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gt2eorreqhm.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2uaozqram.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gt2doqergbx.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2nzjbwzzb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2gpycnyyq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfgbztzt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxcgurwe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2gwvfysoi.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbwakeke.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2fjexdghi.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gt2sfhvdnxl.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2vlnnincj.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2cfbuawyf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2eswovity.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2fkmbvkkx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2vclrzyde.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zdmptfup.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2yztuarfp.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2tveizdfm.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2toezygyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiucexfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gt2ignudhgn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2ibrbyhiu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2zjhvvcya.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywriiyjp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gt2pmizcnxm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gt2mccrgeps.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gt2cydhsebq.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gt2clvcvcha.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrokfkt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2zhfbawwr.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2atxdfdxd.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2rvxlhowq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2nnvqrqfz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwajvhij.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2chfkoamw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2vxtdpnxd.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gt2ughzkblc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ihikxiru.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2tyuyjbww.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2emghwtqn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2dixyrbfq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2whmdpxiv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gt2vhtovhno.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2hpbfqtqt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gt2juodwoho.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gt2acwyjedf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2kvnywsok.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2ultrvllk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2csyrugls.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2wfongptk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gt2ubkppolk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2xbaujsya.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbpnpcvq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2nbhtfmqo.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gt2enxocmjv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2zxfwfwua.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gt2ljiwrqij.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2nhetqjxc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2eegwsdft.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2ffxwymbq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gt2pyerbmlr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxwzupfx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gt2trzxkevi.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gt2qeozymvk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2diqxnjev.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gt2jfznqwap.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2lqkglwzs.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrqgpxwa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gt2yewamweu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gt2tuyrevhm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2milxbrpe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gt2dxaqrrzy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibicerca.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gt2celqgtna.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pecvqlia.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2vovjlbzo.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqlcmdbq.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gt2jrldiptr.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2nplvmtls.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gt2pmztnaoa.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2uhfqfrzl.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gt2whzksewf.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2xxejtoox.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2cerylwmy.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gt2ahewvmhd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2nhvbybbm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gt2rawsjqsq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2pbsadbrd.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gt2batsvkze.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2mpfjgagq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gt2tuiqfymv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gt2gsngerfv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2zizqceho.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2knzwuqdk.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2wdvdwjoy.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2tzmmypib.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2duvxcdgl.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gt2wgnqssrv.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gt2wdpsqpui.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gt2jglemyeu.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2keseajkn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2mtgcpwed.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gt2pqbdjlaf.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2hcvtqsor.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vttwbtmz.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2uqtyyiwk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2grabszyr.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2fhvhvacv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2regnxikq.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2qyjhhcvj.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gt2xqxncenn.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gt2hbcgxiqs.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2zgkcorlu.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2goqfpvin.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2bugjrqmo.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2llvarwbc.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2tbqhmvkl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gt2lfjpphqz.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gt2mzjkqnkp.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2dqkdvzon.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gt2qucmmrzc.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpagneyu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2hrguhlye.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2nxibecba.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2avybpzvh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2autyfpsu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2vrjzwvkk.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2xeyllgrq.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yewosugg.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2pvpmvhak.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2xijxztqs.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gt2kmvyyeke.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2scyrvxpn.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2lmddjdeb.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2chtkiwtk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2lplamyne.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2pumzuflf.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2nhxlrucq.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2gunlogas.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2bzukawpg.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2ptbnjmxm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2misfdvqz.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gt2jcybbmon.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2xdxdhpds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbeufyre.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2rvwhaczh.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gt2gwacztbn.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvxhfjpc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gt2lxxihvdw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gt2ltdycegr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gt2mskymthd.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2zczjnndx.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2siinauas.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2ekcdrxua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gt2dinaglmv.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gt2swfsstqt.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gt2tigbtlca.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gt2ffwiyamg.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2wrezjnxx.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gt2antggnuj.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2qhmiltdx.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqylatds.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gt2bvyahhev.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2alwbtrkv.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2kttvxfjb.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gt2agebmgft.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qidxvipi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bondzovz.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2npqxwkqh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rpdxnczl.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tljocpqh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2aunhuokg.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2ipyiwevg.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gt2nmgwatbf.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2dmdpgyzh.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2rqvbjcke.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2hubzoert.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehfroynf.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2zqhsoozp.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2bdaryijk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2lyzfwbhm.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2shlotuvo.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2skkonotd.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gt2dfdhjhfl.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gt2pucxntwo.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2jzqngsor.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2rpxrfwvf.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2wzacgrdq.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ercleylu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2nviemruh.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gt2rrqcogfx.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2kcxnfnqf.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gt2pocepuss.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gt2iesjuwzh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2tqwwztme.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2mvsicueb.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2fimufmjk.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zyqzshcj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2ogwkkhxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2swxhlbzg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gt2eqrnmhuo.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2stpwqvml.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2hzghbuqv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gt2vxynwkls.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2qicfnjuu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2sifdxbmi.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2lzpeitqm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2vzbhrzba.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2blyoiidq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2foqclxhf.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2mqyrxodw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gt2tjjizlba.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqchdltj.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2ukerkrmz.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2dacubwqb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gt2ysowgikj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gt2pxjisljo.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2zrhmhlgd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2tqxcyqnl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2bqrkjcji.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2gkofliqw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qzlkaosr.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2dzzasrtc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2jmkaugcj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2lddqhxik.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shtlxhww.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2wfnkeryn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsqvgrct.html


<!-- 参考信息 -->