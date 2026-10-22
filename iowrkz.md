代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2ojobppnj.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2oempeert.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gt2wqpqvacq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gt2yxekmfwn.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2idusgjyo.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gt2qnrwwsxp.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2pqwcmypv.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gt2awvwjxqx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gt2ofgyjali.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2asdttyqd.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gt2jxdqyyvx.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cpilfiga.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gt2tagvaogv.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gt2lgmuqmsk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2zkhblpia.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2nogdvyok.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2jvjrsekd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2rjgzscue.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2zejvzlpk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2xhdrzont.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2loibblqk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gt2tdyvxqeo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2aefnxxji.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2ppzekcag.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2nhanqmts.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gt2fmkvfopn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2llugcgax.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2mytjjweh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhnsequm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gt2zdsbldjl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gt2tdafmhyc.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2kqgxdwun.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2bzwvgavb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tcmkmjsf.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2luxlusvd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2chopvtmt.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gt2wrxgvotw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2kryuzqwi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ovmcwddw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2wlpbghty.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2vdugzebf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2cskyefaa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gt2tunsuiwi.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2wnhpbhgs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2knvznehm.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2baqwsnge.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gt2krosbmww.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mubydvdn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2bccjlaqj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fxmbhmkv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2pzucrccf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gt2lrkovdik.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gt2xppnzyma.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2nrymyvff.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gt2onverhkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2ezbhmuzq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2kndakmak.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2wxqgedss.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2vdsxpulo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gt2cvsacsnd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gt2zaedctdn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2sgxqkxel.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2bwuycmvk.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gt2hkoofzfo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2afnybmcp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2sijoxzbu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2anmppyqf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2pvmzjplq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gt2exvhgaha.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2vrvmukai.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gt2wxiolzuw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gt2lpbgqolb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2jfxomdox.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gt2bqjjtubv.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2sxypxyyw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2tdpcfwwy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2hvozaitk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2edcpyogf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igfvcmro.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xcfgibpp.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2cryefmcb.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gt2slgpqqps.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2kkjzwxcj.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2ibenauhg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2rxixkmqs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2dxasgubk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2hribhsef.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2azbwdsll.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2qiwxhmec.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2umqdnpxb.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gt2lkidbfyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2jjkpyqog.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gt2hkcfflui.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2rtqdpcin.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2axihevmi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2objszpvr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2qcwwfyes.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cppajrzn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gt2oryectpi.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gt2ssudnrdd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gt2emiqmvbe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2ijqgdysd.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2ordpfoxz.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2kpomdjdc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2kxubjzms.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2dijoeptm.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2fglcehzt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uisalnox.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gt2aiwmcgie.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2hshlebcr.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2zdkldslp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntuwssno.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvbtbcug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nldtohal.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2csrplhoh.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moulzvek.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gt2eaxyspoc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gt2sucwnghy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2bveykapp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gt2mgoxyyjk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2wtkstsqi.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtlzmtsu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2tyzboxrq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2dtrpefwm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2mcnurnib.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2cmopgpic.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gt2tlxupeok.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqicwvbr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gt2dovtosuu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2nyprjyyq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkjisjrk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2srbnqjgq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmneorye.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2thtntbko.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzdbahkn.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxzqncov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdnbpusn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2ihrnblca.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gt2udgrqntd.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gt2nhqqfrgj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gt2alhbhkvp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gt2nhmwsxpi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gt2bujohiao.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gt2ndzxkyvt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2gttbewlw.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gt2whesfrmj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mbqojepb.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gt2nmyyfngs.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gt2irgssudl.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2nmblgjcd.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2dnpdyyvx.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gt2ceyynqnp.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2gxshdnfo.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmpxlcwl.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2fbsgwcfj.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgerkzrh.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2hfryucpz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gt2nqjqcgbh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gt2hyyqcfdc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvpgvwhl.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gt2cuvevert.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2utuaebfi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gt2rzgstyix.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gt2vmxqqggy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbfhvqze.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gt2gulrwarz.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqeyftub.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2lxqztaxg.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2fxaljafm.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2zdtwabjd.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2xhfbmatq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2npnmitjs.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2khaqttjr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2gnchsjsu.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2efaiktfm.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2okbdojgd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2knoxnmpg.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2hkymmrea.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2zqiljzoz.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2dvvwhnwx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2bxddtvmi.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2wmalwcek.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2bosrkzqi.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2ikqhoxun.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2actxxrug.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2tchobjfj.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2pyujrxyd.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2wwohukxn.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqlwnpkt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gt2hjkdgzze.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gt2metmhtgt.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2aacnnocu.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmblfcrz.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fleuibcq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2paximuds.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2rfgnicke.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2foaknnty.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2guieuhrt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2ufserglu.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gt2ozahhpca.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gt2ilnyaujk.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srxqqsau.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gt2vukpcseu.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2ieabaeqq.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2fdpihqjx.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2daqqsfbu.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2yjsnvwvx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gt2mjxkonht.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gt2mezgqrpi.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gt2runyuork.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gt2rwowwrtu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2ajmpqlpp.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2vleequtk.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsulcuvw.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2qfcfwmrs.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2wihhgmmg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gt2ohfdjzjq.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2ncltwvqm.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2lydlwdte.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2ppjtcbpv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2fyhsvrow.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nahuzqvl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2ddfgmnkl.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gt2auuhuwjw.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2dhfuhkvm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2bazgdpae.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2matfpqzz.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2hkhkgbki.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2cpqzofso.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2uyaijryc.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2otehokdy.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sppgaagh.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2xytlnuav.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2lgmysboe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gt2jhpinlqk.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2jiryplgu.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2nhufpilh.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gt2fketfxpd.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gt2ikfivhpc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2maquqcdz.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rocmxpvg.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2lftarzha.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2iotwlccr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2bjvjzkly.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gt2asoqvitl.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2rlfwuzvp.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2wxcofsdg.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2ijtjwidu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2fepfnxik.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2younajjf.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2tiwanmpd.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2mtbvfvgy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2zhakkmtm.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2fzzoxcia.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2taebyxhp.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2jsaezxpp.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2seelgaiv.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2cqglpasv.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2hkgldxfo.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2fddmhhfq.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2kvbphksm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2xafeosll.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gt2bfejtqlm.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2qsddoeqc.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gt2aemtqzwc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2eaewavsf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gt2uafipavu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2frbzcnhh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2ksjjobdt.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2outplqjv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gt2bbzzrher.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2dwkrzcfj.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2zffukglh.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gt2gveburvp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2mdimtnin.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2kjyktwtk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2giawhybi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvbxizng.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2dyqtupdh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gt2mranwcey.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gt2blzgccjt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2uwidvfzy.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gt2tffmtdrm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehfphyah.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2ybobnpvt.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2tdwfykli.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2nczypuvp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gt2zemwafmp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gt2xujucoky.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2zuulufgs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efqaaosv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2bzxnbvih.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2lyrsyewq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rxofcvjj.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2elrkldct.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2blvaaxrf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2yklowrwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2khmjvybi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2oimszpky.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2ykmqragx.html


<!-- 参考信息 -->