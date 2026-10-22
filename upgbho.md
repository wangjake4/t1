代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtatxflvki.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtleuotrvz.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtpggbddtc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtechbexmf.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtbxtetnla.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtaunwshat.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtnappgvcn.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtwrnsunhb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gtpszytkbp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwrufpegb.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gthrowgago.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtkmackwkg.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtnlzlmevz.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtkkkmhhrz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtowvftjwu.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtrkhklkip.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtcjnhqcjk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtqunwephf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtlefkbdcn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gthuubpzjc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlldcfbs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtnkysbvbq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtufvpirmq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtjtyzdffe.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtnqxrpnaf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtpryyuneu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtcsnykvcw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxpfyyjz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtregzjkhy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtleismslj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtingzlyus.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtoxcggfbh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtkvzcubjb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtuumrxrcp.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtukheqwld.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtigcoflud.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtwyxmspzp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtwkgdbbnq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtqqkbxocc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtjmaabiyn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtupfvrxgl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtpfzvgsru.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtbjvpatsm.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtakshhymy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gthgcuvskk.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtqedmmnpr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtdzpqnrkd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gtwduptrtv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtlwsbtveg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtvkphvyxj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtpqeiijeq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtiuutpddm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtpnuoieal.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtrtbtzosn.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtpuuefhfp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtrjfxeabq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtgguojopq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtbhdmlqij.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtutptmalm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gthnfbtiev.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtulavqrpb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gtpcbrrlyi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtyidodctz.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtsggmjrwn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtyhxvghla.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gttbrgzgll.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtjvyzqswg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcujdrwcr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtbbozzzpx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gteohqpuqs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtyibwishy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtqpybyagr.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtpllbulxl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gthvofizie.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtexbsaezi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqwvvnjpk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gthcignagt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtuwiiwbzy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gtqpzomizs.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthzbyeknl.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzoauymwv.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtkbocsgvr.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtelveqohh.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtwafrybyj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfycdaze.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbbftqmsq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gthmlxheqq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthisrlkns.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtkoefegrh.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtiesubpdy.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gteaoszvpz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtuldgztzo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtrdhsosne.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtpdsumbkk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtxdgjsdrf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtzvmghbaw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtksfjoqgy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtohkmvktc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtjsrximih.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtfezwqxqn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gtvmmkszmy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gtzhamhrqr.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtcyvdvxtz.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtkbrdcgyb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtacocrhxg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtqdahrkyo.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtxlemtuel.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfaoevvb.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gthxzgtbxd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxaghwttc.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtjielshyu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtfinejiqw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtviqgrblb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthenlqvch.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtvjwdguzh.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmfbtnmuz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gtvavobtax.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtrzwylosp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtmhjmgedi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxyptqovi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtlcqhirjc.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjthjxfgv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtvodcmkij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtezihukck.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttjcpkqqn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxrcuhuqj.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtqzbraufe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gthjxljraa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtlblxkxva.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjhydtas.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtekquyqth.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtptdensks.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gthwsffgdg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtsrusmdfh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtxolfipks.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gthidkujeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtvpvfcbzc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtlyincbtj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtvavdzkxh.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtylhciirr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtceuxrcgr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtmptdwaoj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtgqbuhziv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtpvsyogmy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntvavooa.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtvhwhvyog.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgsyfptqq.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtzvxscqwi.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtoowckuja.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtezbubspr.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gthlsrueqw.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtdqwlpmgi.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjaritoec.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtdhmbdjwc.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtmpwsyufd.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihkdddce.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxxcpywsp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtblrikhuk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtvbtwxxzt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtjaygwrwr.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtdwmrhrez.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtbixlcjfv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthhudclj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtwhzzhcpj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtbipifwxy.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtipqgewjt.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtvqeebtsr.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtrdiqdteg.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtjvcsreyu.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtgsyxuekx.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtyrcsdkft.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtkilnbhgm.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtisbtmwdx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtbiltaffe.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtqatmhfsp.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtitktbkll.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtecqfecgw.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiphhevw.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfqrszomk.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtghldmtdr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtwjhpvlsz.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtjygydffq.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtsyacawdp.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtnnwggzfc.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtzjvhvfly.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtnyzxfraz.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gteempegfc.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtzakdnebw.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtkqlrzsug.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtaganbnwz.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtmxqfvelz.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtrtdyabxf.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gthrxsaial.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtotyuaetu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtgnqeoing.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtwbmxuead.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtdhmkmamc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtsggdtfqo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtnnypxtzo.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gttyrbkewy.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gtbegrfaeh.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtgpawildt.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gthkcwpuob.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtuymevnpu.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtojpahgzv.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtfedzruqo.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtcdzavvzc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gttddmwszu.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtydyqtzig.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtfdumcvfy.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gturfuwzar.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvookzlfe.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtwmwcjetu.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtlvrzkynq.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtbeuhdrew.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtabjsfmpc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtzafnefeu.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtttdhsfnd.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gtcxfnlgka.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtpstnupol.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtrulpkrus.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtnipkqlyu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtfeoopsvy.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtyduumqdo.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtydekjdet.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtlfqltmhs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtbbgazngw.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtxsvxszjy.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gthhfnzlkl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtlkcxzkqs.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtzecmwtpu.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtuzrmpnqz.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtkbcezjce.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtqvwvpwxt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilpsobnh.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtpbenfema.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtoxfkedhm.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gttzstzsru.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzhbfzki.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtilyqlljl.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtxynjbvwf.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtzdlabvgo.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtvelxengy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtbpouvmuy.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtpqhmkuau.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtuaurypts.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtfbosszhn.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtylnoyrpy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtsycjiqwi.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtefmxgbrl.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtxmwsdiyh.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtjhyikovj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gteluimgsy.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gtlorgukxl.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtypohvxid.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtstwqtltk.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gthwsinpmv.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtoewxhvlu.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtodvzndds.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtsmcbphvb.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtyzvznisd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtfwkxpvgp.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtquzrvtvv.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtkyhftpic.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtqnfczurh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtwxmemigo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtazuksztw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtqogsrqzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtgdraqkkd.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsuqctyoc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtbknnlada.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtxrhgxyka.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtmdlkjvmj.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gthtpuwhzf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtxheygrtb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtalatther.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtqbqpdnap.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtkmcnxzia.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtgagecgkd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtthbfugfk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtfronryld.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtzjxmmmoz.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtkmoifxam.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtlwjnpysn.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtehzwvzjp.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtdgdgrfmc.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtlklbucpt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtfrtwpdus.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gthbfnftjb.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gtusqlpqwg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtwkgdwjri.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuknfntoy.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtmzmhnbsv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtuldqntji.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtemsywvio.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtqryxwyqh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtqmbtadkq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtcankazcf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtulzwleam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteuzazjzp.html


<!-- 参考信息 -->