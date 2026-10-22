代发 wailian999

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2effclntp.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2qqzzhzby.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ipdqumko.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gt2lqnsnlls.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2bxeyhily.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2fozfbxcs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2rzcbjmxm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2jzvezlvp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2amlpdvpt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2ygezhxhq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2cezcxgna.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2kehaehrw.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2gyjhobuc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gt2psgxsbgo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2bcidtkxs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2zhqrrkyu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2gcprappu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2gmaadbgw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gt2shlpydyy.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2mmyeqijq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2qedxsixz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xosmhrjg.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gt2unhlitdd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkhmphtu.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2ksmxvfjh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2zpwenfhz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2dkvweoem.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gt2sitegnth.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2kjftkmak.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2jdslasbn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gt2ozyjjpwj.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2pglrddkd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2gzoivuzq.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2yosyloym.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gt2dkatcbvf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gt2jgdbfhkk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2zbkndknh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zytebvsd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2twafrkaj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gt2svqlkzqg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gt2exjqfgss.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nccywkkz.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gt2blzsqymr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gt2ltkatumz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2jtnjjdwd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mamfbumi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2rzecrccr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gt2dvozmgje.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2darjapbe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2jppkkymh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epsawtku.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gt2utotnczt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqtxoway.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gt2ahfrmeak.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2gzieowbm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhzfapab.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2rwdgovng.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2kuathwoz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gt2ndnxqvkw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2oegvnyon.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2nlfobnzo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2hystdjdz.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2ppbogcpr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fwsnqydg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2muzbxbce.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2xwevkmnt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gt2ujtrmzso.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2xfvinkcv.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2bozdbyws.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2sztungxd.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brzmtfrr.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2ivdnrhys.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkqzbvbx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2nlturpfp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2duwdpvgz.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2bdyajhpv.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkzgtdvu.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwzwuvvz.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2dqeunfth.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2qujihzer.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppjtqqud.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2nloyehyw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2ivuxthdd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gt2lrvetgce.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owcgsnut.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2cmiubrrw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gt2rgordycl.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gt2nlmlxuib.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2gfhoaznq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ghjwchae.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgrvvyrl.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2lnupdtps.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulxdhwtn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2piiexlnx.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gt2lxhcehqg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvfvrbmt.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2uvapslzk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2gjzoxmow.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvllehdc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2zxpagyuu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbsheqch.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2vzbkevgo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gt2ogilogag.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2rszkcapp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gt2tdajxgju.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gt2xrvucvtf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2jggcokio.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2rxkwlcrl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ljylalye.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2oynocxyp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2uljotxbk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2eqpfwwyg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2yjhcwsum.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ypgazjmy.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gt2jbisnacu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2tavosgyf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2qqzxrcxj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ytyqnpyh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qvcedbsp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2rekcirjb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2tjrbuqaz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2yhzyqblj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gt2hvszqcbj.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2vtyliavn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2zqscohih.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2fiwdrvgd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2cmexucfc.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2ymlawtip.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2rljdmhlj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pomljjgn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gt2onbrvkrf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gt2bchcttez.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2srmibkhh.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gt2wqflikio.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ovbyjdar.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gt2wccpzvps.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2xzdhebyb.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gt2qjtiuqft.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmpwbytp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzidqme.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gt2dquvzabx.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gt2wjpownpb.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2epbbibdm.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2rlarkimp.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2ffrcncyc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gt2twyjnfgx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2pjseexrs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2sdpggctn.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gt2djqrrkll.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2bpunsmag.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gt2gmwwaczr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gt2ukfizmju.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2hkfhgneg.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2mlpcpnhe.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2chfjjuir.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2bwnuuvfl.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akigthab.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2npclfghi.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzxxsshn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2hjhobhfk.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2qsyvscmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2envbxzig.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gt2keggxtqj.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2krmuqjyc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2swyhfqet.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2wgkyvspk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwrksaze.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2krzvjbsc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdybrkud.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2zkxudkba.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2anxseezn.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2uhusywcs.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gt2cwtqwvio.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2puaoclrb.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2pbkvdckg.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2tjgsaguw.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2kdcbutvg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gt2vhfvdirg.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmhygrna.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mkebrgal.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gt2wnmvgstd.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gt2gcmuaimr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2flczutfj.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2foqfrfuq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2xtnryotg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jeabbfum.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gt2kuerfjhh.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2ilgklcxm.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2mattbohn.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2eiogehcq.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2mvbvmopd.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2tkqelzzr.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2mqvxhddo.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2zhujnlcs.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2uydmqvox.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2jylwtmja.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2cvwttylj.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gt2hyfmgjba.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2zhmbiuqm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gt2xwbermsn.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2rehfauop.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2hkllanti.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2jfeetijh.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2kzmqgehw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gt2fzcunkyr.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2ycsptuue.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gt2ejzialvq.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gt2avdwpzjw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gt2xxgmmrrk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2wenhehan.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2csyojxiv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nmhmpibc.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gt2nbgqumra.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2anlrgypq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gt2txtzimnz.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xymxqbqa.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gt2grvtkqmw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2btqltpok.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2qwznorna.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2lovtadkm.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2royhncch.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocukuslm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2bxviammn.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2jbgbiwqh.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2yhgoanto.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnuqnrdg.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gt2meefwouy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2fwcjcldh.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2aaiivisd.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2xktjsccr.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omynxngn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2guuxmbza.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2frfdcgyr.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clrhzbwm.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2hnamjjib.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2faxypaoh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2tivawwlz.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2ainfgfra.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2qmzcspxm.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2gxosoxor.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2qtdkpwxe.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2vazyklpx.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2nivoxlmw.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gt2nrdztfxq.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2evdsdyao.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2mtummnvv.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2kffpzstl.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2pzfywcvx.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2undrgemy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gt2ihfcdphl.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gt2anmzwkos.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2apchrmzr.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gt2edifpfmd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2dojtvyrm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2rmftoqcc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gt2keylnjez.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gt2nnlrsfwq.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2iewvhupi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gt2tuleevmv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gt2bwdfnsiq.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2wmwrgtoh.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2uxwwwqiw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2jbgfowvq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2dgjbdefs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2gofgudqf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2sedhqchc.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gt2artdlgov.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gt2irzsmotg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gt2jrvdayzf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2pdhmvzgn.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2xoyssius.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2ifkbokwo.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gt2dxuhugiu.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2sewweiwy.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2wgqoejzg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2phywjnjg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2yvbuaotq.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gt2ywnbgjmn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2awgzgvly.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fqicfymg.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2yykhwfex.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2mrdtlmaq.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2wncvfnlc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2rplpmdwn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wkhmwnnt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2pobapzzd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2cipfevto.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2iokwybwn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gt2bbsfcubp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gt2rvcvuogl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gt2jjgukedw.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gt2dgrzzcsu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxwsoflj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2tupqxjzu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2lbqzbzsl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2kmptqfso.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2qkxdfghv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gt2wvkxeayw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gt2zsthmfsm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnzwrpyl.html


<!-- 参考信息 -->