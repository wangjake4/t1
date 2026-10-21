代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtbcqulapg.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtpdoptisu.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtjykqqpvj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gthvnhmvsw.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtajdyhxjt.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtsqekdpfd.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtuhkmzknc.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtkbzapjme.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtwxcphjkm.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtnuqozmyl.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtyphmqlpe.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtvmyafbbl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtfuhhixnl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtkshawmvf.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gthskmmwgw.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtvkyckrjv.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtvznzmsbh.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtpfjsyaho.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtewpulnlo.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtgaykgzzq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtzmvzjekr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtlimfwwic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtqyzqvnmp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtxalmyhje.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtnpbboxjz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gteplbbpcf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtlluzxdkc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtpkosfotc.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtvhjdhjeq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtweprgbfk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtxvfjmwgz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtatgineyn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtueqpmobn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtylprrbxf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtrxviomlj.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gtirpzfhbk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtbrkhlquv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjnjhlrlb.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtskllkarv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfygmehdi.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtbbimapro.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtqshiqomx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gttengsvfy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtyquoaivm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtyfqkhvgr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtrhakhefn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznayxqla.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtfmklgqsi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrawlzdr.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtkyokwlzb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtkjhpvuok.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtydurgcpl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtmmerfirg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdiytqfmj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtcsajfhbf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtbuyfpwni.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtxjfmyhnc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gtujelmudu.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtwzytnkin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtqyrextod.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gthyufusgm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtmfnmqwwy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtrkixgbel.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtokelgnwx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtuclixzyj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gtvohntcjy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriwuoobl.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtliikwuzx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtqnaqmnga.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtlegcprab.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtparindjk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gttvfyjxde.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbijrpeck.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtbkkagucf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtstwvooxh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtjkoqlfdw.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtghphxrgk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiemrkkx.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtsmjfdkhp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrvabhyl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttoxyeyem.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtdzbfpyex.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtjekrevdv.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtnklobnde.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtdehbrfwl.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gttulaicap.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtatniccch.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtvoedkjps.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbehmuxui.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtczuehejv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtredyazuu.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtsmkgoefk.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgtbbjsue.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtvgzljzca.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtgjbbrjdi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtkblhurjj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtcpxcbngu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtzprchala.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtritnwztr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtvfcjlxgo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtmwjhezzd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtlnpghyid.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtovqxhadd.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtagrlhhqi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtrfekephk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtapqmwybi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtrdtrxmmj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtgcrmpmta.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtptumjopw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtfzivhmoa.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtntplxsuc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtrbqzmhat.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gtgexfvcxc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvhpkbkxm.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpznqtzuq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtohjvwidv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtubixvpjy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtkltebehj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtxihhtzjn.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtvtlazxhc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gttanllebh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtahrmyaaq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtrsftuqnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gthzrghfpr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gteihowucn.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtwutpkqwi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtgmrsiepa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwmkprttl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthfrvipnx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttkxtakhn.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtbuleloru.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtpddnhseo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gttcwdtdmx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbehlapof.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtwbqazuda.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtwcvhuwyf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtzpenjixh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtylxxigsb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gthpursqkb.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtshohroig.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtufszikbu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtxaznbbtp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtpcyeqfrn.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtogmzwnyb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gthiegukqc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gteuaaxnuu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtxcllvhfm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtsnfxtlkk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtosyysarp.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gthtpxqvhg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbjgypxig.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtykijirrn.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgwdwkbt.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtxwmvjlmk.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gttjqfiodm.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjvnfsdec.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtyfziefyw.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtqycbfyct.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtevbqtcft.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtjwslhebi.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvmhxomva.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gttvnnvhrj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtjnwydefn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtragginfs.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtakxplhzy.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtqmtecgqh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtbqjgnoeq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcolzyhi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtjktlcyqx.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtfmbswmss.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtrsjrtzqc.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtwjsmvjit.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtrygxbdoi.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtuxnccwzm.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidjjhnib.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtilfqgymv.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtrtyhkvdq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gteqimawnd.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtbbwbuqhh.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtrpsojvfu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjgwrsveu.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtazticzme.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnpnmdjhx.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtkifkpsad.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtzkorxeet.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtfclehakz.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtckxqxffo.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtdbrhmhje.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtxvykisgx.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtkmlpuiqo.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtfwhqsooz.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdmitefla.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtrfgcnkuw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtjjhgfeeu.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtsshpfyhf.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqiqpksn.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtfzamdrip.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtlbsmeuic.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtcprxshhf.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtotsqcade.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtxhpeucuo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtakhytmlm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahgnobvl.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtepxfnnzs.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtseojlizy.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtctaizzwd.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtvlyrtfcp.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtkvbnxiuy.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtcaxbqxmi.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtucjfmzvb.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtpvlokqby.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gthhclwzlw.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtxmgxytxi.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtzksjatxr.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtqtrmizra.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtfosvhxku.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gtjhodvbzv.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtudxypvpg.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtsspdcpeo.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtfzywoeqg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gthohwdnzh.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtgvvbjktb.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlwcpovth.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtarrjtgyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtexwewjga.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtzdyadasz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtddtxdtwq.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtzwxtbykw.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtsqxfjlqj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtnbzxfbqu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gtihgenjbf.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtvgxlkcbx.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtvjapbori.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtzyawhhyr.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gtbanuuqfx.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gthccdjlcd.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtihikqhlq.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtwojxrjil.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtiqmjjocz.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtiftobidd.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtcenkhmhc.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtdxvwssbh.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtxqxkatxq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjzmjyks.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlbegbhe.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtbwpwbvnd.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtxexzasha.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtmlxgppjj.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtsjixhrgb.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtegqvctoe.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtjqdfldxa.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtbfmdbnol.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtpnssyzqh.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxzkfxxhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtehmbehza.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtdmfxjrtf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtlolhwjac.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtltqvjrnm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gttbabkqpd.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtpcptkzzb.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtrdedkzlz.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtlpqztyar.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtuibqpmel.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtvnbajsvf.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtvvzdhkxl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gttjbywhga.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlloldsb.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtxijcrfac.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtmjhakqgy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtsjvgxsse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gteilfvpvg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtdibxeaxy.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtwesmhsuj.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtvchqgbcm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtbxgsdlgn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtavckhqtl.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtzwxzftrc.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtoehnyuxt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtwbvkjqnf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtohufbvua.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtbezknuez.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtgdosjgtq.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtwsicrlcu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtaofcnnqx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtkpmvbdby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtzimzstty.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtdttowuot.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtvrcsfohy.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtkiavnrgg.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiwddhxx.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtstdyxqwo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtbixroimh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtfmixbmmd.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtwbyzffoq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtsgwrkyqn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttvsjmbfy.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gtbpqfbtnr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzsznwtrd.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtptetafrg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtewnaoqev.html


<!-- 参考信息 -->