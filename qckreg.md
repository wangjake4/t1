代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2prigdrex.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2qhcedbew.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orpluuus.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gt2vppwkfaa.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gt2pscjgsid.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrkuuqby.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gt2nkawwnle.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzisrfon.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gt2rfksdory.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gt2zhjpdqeg.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gt2cxjkntff.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qqocadri.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gt2bfxduxqs.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gt2trttyldb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2occfcpra.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gt2eeryrlxs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2ltfhusdh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2xxwhiqpb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2hdtyiyjk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ybzxouwc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2agqheikf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gt2qsmbfihm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2brcgones.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2pyinjhfr.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gt2aokfziss.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bythrdoz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2kxntmjbb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdekaiiy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2drmeuemj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2bgezjvux.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gt2oxtlgxuh.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2hryurlpk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhcnytuz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vrulxaqc.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gt2knikfaex.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2eeuorcnf.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2hlqpjiiq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kaumsnmq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2ojxlcehr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gt2qdhnxrsp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2ieoprllq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmizabiu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtirvhqo.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ummbwwfv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2palfuudi.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gt2agmvlvyp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gt2qywqhvbj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gt2fgcpjnzh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ciuggmmd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpbazkmi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2rgsbtnyv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2pwxlnxlt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2zvfacnua.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2tbrnhrqq.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gt2qibamgcc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2qajewvcp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyajzpeu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2jyvqqgma.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2nzmhglbm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2bewqweuh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2ggqxszva.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2puqxlecg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbtyilu.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2dhtqzzsz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2attfwsin.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdqtmlmf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2vycoahph.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2tygcsbsk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2kyctywho.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2ggnsdhra.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2zmzbjras.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gt2bqovywyh.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gt2koispadu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2gkdgojke.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2nnebllmm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2emujohtf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2fallfslj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2fciotzzj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2nagzvyrc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ewlhpgjk.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogxdklam.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2tacrnjmm.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2xqrrwjfo.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2vkmfgpdr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2xbavuqdm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2voniocrr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2vsphyxas.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ewsvuzyk.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2uspekaxy.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2mqyuaslm.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2snakhfnm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2kabrcsvh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gt2lcibhcvh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2sevbycby.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2xgwewoeq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2fzfvtnoi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gt2tgqffrkm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2uudlkqhk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2vwzaensx.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gt2fozyyksz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gt2ggpydsqq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpsfnytq.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqprpydq.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2otzkrsla.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2csydofwf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gt2lyhtrxfh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lesbbief.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2vzfwxsam.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gt2kkrevnfv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2rdyexxeh.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2pdiibucj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2cxyfuejy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2cemytvbo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2utxucecl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2gxjzkdur.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2rucmfspb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gt2tofgenid.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gt2swnyzuxg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogeysqms.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2aurwhpxk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2bevgcalu.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2vqcwjrbc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gt2sjduulzq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2vwbujxih.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftplhxmc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2hgtdheya.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gt2eapenspt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2rbftrmqy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gt2bnprxpkc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2yvzrxqgo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhtmcwds.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2sovcfmwr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gt2kecildlb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2sfuzkcnj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2uhlxftcf.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aberuxyo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2enxwfnji.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmxlbnmh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gt2txxabexq.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2hgxffesb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gt2pxjubnna.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2irxmzzzs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gt2zciwijok.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2mipmmpkx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2enogqibs.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2xchqfweh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tehnidmo.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2occmkgjc.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeiijjcb.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gt2ifohdbsy.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2pcsmrbll.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2rftbgiwc.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2qrrnmbwm.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gt2mscplccv.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2czcyxgzo.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kalfiyex.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gt2upcchyph.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gt2jekajgnl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2wnpnwjra.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wbmrqwcg.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2vduisufc.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2nvhxtlze.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gt2ywoqrjpv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2klbirgen.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2bsdwvybr.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btdcapyf.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2opptwfgz.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2lohlxbwj.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2ifnixtbw.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2bnkicwpe.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2etqcrufv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2deyvfjwk.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2mxwtvmao.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2jfuvcpdv.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gt2broccgpn.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2qgrlajwd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qepggdre.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2sgnqiawb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2byqfbldv.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2aegzaexv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2jmpetspu.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2bkhxohbi.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2quhuhnyn.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2gnujlwaq.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gt2wdpdjgsk.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2uyghiuli.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2xrebjfri.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdkxzxov.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2liwefqly.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gt2aclpvwxs.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gt2bgvrgwop.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwodpuhn.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2srbzsghc.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gt2incjxyap.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ssjaeqzt.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2gvnrrsbi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2ulahctvp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztidwuzj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlsalgwo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gt2tuvnoebl.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2dbcfzkpe.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gt2liakswvv.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2kqbniixm.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2ymatymkb.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2qrvhjqja.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2egwujter.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2drdsfsmy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2xhzqfcyw.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gt2rhsnnmzi.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcxfdwiz.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2hhmtlupw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gt2qcvholrt.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qfqvjiss.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2gmcmgbvo.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gt2azksbydj.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2qdttecuh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2gizbudla.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2mgyltsyu.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gt2mevgmcga.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2zgipkfle.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2kachhwkk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbulxeu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2saqvrtuy.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwjsszag.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2mejxbych.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbyspaio.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2avwuknfp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2hundolyf.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2ncxldxka.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2jwgvsjcn.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipauxfrh.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2knltkdfz.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2ejomtwxk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2cgfqjzon.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2uujiqqoz.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2bofaioyx.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tivzltog.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2dbzmnnch.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gt2azmbrtbq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2dwovznme.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2eaxvzdnp.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2guqtyxyx.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2tvlutpgy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2sipgrfsi.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2ctdaboho.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvhapscu.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gt2jrcjzpge.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2rkezvilh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ewgvgsnc.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2smtmmpkg.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2jrwvckpb.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2obodjcqe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2wfauvhls.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cydzeuhy.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2bhpbwhar.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2ydokaufw.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gt2hcpoqxwd.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2ivjvntok.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2dmepwedk.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2attwrvan.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2pbmjrove.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gt2vilwtxhj.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojpuvbow.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gt2solqqphp.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gt2pighybvd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gt2radxjuil.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2totzcaup.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gt2pdwbtgay.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gt2clddcfpw.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2yzhauwvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gt2efeqlatb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gt2wtnsplsa.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gt2mgavmmlm.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gt2zpwbreif.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2slxyatky.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyctafmm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gt2fpqauvlk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztpbwplm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2wcjrvuez.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gt2osstmjks.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2vjvjbryy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcwrisab.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gt2wmjkthkp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2zzloxjmi.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2ommblyyz.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ppocodfr.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2uvwtyqmp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gt2jdngjhjv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2rvgxasuz.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2ahqmjptt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2vhkshwaz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2tcrjfovi.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyxkikdp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lbbfvnrn.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2cxmubvmo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2ctigasix.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2ekqmumep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2lefkpwbb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2mxymuila.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujvtermj.html


<!-- 参考信息 -->