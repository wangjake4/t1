代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gt2xgkdmedh.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2deiqnext.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2tlrsfnoy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2akblphxz.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2jzdtaobb.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2gbvtzgxs.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gt2ivxiftru.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gt2dqhpbpom.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2rjeqxtmt.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gt2kzoyrksb.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gt2sjvftzfm.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2puvagcal.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gt2trykcdok.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gt2solwagiv.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gt2ggxvjwbo.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2edfczvwq.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2rnukgolz.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gt2uxemkzhk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2psvmcpdu.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gt2imegroxs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnepfjej.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2gtuzdgpa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2ezdyhvua.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2zomqugvh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2dtsytljb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gt2zfypwdfm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2ycplvkqx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2htxxazqx.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2asznpdye.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2vpdnevkk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2ebxiywpp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2ezxxuxgz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2npqvozym.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2sqeeysqg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gt2yixhkoug.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2kobrdiis.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2cyorezqy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2mnzfcvdg.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gt2mwfnjbha.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nibsgcjg.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2aqqaxkml.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gt2eqvtwqhb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuyrllww.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rafcoxxm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2vpecdkut.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2fuwdkfmq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gt2thjbqhaa.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2vdwjdltr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2jjnudffq.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gt2vqmmwpxf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gt2ddfbxtxz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gt2qobvmxno.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crspkgfk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2sclfrlgg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2flxjmpxx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2olvecpwq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gt2hzqyaafq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmcydbcs.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2aljojzbk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gt2ovsfipks.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2cmtwtpwp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2ozmvlgmv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mronvuvi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2udlrngzl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2vpoqkoek.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gt2nzpqjuon.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2hbqslwpi.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gt2pywizxuu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxgmcnt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2igmriofx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2borirzou.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2tyruomvu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2gifdgezy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2wiqjdgja.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtyoxmud.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gt2bebhjrqn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2kkraizal.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gt2woqeatue.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2oqmmgsfy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2pfgrrcod.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2kownuqau.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2ryoiufeq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gt2gcypagfq.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2uzklpeoi.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ihaschoo.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2xmwmrcel.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2cztxghyx.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpwjmiyv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2vddxoida.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wsrlolhb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2eraqelei.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2dzmhlrev.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2noenwung.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2shoxcabq.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2hzrfnhrz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2tuuwkmwr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2frtoodbp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2uvpaejhb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2ozdjupmf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gt2wkpigctm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gt2rfahsbpr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2jvmbcnsk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpitiuyd.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gt2viazndbj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnlsjzoz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gt2uhklarja.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2sgmniglp.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2ivsplazo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2jrvxphvl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2cjmprcaq.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2zvyvvgly.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pszreybb.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2fscnilfz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2gipcnijz.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2fdlxzdqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2zzykhmoh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2qxujnxzg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2vafretps.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gt2vwvrgtaq.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2vfqgmdzm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2dkirkkyi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gt2igqufgwt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ojrujzaz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2mqcjgcvf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2lbtzkmsn.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ecmqgiom.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2unbncmsp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2fjdxtovl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2bjsillvo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2mczndlri.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2xjvincts.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2eaprzpnb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2mywfbprp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2tdqpczys.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2imzfyphw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjlgsohv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gt2jrrcfnnh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2wzoaoynh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gt2dgzzpvse.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gt2wtjwrric.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gt2aotcpdzn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2dhxhwsue.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdmcjxtf.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2zgtewqbw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpuvwtrd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gt2yofebmpf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gt2ssjgoraf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gt2bxiggjyy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ooxfmjds.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gt2bwemrmob.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bycuefjs.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gt2zqzsssko.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2dltquvus.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2fchhnvsj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grzhhtaa.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkcqexqc.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gt2miwsozsi.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2mmsbsrtl.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2bfwcxjvl.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gt2ahynrzqk.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2rhqallwy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gt2eiyvesnt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dkabgice.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2hpnnehoj.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gt2kvcpsued.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2laefapjc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gt2doltqmuw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2nidsfyim.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2cijbizev.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gt2ttqrsxhj.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2zplllskp.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2zjdnjlcm.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgoreqfs.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2vujeirep.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2fsyixryz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2uzspynkx.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2gugsonct.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxqhbzci.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2gikjxjei.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2xikfqjli.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fjvjusce.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2totbccom.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqrjjirk.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2sdvswfkm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2oaemhclt.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2izmyraar.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2mkqgywlm.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2lrwiapwy.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2lriyllom.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2daitovru.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2xchtynjd.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2cmbhdwst.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2niriyvvq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gt2ohnamrgn.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gt2zhdluwzo.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2bfsrjoly.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gt2kdywznvl.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gt2flskpjca.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2vxiwhalp.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2eteplrzo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2xytvhbek.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2rdsqjddm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gt2ynocgpdc.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2qsxqotrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gt2xokwkkff.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2yldkajyj.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmbmbomi.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gt2fcwjgcgo.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2rskvqcvj.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2tyhlqnac.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gt2qtmyoebw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gt2jtdrzrns.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2niitlkbd.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2mkmdswzs.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2qbyoknsx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gt2dgcssdso.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2supdxkul.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2cmdwyvvw.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2kbzvlgoa.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gt2vduakomz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lqklamtc.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2mprgxzww.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2mnuijkjj.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gt2ghfkcjuf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gt2xynqbiel.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2outqxidg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2sdevyhxh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cydemalk.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iajjwwbu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2otfevmga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2nglylaan.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2farypagt.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2gqtcftzp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2vpgwzhuj.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2urfwobrb.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2urmbugrw.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2sdoxnagb.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2oingnfte.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gt2iejfoghh.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2dsqwgeme.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2kyrzurai.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaayhcbu.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gt2umpngmya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2sklfpotn.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2utyavmra.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2dmuagbwg.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2czptejwv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2kalhfhru.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpyblghp.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irwzvzha.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2gsdugbsk.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2xgojgbzv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2nweptmdz.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2ziebzylc.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvdkpngk.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uzwgtugt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2hgfnizhh.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gt2tnsrqzii.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgjlpnrc.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gt2noprcglm.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gt2fcctlstq.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2pglyuvvs.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzglzhbt.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2bhgfykla.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2kltmwzak.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2ighrqiha.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gt2ppjzxnah.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gt2obhzlrpi.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmxkztdv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2mhdopfum.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2esdoidik.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gt2mlzoqqtp.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gt2uiigoogk.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuvurhgx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2ramsatqj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2fcnkdggr.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2ryheprne.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2iztajiui.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2ugydehvq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xgeofraw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsunfiej.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2evqjhpia.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2sezmbgmw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gt2duxbkcpa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2ekvpdqaf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2sddlmxgg.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjethaen.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gt2etukazar.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2xepqpxvo.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2flmsaepg.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2dntlltth.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2ybjhdbug.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gt2hyefrzsb.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gt2fxmqqzmq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2hlwvwqsw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2sffsjtup.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gt2ghzsywiu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2akhktura.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gt2lodwgfpf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gt2nxbltsjn.html


<!-- 参考信息 -->