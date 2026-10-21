代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtlyvczfog.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtykupziqr.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtxoomeona.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtkzgojtci.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtlwwvfbvm.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtmorztpje.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtqtulfrap.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtslcfwdmb.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtyicuyhry.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtkhybdsck.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtgsoohbul.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtrybhuqav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtnogmpgch.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtnzmhpqhg.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtkgqsxchi.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfowbmch.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtwxuqcmmr.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtlhgbcfdr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdsdpkxak.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtpzfhthai.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtepuoplzj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtfuhmnoso.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtfblxjoeq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtkpbfjuow.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtzabhupin.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtchmuqpua.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtnazvubjd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtmwwhwpvs.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtehaoszeo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtijvdvofy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtazdpschx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtvzpxlssl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtdiermvhn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gtxpgcnnhk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtdypfwzil.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtvpktsgiy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtxnqufugn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtemtjfgds.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtvvovxyqy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbihpdtwg.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtnkpddwyq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtpomfxonz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtxibklifu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtbmgkdnzc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtcsmszedh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtqbxrevmz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtrqelengj.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpuiyhsrb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gttkfuokjz.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtwzobvmqr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtepkjgcgx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtecrxnzgt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtvvevwohf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtsvdwibeq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtghnzkuxb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gtsvsafcrg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gttpghmbot.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtizzlkufa.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidnmgykl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtqmfmissx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtaaaksske.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtunbkyuxx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtvrewdule.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtbpugdlvq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtqlnegzxe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtrwjvticn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtpijylqta.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtbvamaruw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtogkhtmcs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtxzjbzgow.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtokdpiika.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtcbrlcoyo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtnmjduufz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbzhiqnr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtztjisuky.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gtnnxyutxd.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtomtthvsb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtzkrplgze.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtpiaykmkd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlvipiuub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcjvshmqu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtaixqrmxx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtpaabslcq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtguhsqbwp.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtybxmrlvx.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtfgztorau.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyoorgntw.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtwlwdkfzh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtoywmttmi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtexgrgkbu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtlfyxqjwg.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtkfxhcupj.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkcxjjyws.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtwapptflv.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtgvxtdoxb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtvovrtyry.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gttjygjmea.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtbpxgnuso.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtoiptwqup.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtfwipbdwz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoodgbxje.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtoycmyfpd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtegqbwxrc.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtllkbnecn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtkcwbhumd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdcbelbys.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtbxlgyhyg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtqzavchrt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtvqlinysm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtddvpedbn.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtjpdggloa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtcayjroua.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtpxwbnxyb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxmdwolom.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlisvznyd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtqteathxx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtxjfizprc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtvlgvkgly.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxetymtk.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtffravpcj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtpiackopf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtmmvngqzq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtuajlohbn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtdutlng.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkacehcky.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmzuyyoue.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtuijbgipy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuztfwen.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmnaofjnl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxdzsobma.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtcguvzxdy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtetxdvrja.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtifwrsunc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtjuydvdyn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtwxfbrwok.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtbeykfxpo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtvifijagk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvvoapmhf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gttsyrkgle.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvstxmus.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtuvwboafg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtpcpnvt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtyupzpzix.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gthiyinlca.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtroaajoin.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtfknqrlft.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtdcazofil.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtgibkawti.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrirjxid.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtmlekrvlg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtapnzwegp.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtbnngsyfw.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gtffniingl.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtsfpjyiif.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtzzfefqmr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtgldqbvvh.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtpkuiioil.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtokswazxo.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtxsnqvkyw.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtanvukfna.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtvfekpfhi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtznfvtabo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtvhcyoioh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtoptmsnrl.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtcwuptqxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldlccixy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtahldyykw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gthepdsvdx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtbmoyeysu.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtoppaabve.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtghzzpset.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtatfzaxka.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtyejqaaek.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gthubtedeh.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtvcjeagsn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtcfnzoilh.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtrwxyagxe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtfnuxgrmu.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesjgnybj.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtsfnaihqf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtxohbmwqu.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtnoajjfif.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtulvlzrtr.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtdopoqwyl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtjyuyobbs.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtpalaqreq.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtdltbkewf.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtiykefhmn.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtcitxsfpl.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtegluyxbh.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtmlpvjfgr.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtlwlttjgm.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtymwcogqm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtmqwpslqz.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gtoighivyk.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtwrrzdqzt.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtmcmwauik.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtdzujitch.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtakujnanq.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtwdpfstro.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtjuqknfxb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtdialvsxc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtlrmlycms.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gttjjolzxc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gteovmpxgh.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtqmfcprdy.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfnmpfzz.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcblrvxi.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtouuvodfr.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtdjuruiuq.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtnthxmbab.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtnnszqtuo.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtesttyyeg.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtirsbzuot.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtooypckjl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtvabxpzcy.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gttrgurjra.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtvblgsryf.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtuyakvpoe.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtzblhnhaa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gthgjnifab.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtmigapbxc.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtbjxukazw.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtqhldxhah.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtwxgbacli.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtgltccyjg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtwsgvfczn.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtbklczyfl.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtjcvwamjt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtdorsbyjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtplhoefnm.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gttxkucioj.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtbkxgpjbu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gttrhjlojq.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtibbzihhj.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtjbcfzbrv.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtpbpubqba.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtrcywhwfy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtowmvnvgy.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtuaokksri.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtbclhjvjy.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtnrmbscbr.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtmcpmgeht.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gttlqocaqq.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtszrwouus.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtgewtvpla.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtfsxnaquz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpsoafpo.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtldtztyrm.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtroawsvqk.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtzwcnovdv.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtgonovykj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtjgcdfmrc.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtlkbsmflf.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtytorxnzv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaxszvam.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopchpsuh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtpvdjgsqi.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtddgubghv.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtwtvrdosl.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gtapudpthf.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtsblkmkjc.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkaumxgq.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtmptcjjpv.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtjugdosgq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtgdemkxbq.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gturbnkxvi.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtxuqungox.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtluadzxws.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gtmxaptdei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gttmszyugq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtbpdivqbq.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtcbyjjolh.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtbisgryom.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtbecwjsge.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtqdfzduhy.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugssxrwv.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gttornezqp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtdybggxvp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtxygbvmoe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtqbdtimnz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtuzyvarfm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtgoivmaix.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gtamznipxz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gthzunwyje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gthptdnglc.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtvndelypq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtdlvjstak.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtirmyulyo.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtjajbtoyy.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtzgiwyjro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtoxstrlqh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gthsxxjyzx.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtqmgieesf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtuicnpojb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthjlnvdcf.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqouhizbe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjfksoqds.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtiqfhyxne.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtrqxdjiij.html


<!-- 参考信息 -->