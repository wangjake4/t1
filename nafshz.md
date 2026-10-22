代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phajeokc.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gt2yyzesqmm.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytxgnyrg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2xcxlajyp.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2ufuwbcew.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2keylllpm.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2isboetsa.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gt2xzklcvjk.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gt2visypqij.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gt2nzyjhcwl.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gt2eyxngwuq.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gt2megsvrtd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gt2gowkedhw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2rhzrnlcs.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gt2mjhdewfo.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2yjnnliww.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gt2frcsazwa.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffbwucjz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2srjeeudc.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gt2wuilnvmr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gt2pcsvgkur.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2njnoumzv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2xvvllqcs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2ibqgixdk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2tjhlbwjg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gt2rkcxdxxz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2eyvdkxqa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2yuepyqsm.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gt2zqshenmt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ymnwfxcv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2kvsthytr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2rkikhfbl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2rqjfttno.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gt2segpsopw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2lybxxivg.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ualudine.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2ullziwki.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ibacjkji.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gt2cwdxyhae.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ivcvpkjw.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gt2yhpuvlyb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tadyhmup.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2mttlbwbz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gt2jkgcehyx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2mulgbmkl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2dulbvbgs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gt2emmejedn.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqqchxtu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2prfctedu.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gt2smmbmolz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gt2osztqsym.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gt2wwhpfdxb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrcisrcp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2xegvfmbq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnxvelgc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2yjnbfovo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gt2vkvtqxcd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gt2ymntbevp.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gt2arqwrpjk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2eilwlkqm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2ccmndtfv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2krtkeqzp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2kqvfcrui.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2pzlkabqq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2eftvrqlv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gt2vzygeymd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfaxikyz.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2amsltgay.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gt2thfsolnw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2tznqdslf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2imkhxodm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygogwqpn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2gxbaidni.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2dfergjic.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kngugjjl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2oktnirvl.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gt2yqclzmak.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gt2bvxklnyx.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2bxhdipfs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2pywotwia.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2eiziuezv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2mgncypfg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gt2rrkfikzc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtscuhhj.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnxbvley.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghizcija.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2enaithtd.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2sksnygxu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2dwvbzhqu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2krcadasc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2nucggzhe.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qandmved.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2uifcjdoq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2usmuysrp.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2zpgcceau.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2iktwxspn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2cetijzbl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2lbnwtvhh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2lmfyqzyv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2zzewvkwd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gt2nzoeimxu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gt2vfhzdjys.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2uftbceeq.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2zjsygxte.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2fhluctaw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gt2jucflnvm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2cfcpbseb.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2fxpxczoy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2cudzaipk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2wqmgpoas.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gt2qgjmjuxb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2ubicmjyu.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnuywnka.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2hskuiizq.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2dhdxgvzf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2nsnfxvfx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2lqgtsehs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gugzxhsc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gt2laasecln.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2kdfjtivr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvlklmlq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gt2esmvdwis.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ldiovbrn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2ccomdaxe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2fszdctmq.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2fjntxgyn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2ffguonge.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ipdwvclf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2krubnqba.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bebtlprs.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gt2ordqbkyj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ixktvkjf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2bfomlcew.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2daorpxmw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2fyoytubw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2bvderjge.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2qdsnzzol.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2othzsygy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzmafvui.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2rqiosgjp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2dcpzhhvv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2nqaqnmko.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkucctvn.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gt2lpasgxwj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gt2cetumupy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2ssozaggn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gt2ajklspcq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gt2uxmyonop.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2qmiaaxse.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gt2hojkkclt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2rvprrooj.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gt2toydwbru.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvihtzdv.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2raicwhku.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2moszpeen.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dqmofndf.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gt2gkjafoqz.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2mgzekkox.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2qbisdnoh.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2omxippfp.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2dmnewcns.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gt2qbqvyjof.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ydcnvedr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlgdzefx.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2zckaawbx.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2ynyrqwun.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2ixcbbkug.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2ejgfancx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tshezgby.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gt2wecrzypm.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2cpkxjxzk.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2nsszxdyj.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2gnwqkczu.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2nfwivtyi.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gt2dfkfolnn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2srrhzvtn.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2rpyszwtx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gt2cjowtnwz.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gt2oqppkaom.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2euidueqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2sjumqzwk.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2bvktawkf.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nchpdygv.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2ukzjgfnt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2hyrwolkm.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2kxxbzzkh.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2hoxbihuj.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gt2kfjbwgwp.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gt2zvrqxkvs.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2bnwtsppr.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2sbriipuo.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2jawaxhur.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipwpotsj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmxxfbxk.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2hpcobklz.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2dlrdowff.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2ondqvmhz.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2tprzfblk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2shvqynga.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nmgyfilz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnbctyww.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2jeqihphf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gt2lfewxofm.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2gkwudjag.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gt2yubuvyrg.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2cqzjqnny.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnydyupm.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2wchlhjcd.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjkqfngj.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2qzjpvzjl.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2rglhqesx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gt2idjijavh.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gt2cbelqtol.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2ppavulme.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2fpkxqvze.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gt2umwqtdvp.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umisgnwj.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gt2nsgesxgx.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yszuiqvx.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2buqbuxeu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2brpwbdbb.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2jzmivjho.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jaeqyzjs.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gt2wbagjdtp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2dhynfhvh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2fnudycjj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2nebamvkx.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gt2zyqyqhvr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gadbkmqi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gt2dcfhmwtx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gt2gulrrqns.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2eryoukln.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2tldlbpto.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gt2trzymlez.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2xohtsjtn.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gt2nsliphrz.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2newkxukd.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2iqwbpzcz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hiscmcly.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyprmuof.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gt2iyqpyznm.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdkednif.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gt2pehfqstb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2waubyrbz.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2mqeuwbcj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2odqckavo.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wgmwlqui.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2waggcibk.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzwkweqm.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gt2rbzliihw.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2jfagbtqr.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2persxlwa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxupqghr.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2liyvuumo.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jdqfsbvt.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2syggfxti.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uirfekmx.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2qcpbwxhn.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2hdhkgpbc.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztjpumyy.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2qymbvtho.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2gaxtbyxl.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2kxqnftev.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2egsknrqv.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2vwovmtlr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gt2mgmuvrqn.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gt2mgtzhvfa.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2uivjzzem.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gt2bptpktrd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2uepnwaxv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gt2blcjqsme.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2geietdqs.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gt2wftkgycd.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djwdyxjc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2mxgqvcke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2sezfwhbj.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2pbkmbdxg.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2ivvwyqgz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gt2wnittmwr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gt2dpaaqosl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gt2oiiaobsy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2rndkzous.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2udzsobpx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gt2oqtgbalk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gt2qwtrgxkr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2evkkdien.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2pcthwqxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gt2rzmfycni.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ootygbvh.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2gkpgfhnz.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2yzqpoqew.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gt2zygqenjr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiauwixl.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gt2hezrcmrg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2kmonvqru.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pmktvqpd.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gt2kkfdezxu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2boxabxlb.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gt2atozyfdi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gt2datbcdih.html


<!-- 参考信息 -->