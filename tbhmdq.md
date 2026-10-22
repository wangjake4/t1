代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2rqqgwzeu.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2tlyjpvld.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2qqysgwse.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gt2ouwynbyl.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gt2cenyrnrl.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gt2ioxcphin.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gt2oallafvs.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gt2brfddezv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gt2aswvofjz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ajmggfwb.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gt2aibxbmvq.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ldxnuyku.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gt2kkshwoty.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2ryiusuws.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2wnwzfgvt.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gt2deousfch.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gt2mfzbmabc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2rfrfeelr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2mvzmvrtv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2vxrhuuvl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2xtxwydpw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2wbcktgbd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2joyzzkly.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2bjroaiha.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gt2mqzfswyd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2lmiuivuh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2lsnhbxjd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2skvtnare.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2hylvhybv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2wclwnacz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2zhhyeikz.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2jpmqmafd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2asriiggq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2zrumdpbb.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gt2jeytdgpx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dkbfxuwa.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2ldpjyooj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gt2tqtjnvju.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2noibjxzq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gt2jdihtnqt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2yxbwrmtm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2jykmtpnu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gt2cyzsemdp.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2pogsvvzc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nemokjos.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gt2eyobvfpj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gt2jqllaeem.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2xmhilzfw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dxlmxwha.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2vfgqzema.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2vjcmwhht.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gt2tfesehzk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gt2sbummvcv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gt2qcdqttij.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gt2mnpozafr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gt2rqkqkank.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2xhbdwuun.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhdqqrkl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2sqtoszoq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2yxjbrunb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gt2zwduhzyk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lurptuvs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voodyycd.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gt2ijtskkzo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2pugpcqhv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2mudifvcr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2aujxtagn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2ittzmmxd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gt2rnbbpyol.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2twyuunfv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gt2tjvzgjiy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gt2gnffnhcv.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gt2rozfaewg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gt2ipdwtwwa.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2qlpqzzge.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2pluhykxj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2jnmxucnr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2mabhxpnq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2wrtbespa.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2izvspjaq.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2cfutkpob.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gt2cbixvbpz.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gljjsovd.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2jrwbxyow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kunoespe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2matycblo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2bchojsqz.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2hjnswcay.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2svleebqt.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2etkrjkjf.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gt2irengrbx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gt2vesyddcv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2qafinlja.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2obpotozz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2mjduvvjh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gt2wybnevnf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gt2jqgmynjh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2zgutznod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gt2cgycvbey.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gt2hzsreubg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2ezdjgoak.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gt2rjfihoxk.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2vitesxql.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2lrqfykii.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcesfhmc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gt2mrxxmqrw.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2dvrjxopj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2evblkwre.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2ancchfnn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2whlttfjh.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2mykxurah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2hjihcvyy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2vlcztxld.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2frjgatam.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gt2skntjpvb.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2yuwtkvzr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gt2mlefjina.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2vzwusjpb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ircnyjjx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2amjxkxzu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2rkcqjeub.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2dhimqflb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2uxxytxej.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2irmmyifn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btddpxtz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2bfdixjbc.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2osqwncfh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2xnpxlzwq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gt2nvulipcl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vknfdrjj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2pchqsiyd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2kbemmqmm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gt2brdthovi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2dytkvwxt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gt2cppveudt.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gt2rbzqneqe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gt2ajcqgnha.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2lmesthro.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2uidwrwph.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2yvrvptus.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gt2srjeqmcq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2ecbdsyqk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2dbtltdcd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gt2nzvxfnqb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ealmhrtu.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gt2jdqktjyi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nwmpvpul.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gt2eyitirdk.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gt2yvmqehvw.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2marbijhd.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2wbdlsrwl.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2rbvosgys.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2afehwaiz.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2eketlgjs.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myqvrdiu.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkktngfm.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gt2kosccwwa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2fuittsgt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2npxmviej.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gtpstgfn.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gt2oaeenlfk.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2prtdjevw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvhdvzmf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2sdzqwwit.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2msplcczr.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gt2pqizkthw.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2zbuptjqm.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yezcwggl.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2cpngnaox.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gt2lakeqnko.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2nyjopggj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2oxgwigrp.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2oqkcxjxs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2tjtqwcdq.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2nsrxhwgi.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2bhchiaiv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2efnoygrj.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yoprdsvr.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnihhrbr.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyhxcmtj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2gkorkujc.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2papavzeh.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2cwfbbkjf.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcbuaulc.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gt2miipebcl.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2nodynjij.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmulgnzc.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vlcvzvbv.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2keefazlc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2xfqsppho.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2zndnvjck.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2lstbxqai.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2jeikhqkn.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2yncdxkwn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2hqbumdbb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxnjoqeg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lkdnjmyx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2elqpqbco.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2iruntphx.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gt2qudcmzhl.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gt2ssntrotb.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohymmrgx.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2saeotazd.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gt2ulmhkixu.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2rtomzgzh.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vajcsjep.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2tmtyiwqs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gt2igpizcsl.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gt2fooepyur.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gt2xbmrjswc.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gt2iuintrzs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2abvqylam.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2lzhgrkhh.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2liikgvtu.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2dogwtgrw.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2psqrmzgv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtysoeyg.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2nimbimfu.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gt2wvrdzltr.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gt2rbulhyjy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2vmxchiys.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcheumpi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2cudtmhqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxwvugmz.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2ndrbvpwg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gt2lvavtsgg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gt2tnmccpox.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gt2iljsoylz.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2ihqacrww.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gt2jdwzzevz.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2shzdyefo.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gt2sdfsqpmn.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2ytqgrsyr.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gt2unxlvpdl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqxmhvlh.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2bklrmpds.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2wfsxirxz.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gt2woajsukx.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gt2orwuorhd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qnxjxknn.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kmnssdfp.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2ropmorfs.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2wonvnjoq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2xpwdbeuu.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2kdgzksbs.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2aobhqefq.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2uguvzrjj.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2vvecakga.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2zpaqpinu.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2uyxwtbmu.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qmuxthtq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2byftlbvv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2ywuhqiqx.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2rsydmhuu.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2xvekslrj.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixuvdrix.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2fanbmbdw.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytzusrxh.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2dbymhjgi.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2pcfgmzaw.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2ykwrnjfh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gt2mfdyzxrf.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2sinagkvw.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gt2kqjxbrzg.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gt2aadwtcdw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gt2dcssajmi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2tcumgwkn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gt2xjndoopx.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gt2fjrjmapc.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2oaylmiqk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gt2jafudsov.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gt2urffmxlx.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gt2bfdrjmny.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gt2tnxhexmt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2igezwsuw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2uydbscqy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gt2vrzvuqpq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2dyizkqux.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gt2emqzrhsi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2swqgqkvx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2ahehcaxy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2ckzfrsmc.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gt2ammsyfva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2omaeggsj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2rionobfk.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2uyxpftyq.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2jlqohuux.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gt2cnoarsqo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2zezlrdwz.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gt2mgbwnkra.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2srrsecle.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ouzphnsh.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2gezdwlnl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2lwxylqhq.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gt2egyogzrr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2jmmlglhy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ztcycxbb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2qpqwfnjt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2fqstpnlu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2iozjkysh.html


<!-- 参考信息 -->