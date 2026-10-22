代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2xqvweaiv.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2oavmoggl.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2varcmnus.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gt2tdxqmazl.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qauhhfcr.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gt2mlrixyfq.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gt2wsrwakuc.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gt2akjeuarq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gt2qimpzyvj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gt2llpkfkvj.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2psojtqbl.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2sbgsivzy.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gt2hlouonhr.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gt2eurkbnlr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gt2btwwxbuo.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gt2uumfdiif.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2rolyhggn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2scflboqc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2sxuqhmgy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elopgtnx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2fkuqcnpz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gt2hrfoivhq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2ljjegrdc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2raswkgtr.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2yjvhjrdy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2wejzpaoh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bilgegyc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2luuktlli.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2iocaomiz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2oikveiiz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2ugandbeb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2mebsifvw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2gllzckun.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2dhanziiv.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gt2knbbgyqw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmvrxvyf.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2wbutlxmd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gt2byygbgig.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ivkovzvi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gt2olzjktmv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2wugejaxs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2cekchdjx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvyfflsv.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hgqdaiuw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2uexlvxbi.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gt2oeiwijsm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2ddepguya.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2obokkled.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvqcxkri.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2dtscoeoz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2ygjzsiqp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2tfphntrs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gt2nxlzefai.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2kmvlrhte.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xazkdygk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2ykzofrxw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2upfqytyz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnjnaqui.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2yxdbwtia.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2htueqhop.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2tysixexf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzhnugni.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2tttaifpx.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gt2kcvshxto.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gt2iicgyatw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2nmhbyele.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cowdzlaq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2ohblepad.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiivbtzq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2frnvoece.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gt2ujojnftc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffoenxio.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2sqenpitb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2bvqjlftm.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2sfjivncg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2dwhrqsjm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2xeurquxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzaksfzk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2faqxvoee.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2dwbklzpq.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2pgijqwys.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gt2gjroeboh.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2rzljbaob.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvrgpmnl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qgrmrvuz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xuffuxcv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2zmbqtpev.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2qlyajgrg.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ivmabojj.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dweeqvgk.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2cntabtps.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2hqnwwolf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gt2uivyqsja.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2lfqflsvk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2buzqzjye.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2eefkvpek.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2anfkejjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtzlybvk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gt2ctxgwgzp.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2sqmnqkpu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gt2rjitizdy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwnyxvfq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2oxowkbiq.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2gvpvdtmg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2qtfhqqto.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gt2jssgjxze.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gt2infidzhb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2iowukchq.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2wcpbzlpb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2sqtlwapb.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gt2qtxxrmgp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2oqjascte.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjlbthdh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2usypxpyy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gt2fjvelyys.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2qtdidyzo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2vwinrebu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2ilahigjs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2khrtglqm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2wsbpnvyi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2wubfkmjp.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fymbhqdd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2rqpdalmj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2gftysswg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2iybvtzsc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jscfkcee.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epcmvumd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ereqhpnb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyhvbtlt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2djndjtmf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lnexdcnz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2toqjgfvc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gt2nqxoiuau.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2monudyaj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gt2yuhtqztn.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gt2biyhdseg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gt2qwtbvhkv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gt2rrviplzx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gt2owuyevnk.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2zcjqythp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gt2zhknbmfw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gt2dhhmyobi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovwledot.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gt2gbxmuude.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qnxywara.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gt2zaesdftq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wcdmdvrx.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gt2blqigdlz.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gt2hfghszqu.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2cvxzmwkd.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2kizawipm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2wqracgno.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gt2lvbeuzpq.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gt2aaywbfeg.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gt2rtceqwrm.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2ulajpzmi.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2zzthpixl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgmkpzky.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2bziofmzy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2rqmiyitv.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2wxwmsgyc.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2qsjnwlly.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2jdemaszs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2iyeqyklx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yaqjnlei.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2tghccwgz.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2xlxikavt.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2pzrhkdte.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2cppdpeez.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2uyvswgwc.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcqwhhru.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gt2qfbztymk.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2gnzbbenw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2ubpvwcwe.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfbslkrh.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2llkslgbo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2akipsnzf.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ersxghrs.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mqurdqnx.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2zdwrmhiv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2shihqjrp.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2voemjjzu.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2nlczvaau.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2jexynxph.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2cpiohdjr.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2rshcffkq.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2zoicmenn.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2xnxvytnl.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2kygyudad.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2nnmzntzb.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fptsakeb.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gt2zshovqbk.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2bzxofdtn.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2miiudsmt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2cxyeubdp.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhhohfgv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2caoorokx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2fsoxbjan.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gt2jugbklvp.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gt2tksbivas.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gt2wejqpskg.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpxvqskv.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gt2sbyhzcrj.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2vehsuoca.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2bwblngot.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2fgtchist.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2dutjeewa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gt2fkdgfufw.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2xyaqcjux.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gt2fzcnmxsx.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gt2gnpyowwr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gt2cgcubnzk.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dchsdcfv.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2tukmbyft.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2bspjiflf.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qzavthab.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gt2fqojplsx.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gt2gbpbydxm.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2lkzzhkva.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gt2glyqovqv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gt2spmemxhe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiffhewr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2wsbkncfw.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gt2somczvni.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2qdvjgmms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2wljociro.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fniyeuau.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2lgxmahme.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssmcxwco.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gt2nqozoxhw.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2ckbrxxzf.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2galfysfz.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2zcqgefuq.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2stepfdhn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bibnjxpw.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2eyofvzmy.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2emxdefla.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2kyeweunc.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2ajsrbgrc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2gbpusggr.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ervrnutj.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jgecnrfw.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evgmvcqx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2udfvaclo.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2bcrzlohg.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gt2vpdcwkhy.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2mfqrckyh.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2neqghuvz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2skhkagbl.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2xverjmom.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2demuilxu.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2budabbbf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2adjdhnks.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2uefdjcym.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2phnqegvx.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gt2wexgztst.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gt2xkllkvlr.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2txyiafny.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2bpvjcrat.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozmutinh.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2bagyvdui.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gt2lecgjeyz.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxdkjepx.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2yddsjmmz.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezkbagzy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2ipldbcfu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gt2iqvjrwrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2rgvpvzjl.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2ebpuavvk.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbsmhsqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjtqjuwq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2adznewga.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gt2grrfnezf.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2bobinpuc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2atmsfxmp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utwlmmhp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gt2qpucdguj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2lixqsuoo.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2bpjcfcrs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2unzzfpxj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gt2qoynylgi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2pivetycy.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2lfjgsibr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2lzeaaijz.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2yjnsecfk.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2egbzedcl.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ayzzgrym.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gt2wmzzckbj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gt2vlakkzun.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gt2whazyvzk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2hmxvkchp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xhbkrjwt.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2amglqtds.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2pxvdopbt.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gt2vzwncdwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2oyftsuoq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkdabjyf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2klwiqzyl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2mbqhapqg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2vhgitlaz.html


<!-- 参考信息 -->