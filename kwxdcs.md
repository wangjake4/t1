代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2bgtlnkmx.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gt2ishugbtn.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpnmltka.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2uafejgvg.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gt2mvrdixus.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2sledqatl.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jiyduvsr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2nycvmqlj.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2igjzxana.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gt2ddtnpcmv.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2ftnfnldk.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gt2hsheqkqe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gt2brdytdcc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2oyibspft.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2efowswip.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2zkgqkixk.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gt2srcdwayu.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gt2lvszvcmo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2fabkdsst.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gt2yjoovjzm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gt2tijrzwbn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2oizhxdsz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2ftvsbcqr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2fqdvisgt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2oscqunzt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2ukpxlfxn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2rqukogzm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2ngktwlhx.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gt2fretgngn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thlrhrsd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2bxnnfppo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2ycmhuhrl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2zzerotna.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gt2dszcvbts.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2afeycjfo.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2mmtumdjf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2gyqznhfr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2fqjhdztz.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gt2ctnkbkgr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wememjij.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltihhocj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gt2orthjqzg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2wbgfierh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2vehtgkga.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2ejvqsjof.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psaindzs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2xxtinisr.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ivgyuxrv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2vpfvcwyj.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuezbbvp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gt2dfcrxcfi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gt2rxyugxvv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pyqsarcv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2wlocvvvo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2rmqyetpn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2fpwacjwu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gt2bbktlgvs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gt2haiefqaf.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyugblsk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2vsakhwez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2hlffjveo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2xmnioxqc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2uaqcxovl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gt2rxmobzpu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gt2nnjuvktx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbnsjzxy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2ggqxknce.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gt2gmzkigqi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2pckbucpf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gt2orpuulpm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2ghzoqvnu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2dcybkyqz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gt2qbpbqxur.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2wutdcmkk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcrsmrdj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gt2mdwpesbh.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2hkezwujh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2vwzeagmw.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2sqejvzie.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2dehinrlr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2iwjzyizg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2djxqcpda.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gt2sabygecg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2xjvhqbny.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2yvokmmma.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gt2hxccnwgp.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2zygixheq.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2ozmsrnip.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2kfzsohwo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2vwnubuqj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2ikqkgqda.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2vvgakbes.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2odvsbsyv.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2dpwxbkty.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbudcndr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gt2nokutnuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gt2vsawypug.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2lbvjcntq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2ejhvuyje.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrrnmqfm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gt2qvhvktxd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gt2ehkqnbmm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gt2clvxpiji.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2hdbnbfkn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gt2vfjotnya.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gt2qnwldmxr.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2petpwtyi.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2qjfuxqwr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2nkgfxtfl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gt2ioedqhqy.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2gvbfgqom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2phndocld.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gt2dcdkrree.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wtloqydp.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2jmvthbcg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2rvucscht.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2fslreaqt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2caceizpz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gt2vrxijrvp.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2jyascrdg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gt2xmtbwhtw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gt2bmmysmvl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2kelmagir.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2tfgdgjia.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2kxxetufw.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ghzdcojv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2kjfrmlza.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzceghbk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2zvyxnaoc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2sohysfjl.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gt2uvaqyeep.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2qmekorre.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2sdvwwfhl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2rtsmnpdm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2gwdwlpvx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2mbpeydlv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gt2irbfqpbq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2agbzjvoy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gt2sravbszm.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2xgtqnssd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gt2kqxdxgke.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2sitvezlj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gt2pbietmoc.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2esqffsgf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2ihlcwqyj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gt2zlyrwkgs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2fintvoit.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouhtxivd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nkobmons.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2gnsoshca.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2zvhetdhn.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2rfezrudr.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gt2mxopflpf.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2mwlxnqqx.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2jzdnfrte.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gt2oowvhoxs.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ltcngwyn.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nekcugek.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2kgkepgpu.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygeoltcv.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2rdjztdze.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2bisoopnj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gt2myhnynms.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2flpbyybe.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gt2aharszhi.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2udhradmb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2tgpmryse.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2glbgaqqh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgqixxkt.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2caxjzdwp.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2fxoeximh.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2qkezbyzx.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntrzwvby.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gt2fsugejxv.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gt2zfkjnwwm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gt2lgykjfmu.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2ptyzyraa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gt2kowlzwxo.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gt2kaxuzssn.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2hjfjwjsu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktzwifrs.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2jpdgugkd.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2hqbpzqho.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cstldgxw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2rfkotfsu.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2bevgwxse.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2idznzkhd.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2rtmeexuz.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2ocahypxn.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2yfdhmwya.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqgqdaky.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2xaftcowo.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2ydigzmac.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gt2xoajudbw.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxiuvkqa.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2iehdbadq.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2dnbnvtxb.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gt2qnvnwdps.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2lhdyyntn.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2ibybjuht.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2dstzbuvg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2etutzbqt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gt2xkmdopmw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2junkhult.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2canroebp.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2oepfpvsm.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gt2xkdxkaeb.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2upovraft.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqaxcwzz.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2mzypkdqj.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2zivinmjy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2qudxasrv.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gt2qomzekmx.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gt2otjfaobm.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gt2fyyxxste.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gt2ptporaxb.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2dqgwvqis.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gt2ydurkcak.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gt2nvjbheam.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2ouhddmlx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gt2uxqergep.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2swzjwkvh.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gt2fsoszcla.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gt2ydvbaajl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gt2gmokgdfm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gt2wztigmpe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gt2idkcigqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gt2nnsylldv.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2jvgdzhfj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ksdtzixm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gt2ratwsuen.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2bwupujve.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2kutjnlgh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwmcllq.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhvkutul.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlnhunaf.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2ecqglteq.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gt2qjrfgxjx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrfyaxpm.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2nyfzofwj.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2voengayy.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gt2wcpazvfo.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gt2lxodbxxi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2gxbayhnh.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2eppyfotc.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uurbgvbc.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2sjkqhbal.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2fjoqriya.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gt2itnulwzb.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ourgvbpp.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2nomvgohm.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2sjjkihij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2zngsswed.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2rczukmpr.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2zjknoiut.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2fbocrste.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2qwbcejvf.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlwbwoym.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2szyhnuys.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2gpdmdjup.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gt2eswpncqu.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2hszkdlgp.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgryfegg.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eaehachi.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2frrntqtw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2tqlvlioz.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2nyovtgso.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gt2aodoeyii.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymcqpxwu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gt2vemcemxw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gt2wfyxymon.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gt2yuuehwly.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gt2mlpqscrk.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gt2khcwpwyr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2fypsfwrm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gt2zojrnudh.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2ryjvefjm.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2clakaheq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gt2cftdpcif.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gt2lqxxjdki.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gt2uappgiqa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2snptavmg.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gt2fxbqoclw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gt2ckznotkk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfybupld.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2gnhocmej.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezogntqj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gt2xbcwejtw.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gt2cjberikx.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2nrpnaefg.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2isgrcswi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gt2oqpkgiao.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2annonemv.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gt2ftoixqoq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2swinhiya.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xpghicjk.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gt2azgzezqh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2moiczshf.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2pznvzbwg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2kdmntivk.html


<!-- 参考信息 -->