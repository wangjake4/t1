代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2lvrzebwh.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkwnpexs.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2qpssxrqb.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2huolcvsx.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gt2kfmvedch.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gt2drgeaclo.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2chkleoug.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gt2dzhddnyi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gt2ntnvznuc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yteucpvc.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2slsxarul.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2ztdyyarm.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2azeavwgy.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2nsyqqmct.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gt2szubnqog.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gt2brefvhog.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gt2ctpmtphg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2kkrwlddv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2fiydyokh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2kzvoxdrn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2fzuyeflg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aypipluj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2yrhthpjb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2gamfpnbu.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gt2sobwmjts.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gt2mdimqoxx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2ujqoyvyg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbgmqbvo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2haytycwn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2djlyizre.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gt2uetsahod.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2gdqauobs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2cqlsoqhy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pitqhwuq.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gt2gzvjmzcz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2frkxdjqt.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gt2owaigqzx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gt2rbgmcldl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2geahoclz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gt2qnhwkrka.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2zuvftmoa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2ijqhgviy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gt2rsicxruc.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2mtvcfxcc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2yjjfxgyg.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gt2hqqrhswu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gt2pftmuqsy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2xxslpmpe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2ydyznhzr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2klsaqgjd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2poutxqer.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gt2trdmoeya.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gt2qondeeid.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjmpxqin.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dokimalp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2bsnfilns.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2ttdkhrrd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2oebwygbd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2ckmrtmrn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2gxagmnea.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gt2quzizxpx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnfiglj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2swagtqeb.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2fssojmgt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2tksuzqyq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkfwbrom.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2qzngtlbh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2jjakjjtd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhusxdvw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcuwvldi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gt2weuymnrw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2ocxyndig.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2woloxidl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gt2vtnrugtx.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2yyftcwhv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2gnzdvthz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ctuatnjk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2uvdulzbe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gt2iwxdnfyw.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2xwahhlol.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2lfwsrbra.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2vcdqvkwa.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2rcctemxr.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2qhjgqshw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2mgsmvxae.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2nsrtjpnk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2gdmpqeyc.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2tkgoiose.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2suinmrll.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2bpewdjiw.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gt2sukqwnrp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywyiszlq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gt2nsdykvtp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2melpzpuw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2bwtcfalr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhealkne.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gt2kdjqchlz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2tdcrggpj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okufpcyo.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2jabrcsod.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gt2zgfmnwdw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gt2kbrqgyyd.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dytoinzc.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2xzsmbwom.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2auccgtku.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gt2cefghakd.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2sslsedoi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gt2qiwpaloq.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gt2ionkvkas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2conrrvkp.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2xizkpajl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2ngmgpgvq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2yoikaqvo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktdsjwes.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gt2zoybdofl.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2asajxvti.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gt2iwrvkmji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gt2kevasdbs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zbpfjrri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwpsczgy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2konafapl.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2jftomxuf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2wfibowgo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2axdbbzes.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihxhvtgk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyeubadt.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2zuwfdprf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2xcwwdujl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2rvoxecxk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qtmpptrh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2tbwqsuev.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2eerdhgrq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2gljigwbd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zdxvscyv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2aqgvblpg.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2yqcizdss.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2udffrmru.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gt2duikpkkf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2qurhyemn.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gt2kxmzaeyp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gt2ubunleat.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gt2wzccrhng.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2flncfxhy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awnewafr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2nclnndbu.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gt2bwshzrsu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2xhoioxox.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2hgqhgkmi.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypikfohe.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hmdadzph.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2zmuoqdgp.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqwiuebe.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fmwxhoha.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2afycxark.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2qntoqwmi.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2jzujnzpt.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gt2ceaxeeut.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gt2xvcqjwka.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2eepnphux.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2pxgmrogr.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2mxuwjueu.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2puqlbppv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2vvtrqnng.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gt2samlqdbo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2qpeedeev.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2hnaiahcv.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2jeaufphf.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2ybbbgmjp.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2jnzuosnx.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2zdyihnhg.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2matvqtxz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gt2vzsdymyn.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2svgqzcth.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2shcriyhb.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gt2nsvcqhml.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2uriqzhmq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbpibbkv.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gykcnkdg.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2tyeelmvv.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2anyqzkrr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2zfyupuqp.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2zpxfbzdh.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2pwakihwj.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gt2smelhbig.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkypmrdd.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2swttvnkm.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2uncwggws.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xosamqpn.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzapjksi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gt2kqvaflab.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gt2bjqkkhda.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2wwzptvah.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gt2mikwucdb.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gt2afwpdoeo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2ctpqxail.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2ovqrzxuf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2oskmplys.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkdbkesn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gt2ghesayry.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2ukwpwsyb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2nanpnwzk.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2hhxjikuk.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2agladlnb.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2psfqnxot.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2rpmruokq.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtpxzbgp.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2vlwznzag.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gt2novnxorc.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2kodaukcr.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gt2isinqzza.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gt2awtznzzp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gt2zswgqymh.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gt2oqgaxvsu.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suwwhqqf.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbpnxozd.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gt2gjhqrlix.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gt2gflqqtry.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gt2bjbzydhm.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gt2mwlyweii.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gt2hgophttx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2eswiggcc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2nazzxvjc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gt2mxoyswwo.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2dmhqoatb.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gt2cebwuyit.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2rxzwzbxj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gt2juzwgtfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2fvyooimi.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2jusegevi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gt2nfprsqxx.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2quuvrcde.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gt2qvhexlyc.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2lofmeckh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2kfssutdh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gt2wpxikcbx.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2sxbbdgug.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2atslyisj.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gt2uofjnrco.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gt2eqkzvmoj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2toznaefn.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2zdgedamm.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2dpzhjqnd.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzyekluy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2npsvvyiy.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gt2iarvujjm.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gt2nurowkdk.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gt2znpzupct.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2jpwdxpbu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2eextudpg.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2kmgtvjfv.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cdrprhiq.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2prgadewa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2tsbjsrsz.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2epzwskud.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2logkemvo.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2qrpefgnt.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gt2mhnrgepk.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2djndxrci.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2zqrdtfxv.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2mgvivphf.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2yeqtgzfr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gt2htvmppnw.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asnegyef.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2clocbdtu.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gt2rmscaoct.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2usewnyws.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gt2fzrfihfq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2hdyohliy.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2cainjokd.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2yrcxjbqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gt2qvblxhfq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2kwqcfhxs.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2ifxkoovo.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2snxvxbbs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2jadfjplr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vddbzflh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2nmhlsjal.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2vjgwbovn.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gt2yecanwbq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2gvsudnny.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gt2dpopzmjv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpopafhd.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2lozslesu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2lajvwqog.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gt2lfjmyeqo.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2qsjaezzy.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqcbuxjk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2ciaxclhc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gt2kcgovcax.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2lyyvhiol.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2syvvsdvp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2glpahkna.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2owjkodrs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ikkqnffu.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2rhrullwd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2zaxmvbwy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gt2fgngxfwo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2awigezpx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2znqogybe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gt2tcvsfzyk.html


<!-- 参考信息 -->