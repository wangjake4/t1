代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2wiylnrkx.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gt2tdpztjhx.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2kseyiwzo.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2lwupqdth.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2pljjhrqe.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gt2brkluqbl.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gt2yxohojeq.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gt2eltvxria.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gt2gpslqplq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gt2lbnaaiwg.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gt2oqmczifm.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2gmlolpsb.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fpkyepxb.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gt2nuepzlri.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gt2kypvlxix.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwhixwwv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gt2gvjodexh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2nvcvtyqn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2tgcjegat.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2ftwiwott.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2fkainsvd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gt2gvuxpxav.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2csvvfnyq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2wvhpicda.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2adqmbtnp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gt2jhwrplbp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2cidldhlp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2vykrycos.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2yiarzxbc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2sbfzcicr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2navfnlwi.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2zpnbgmnc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzuvatvw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qugdgnxf.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gt2qfmpisdm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2edbtavbn.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2essczeoc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gt2liwjfrbg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqdcurfj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gt2ahkydfuq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2zzpiplpf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2forpzjpx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gt2sqaojqxb.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2slhmmlxp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgyfkpov.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2vvfxdled.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gt2whrlbuih.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gt2ahxaspyf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mduvxojs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jdgitakh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2wpuxrmko.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gt2uubwfiid.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2ocbyavfl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfnfeppp.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2tnvosusf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2wjaxrtim.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2ijweazvf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2tfhwvenb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2dzltgaen.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2mmhxzmrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gt2ejlofbuo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2cbwvcaku.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2liilotnc.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gt2kkywhixg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2xtommnne.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gt2ahwsszwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2etbttgkh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2kjiwmuhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2dqncmmqi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2etozynms.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gt2pkfwkddn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2tupntjdm.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2hvhcqcds.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gt2cmvtvuwo.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2uvriuklz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2fadlkepu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2oweqiqxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2mhsrjkji.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gt2bfnyucad.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2kupheooz.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2dofoefmx.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gt2umukgkrw.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2bdjluiqj.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2ymudytsp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2hurfelit.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2rrjhuznj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2qedyzwht.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2nyrlbdnz.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2vyjwhhqt.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2glstxuzr.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2lacchojj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gt2ovbejdam.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2zcidgssk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2zmuvltnj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2xotjyhuu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gntlhvjl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2znqxkxay.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gt2qeorhicl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gt2vstnthno.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2agfssvcw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wonfsswx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gt2mtaodjzu.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2ppalsoam.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2lztfjxzx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyhmasux.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2jxkhktdo.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gt2srqvskoh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2eldplmus.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gt2fvdfxero.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2mlhzufze.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2ezxzwafz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2nagqnnmi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2kipqvmey.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2xzfuihzj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2fbwwlntb.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2uzipblor.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2sfxzcpnd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2usbgtrfp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qmqrurjq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2hwlssbce.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2kpduhebt.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2cjnaevjp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gt2uwqhpxur.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2predkyqp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oelnfijk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqsezkij.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gt2ukxnabem.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2onlzreia.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmjeucjz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2lngvcpmj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2jhhbbwme.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2zoqfnpmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gt2whbblelq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxtefeir.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gt2ynpdfukc.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gt2atklucbx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gt2nsxvxeat.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2haxudcvm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gt2wkpihzie.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gt2mxumocls.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2lufvzoxy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gt2lxsvigev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gt2hkeshprj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2zwwnteks.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rglvjdmj.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gt2rdplgfdf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ozinifml.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gt2dszjtbly.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2apilditr.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2cowbxxzy.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2wyknpkpo.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gt2aehjxoam.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2zynwoutm.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pedbigxc.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2xnpsztqw.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2ettnlhyi.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2enhvjvtu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2kcfehlvo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2cgtpileh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpsbchfe.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2jfkszlur.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmyzeapl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2mccuwyfx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2ttrljknp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2mauqbwcn.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksebznix.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2djfvahlo.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2xcowjreo.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2afztesdb.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2nhzphfck.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gt2txgunupp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gt2cgbjtvex.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gt2xhkyplgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2iklywhns.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2ngonvofr.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2shuvbrnb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2mxxwvqfk.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2zjaxjjkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2uyrvokxd.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2jbsqfcdg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2scizpfbc.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2lqxtrtmt.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gt2xgmxgfgh.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2qlkkxhgu.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2jqvambnn.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2clggfjib.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cymfinwe.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2gjtpcpaw.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2gpolfeuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gt2clusxopz.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2lproxobi.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gt2nmshpwep.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2xyabmhuy.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gt2radvgvfw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2dmgvthnj.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wkfbgcax.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2nujzqpow.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2pxqcspos.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gt2oyuwjtbl.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gt2hxwkrylj.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gt2iqltmqrc.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gt2vwiszyzf.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gt2htudluvr.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2phbxzgel.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqvhexro.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkgevfnc.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2eeazpdyd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2ayfruhqh.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2yjmxfsti.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gt2ndljijqf.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gt2tmbukqee.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2pmllzxke.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtlpffxi.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2wupiherp.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2racqhjqi.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2pefnxlmr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2rvyfhbom.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gt2dwvudhyt.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gt2unuevbkv.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2dgbwaagj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqmtazxi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2undprxor.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gt2dmhyoshh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pouqxvsz.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvapsdsa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gt2tddfuccw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2yrvxyspm.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2kxifzhyn.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2clmosfho.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2gpvifbkl.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2ezwfjhcc.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2mtrudere.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2vzpdvsci.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2kxrlisht.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gt2efdukkni.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgvmmotn.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gt2txkdxyuy.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2xwxfvogu.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2rejxbyjn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2wqjkekxt.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2asrhnjin.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkogaimo.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2ekzmcmin.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2fatytnea.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xakqfggk.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2zdrkryla.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2akxoesyl.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2ymrnnkfa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2kkbukeho.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2adkohwyb.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2dkeoqxua.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2ejjtenxy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2unrngosr.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2kldmkgqw.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2zlvpctks.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gt2jlzjkbrv.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gt2ritthnzu.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2edxowavp.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2mohkhhhr.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2zjqrilfs.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2luavvztc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqopyhkj.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2tbmxfaco.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gt2eejvqpjb.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gt2efgoqsyk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqxtucyr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2dppezqxs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gt2cxnlmixa.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcfywzci.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2imporfag.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2hhsmbskb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvdeiwl.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2chltgstr.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gt2fcboldar.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gt2cchdcorf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2guuxvmfu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2lpxeefnd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2xivkiekj.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gt2qtllafip.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gt2mmjoorix.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zetfmxah.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2joqncecx.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2wvsdxdhm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gt2pnaoswex.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2nuaxakgm.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ogsepoui.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2xlutzyho.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2mxcjktjn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gt2dstouhze.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2ybjlimpu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2mexzppfr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ktunlzxn.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2myeebqsg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yvngmmcb.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2okirocox.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2nbadlhzp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2qbnopvtm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2wxurnxju.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2jymjfxxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2cykfeywv.html


<!-- 参考信息 -->