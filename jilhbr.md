代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjlwxmyv.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gt2umsjnygp.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gt2ufctasgl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2oymiebqc.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gt2ihocqwde.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2eattmtkb.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2mavlzftj.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gt2cfcilcpf.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gt2hrpvbjom.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qawfzasc.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gt2iosocuuy.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gt2yzebpztj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxgqfghg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gt2uhztrvvm.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gt2nbdbnsgt.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2xunsvyoo.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gt2weidwlry.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2roilrlax.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gt2jjenwjfv.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gt2unndkpde.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkanbzsb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lexhurbh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2oqhlpsoy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2izytutzr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2zhqjwosk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gt2lsalxjql.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2bwnmvceo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2vzsyrsee.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2toqovtxa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qdnahgzt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbkmxllm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2ftnpqagu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2cplseikk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2hrdcdqpe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gt2dgkbtdxh.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2qkynndhk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2uglallmc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2kzwcvwdf.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gt2lwfsrwas.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcpfbuas.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2spzzvyib.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dggoyhmb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2zusfhtly.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gt2dafkasap.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2ugaymyse.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2vfxnqpsw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2exotbukp.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2eleoglze.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2jriolwjp.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2wrqjtagg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gt2quqisfqj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gt2cmyjxzue.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2artfoszi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2xjotxtsn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2rmniudqk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gt2lmnfgzvo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gt2lrilulsz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gt2jigpexyy.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gt2babtqdvk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2sdijimog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2uwzdgbrt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2ddkodveg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2wdmaigmi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2kcinulhq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gt2edhrfbwy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtunxxkt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2patzfmog.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odxbphnw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2kyxhctzl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxskfdow.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2bptynsnf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2enupktyx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2hadrhnek.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2roxyusjb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gt2kizwdtmi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gt2tdurhfou.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2yysmxiqu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gt2jimpsder.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2hckjvbzc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gprzavza.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wfvrvfii.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sarcbdms.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2gclotahw.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2shescvni.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2jkelyvvh.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2nfnagmjn.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2dftftukr.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2kippkxli.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozjylmzp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2xtejuuel.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2pukgenas.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2xnwxruml.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjmbnbnq.html

C#:   File.Delete("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2dkjjpspm.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2radirkip.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gt2tfmgttoo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2vwfosigh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2npqtbsdz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2widzycdn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gt2safcdkqo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gt2gmyglyjg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2cevmlrqn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2oecnlmhk.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gt2qoyvkjps.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gt2jefykjmt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2rkhrmpmv.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2slvjrtzx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbkebwup.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kykjffch.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gt2pxitweas.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gt2furtvckf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gt2ftidybtv.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gt2arafzvxo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2gzhkzdfv.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2fmhyyaco.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2kgalsnsz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2zclipaxb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2frudtymi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gt2prsemhjx.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2uemqmyjs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gt2nemlsfcj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gt2lpqvvzim.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2pxfbnoxu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2gubnfgex.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onyyligb.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2pjghgewk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gt2phexajpi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2cwpjwcsw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvgdoirj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olebxvli.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gt2fxbktnod.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ztsevscq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2xlltogmd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2zqsisurr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2oislcrpi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2qxwypxke.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2hldwtnsg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vqzokcal.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gt2vjwpleef.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2jecyxceq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gt2bcrnlnwg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2dbtlyhoo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gt2xvwtqlsc.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2badwliyd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gt2ltyoumtz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gt2uhmkwnzm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gt2nbzofmcp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2jhhufjip.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2btrywfxy.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gt2vwbtckio.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2iiehyevc.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2lecmsqav.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gt2onfohhre.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ndkinozm.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2noczwwxb.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gt2gtzavbvj.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwpshndl.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gt2naykpvdc.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gt2wxcmrudr.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2vqmvsxla.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtcrusn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gt2hephscdh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ccihyauh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2dakgjlai.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gt2xtnuxfms.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2aqwahzpm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2xtupuwlu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2tvfsisvr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2ahuescwv.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gt2bwurqics.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkxxyejm.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2mbruutia.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2efoirsio.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2cdpysplc.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2ikptuyfq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gt2xqykiyqj.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyrjcfgj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gt2ifbradjq.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2ggoitujq.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2kxibkcag.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2tnblcdcx.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ubhkchrl.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2nczgtoyl.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2jtkcquih.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2xlhnajys.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2ukqjnazc.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuycqrtm.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2czhqrkkw.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2bdgiwlrt.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2dcnslhbg.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2qmgllisr.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2lzftwmmz.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2arrqntjw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xulqrsaf.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gt2hqtyddhx.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzgxxifu.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gt2cqefzbuq.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gt2muwhbzrc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2gisheqwp.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2claaqfno.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2vlkarqfp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2fwlzkhhb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2niamzofn.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gt2nlsoqmaj.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2hqcdiksr.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gt2xweetluk.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gt2obgafgyd.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2jhxkuqxm.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2reeuwhwg.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2nfdapcqn.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2awnycizx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2utnnjrmf.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2kqcxbtlc.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2fhugalct.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2kquxgvdv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cglibhdx.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gt2xnfxlzug.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2bowxboqa.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gt2spvmtocs.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gymfqhkx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2lzaikaed.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2uekqdqhx.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2rdnsbdie.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gt2yeryljzb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2ovzcnxev.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llgyzztl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2fkwnxggk.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gt2xgjlttid.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gt2uvxmloom.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gt2anzjjrrw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gt2xjwswnfl.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2osodzvch.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbhgynoh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gt2nwmgbjfp.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2ovvpytna.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gt2aouayuqy.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2dmzukewr.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2vjrzykeh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2uxwnhbcf.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2dhukroel.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2uazdgqyt.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gt2krxjlnxl.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gt2bemwnywy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2pawjiyhn.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2stpxgzlx.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2hqyvdouy.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2eqmjomog.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2fjsukqtj.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2xdfnfwwv.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2brmsvphu.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ufzzdwlx.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmfvfrug.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odvduwjn.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wajwilll.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2onwuiswo.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2piobykbn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2dhcwgkyp.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2dxypybaw.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2isiaghhf.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gt2qdkkpoxu.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2vknxvwuo.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2adxnejsz.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2niyinpiu.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2lrprakhw.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2feearnkd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gt2hvsuvqwk.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gt2xcoqqbmo.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2ijhkieis.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gt2peenzlqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gt2awbqdpej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gt2izjunoee.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2rzeuotuy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2insozqun.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dyfwuzha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gt2laaksvht.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gt2edxfqafa.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gt2cfmfbpds.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gt2vylaroci.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwiinxfm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gt2ennudmod.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gt2qynufnyc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2oqhrpxre.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gt2xngghvaz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2ansyuglx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gt2tctnwsqc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2mwlrorqm.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2jmdkcpqy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2xribszzw.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gt2ghxieclh.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdyabzon.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2sfkbdzhp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gt2ehacsrxz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2tgdvsufu.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2hzerjirk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgyojgy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2swrfogqp.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbxgjzmm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2lyplyuuy.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gt2qqvdohzy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfjrnyl.html


<!-- 参考信息 -->