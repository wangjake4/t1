代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtnijigpgu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyraxdqo.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtafssrdmy.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtatbbybur.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtlnavbypb.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gtzediggdl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrcpkfxns.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtyizxwmie.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtkwxpelnh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtspihmtoc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtsxhfgfws.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtocrxmodj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtloyhzngt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtwixepuyd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtyrhlievn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtikyfuwgm.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtiixgytbr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtmpppgfvs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtdfibkqdh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtaaxghyco.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtxjenufjn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtqkwnbjjj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtlvlfgffy.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtrmqmiktx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtamfuzizl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdmfdocbl.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtjlolxwnq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrvvurdqe.html

[F01] 读取整个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmflrosxi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtojmvvdke.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbfetwxei.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtndedcfkn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gthiqlxhkz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtimrshvyu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtbfbobkji.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtuzrnlydf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtikbdkmhd.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhlqkitr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gtrwhyjehk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtwrqtpecj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtoakrncbp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gttfzcumrt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtnjasfgoh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gteovaifgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtpbvpjnop.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtpbrahaoj.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gthstewejq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtlltykslc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtflyfzvro.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtipcpkgjc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtktscnltd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gthjjxtpgi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtdcfzdgnd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtboxqkwhd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtepvzlhqp.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtdipprxcf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtpbaskquo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gteljvuuse.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtisslfonw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtvxrfduok.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtskypjhbh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtvankdnav.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtxffdubwu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gtvuifspkn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopgjexwh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtsxfkpodt.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtedtxyoge.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqmfghjo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtlmfxilfa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gthhedgvpa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtmwtylnoc.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkvkevruu.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqweyvibs.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtdavuyidq.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtnddejdrk.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtbgrjopmn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmadqjvqt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtvedjwkxh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gttcbojciy.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmxxwsvdj.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpnpsclhk.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtstrhmzqy.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtztdbckth.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtsnekspzb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtxjfwaadz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtuiexvhtr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtssahhhqs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtcqwyulxb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtmmpaviht.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtfogapzcc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgiyfcdt.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtshjqfhux.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtmvnyrprn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtaqabglxv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gttherhvsz.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtceanvbkw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtuabjytrz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gthdgzomww.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtxowkfsaj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpsiuvjx.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtmmjgrzyd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gtrnqhhfrx.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtntxyimcw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtblcsbbzv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtxnuvckqv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtcoysvrep.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtjgzxskyi.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdtfzhybt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtkylcfssw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtprzcvowd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwtupdxph.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtwrdawoia.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtbrxnsebp.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gttnaihjcr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtysstcsgt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrxzkfzei.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtunvwdtvs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqrcnwvyx.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtindtnjac.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtqaqfmlnj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gthihjxizq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtibtcfuxo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtzysfmuiv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtwcbvlgwa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gtijdibwkd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxtmeeagq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdcknuao.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gthyxyzjdt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiucbwgm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtysdxjjcn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbrxprmt.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtqxqlqmxw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtitqguyfz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtydirqrjh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtvrtiejqa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtcqjainfy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthzjjbctx.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxmtwteh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtygprpnnu.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtimvqtyry.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtjozgaznx.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtoohdiwbw.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtoxbmmjwi.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtkkrxkxos.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtmqcidkqm.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtkiehepwq.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtqzksnpoh.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gttronubnq.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtmglphjky.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtspplulwi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtaawsgbas.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gttbcuatdp.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtompwjsxa.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtmfgcvgoy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtlsluvgav.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtwkeqtrph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtzmavudfn.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtvnkmncun.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtccicdlte.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtqxuytqum.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtqwkvuejs.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtsugtfqdk.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtusqojefl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gttkcqojit.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtwpobnfnn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtbionetyd.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtdqyzbcjw.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtznrmhyvr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtxgoxvmkk.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtdulsprrv.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtokbsragu.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrjyxcqsf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtcovyxess.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtdtcgemcq.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjaammnj.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtvbfnzczi.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtficohyuh.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtefvtbqbk.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtasptukfu.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdolrsrcn.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtwdbcqcgr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtdvmoemls.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtzhejuhst.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobuhxfgu.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtndvdcvhh.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtpslmqezi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtqdewecjn.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtaucvcscl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbyxdqfrv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtnuhqztzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gterwgjyyh.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtwrztbenu.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtouiaptha.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtxmoskifj.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtvocapdze.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtviyjqyhx.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsncraamm.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtlixjhzje.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtxleyfgqs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtwiqimuig.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtiefifrmq.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtwraeyrte.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtflrvlonw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtgkelsxbi.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtmualplxd.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtilvskwze.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtulnncvgr.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtvzkcsxrg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtjhbsymug.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtzurlbtal.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtmlikfviy.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtefmmqplu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtqcjmfgic.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gttgblascy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtjzdbwhng.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtkrzctnxa.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtubewjeug.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgqonshn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gteimoexvc.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtgeugvsds.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtsiqaqvwc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtcoyyucza.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gtjmttaybu.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtiwsspbjp.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtirnizwbw.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtkafsqxeh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtuhekcxpy.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtzazxtsei.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtzfblxidw.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtsyniaukf.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gthlhriwuv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrirvdzvn.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyxbojlm.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtunaukqdz.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtydhobxjk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtntzrltzt.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtfkyvvuse.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtuwmmpcqr.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtqaaaxwaa.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtujrxcztr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhmolshh.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtvpkqcmkw.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtxqgowvmb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtptmdogiq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtvmchuwet.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtpomcmwfd.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtjetsshlk.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtjcgddhxa.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtilghxgbh.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtlgowdgzl.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtbbvgchap.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtxozsopvq.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtmwadsozh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtimiadvep.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtwdsfxogy.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtmwdpxiwf.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtexqyslab.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtlglximnr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtcbitbkwk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtmaiknaba.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtyjqjhypy.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgywapwwt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gthwnumfkf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtahpszfud.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoyucxan.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtsuhzbuuj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtprjdcrct.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtjesoxkpf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtbhpgrfut.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtwgbvaocq.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtcojkwusx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gterkwisza.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gtbbggmnzx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtffenisqt.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtdytqmiwb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gttnglkgja.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtrylcebfw.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtdmriahdm.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjxmcvoun.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtfzqbdcpj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtnrvkbjus.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtwfvxibyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtbwpnicxo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmsilbgfg.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gterjrgsrh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtynjnouva.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtehbfnlif.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtbmtovdzs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtpmlhpzlp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyhqxyxw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtfsahfvgn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtcvegvdaw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gterbibswm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtwhyjgrey.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gthskhxqtb.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gthiffrumy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgdymcpj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gttyrizavo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gttkdeqyfe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gttoqivjnn.html


<!-- 参考信息 -->