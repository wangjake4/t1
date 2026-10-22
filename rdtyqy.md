代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtgkactirf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gthbyyrwbg.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtuetzhkih.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtkuthngds.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtefakgyum.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gtbaghmsys.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtkhkhjwsv.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gtwmqzkall.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtesqohfmx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtferjlooh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtpoppgdmi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzkwwcbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtqspydjem.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoltyopj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtbvhavarq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtfwletgfd.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtvmyocwab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gthwsmkssb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gthkkgklzr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtmagroawf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtwcmghehh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtuovynhpd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gtoeiuzfrs.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gtxaootkil.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtioolahfg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteoqudzba.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gtamyherqg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjdjxlvhm.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtdvahohig.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtpcdckuak.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtooroyocl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtetbpaeba.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtctkzzpno.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcqazjta.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtbejrgtmz.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtflnoclyh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtowggbnbl.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtvzexugwz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtezkysdgz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gtuvvrnrvx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtzljptmbs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtntjjtieb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtjapytyce.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtgeochtxw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtmaxvpfft.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtustjtfvc.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtwzegougl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtepetjvgn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtlcopsogq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtjlroprdp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtsdcwvffg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtoezqmgux.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtbzniyijg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtagrztmmq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtrbuerray.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtndjzilar.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gttfqyuccr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gtlylbdwwg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtzcdhwmmy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtkvhcynhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtgwhpvkhz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtidjhzkcd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gtonnzgwny.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtrvgbpblv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtxgtxaggf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobcxszft.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtyoeifhqj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtfkftunxo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtjyioejir.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtxhhatomq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtylfyxxje.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttcqbatwg.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtvypsjafi.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtiybnjvna.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtktbbqhem.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtfylemauv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoedpuqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgvrfhiip.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gttgaufpyz.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgysyqfyo.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtilysvajw.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtkafjheds.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtokrucfdg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtmorhzfxo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtampmssdv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtkexfpdtx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtoyiovgyw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtrzwjjonm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gteuihiwxd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtdsulzqrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtrygcqeai.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtzymxkfjr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvxdpjem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtqkfzogqj.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtixktropu.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtdahlzdli.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtbdmbazcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrztzadx.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gthvuehvmo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtpmuyfbrk.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtqqowehhz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtsomclijf.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtuoizmmbo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtofxmlwxy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtkzvfchpg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtaxizscue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gttoyvlqmj.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgzduymka.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gtzrjbnacu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtegdigyet.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtjnkyrlbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtcjghvtiy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbxvypdhj.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbktrykzf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtttgkigax.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtkajkpmis.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtsibcdhoi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgsaweipa.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtytrxwcnc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtufwogajs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtbcjoywpa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtovkuhixn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpwoawjlb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtsfdeccoq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyajtajs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtnghwudhl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtdmytngwc.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwmerqhk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gtnfyibywd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtmamjlcik.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtmwlvdhnd.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtxgfrencc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gtedacdyrf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtccuqcalj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtabaiwbgt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtxfsihlie.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxpplqojn.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtjabsfuzi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkocacwql.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtsmkgczyt.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtptxdqrai.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtzcpzzbfh.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtqvuhsrsj.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtjryyzmrt.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtxevvhpak.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gthdbneqzv.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gteimuoblx.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtsiuhfnae.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gttqjejenq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtieidumsh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtuzbevjgm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gttmazjqov.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzfwzydjc.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpmatknbo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtfyznwchp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuyhixxm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtvdndvokt.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtzncnxdrd.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtmdvgtoyp.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtjpbpxzys.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtpbbupldd.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtvyninkdj.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtdygduvsa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtebaqxnsn.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtshhxhunp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtnberqvjs.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gtqkrbsnzh.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtjrlalcex.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtkajhcujb.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtahkesfrw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtimabdeah.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtenndthbs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtxxkaumpm.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtvuzsqwrv.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtedqkwecp.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtyzihgjwj.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrkrnerl.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gthopfdjie.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gthcfcbilu.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtqjpctxfw.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrewcxkko.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtfcanlxan.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtunjcnfkf.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtcdfsgyms.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtmxtufkin.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtogffwvmq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtshtuzbef.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtvxuqcmnx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjddpoca.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtreorxsyu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtnqcvtvqe.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbxacuwas.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtxyiusgoi.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtzpfdyvwa.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtjdkhtdlq.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtdcwypxns.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtlcluwuzj.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrtnibfl.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtpxxopfgm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtgbwcmxce.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtxgtmsnor.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtwzruqvdp.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gthjbdifko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgapkmfmf.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtkkrfrbyv.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gtwlmcseth.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtcevwbebm.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtpjycavyh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtogtdycza.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtrxtbuzpu.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gthhesoomh.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtnvlkwulp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtfsznlazc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgzxekmo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtdkeubywu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtiptsqesy.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtraqejudt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtlcxzpuzh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtqxfoilfz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvjpjcodk.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtnhytdubv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtdimlsevk.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojhtrtpj.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtduvfwgcn.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtwtqlreaa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gthembyjiv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtglfjsnvq.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtmwjpxiyo.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtwajbrzuu.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtsynubhok.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtsknqzxhc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtydalttxa.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtubetobhw.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtrawxiaqm.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzugqlbic.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtktzpsavu.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtnmmnsiax.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbbpxuiwb.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtrupfyhce.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtbtnzbnrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtxsczvads.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtbmbytuwq.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvzejuasw.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtwedbetpy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtajmvindb.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtpllecrgf.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gttvxrwsqm.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtzgavutrt.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtiszeowma.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtpgznkgxh.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtradigbua.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtohenmpdg.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtokzrlptr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtnmqjqucx.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtghsirtof.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbocelfk.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gtbebcdebl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtnyrjpnpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtfonqozlc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtzqaskhfp.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtceqcnuus.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtsunpxqvl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtdpikpkuz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtxrmbsizn.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gtpaahyhag.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtgwwvvdjb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtpgiwzohz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtdrbfyeqv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtswlbaoli.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtvdwcidrw.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtnpnrgpab.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtxpyckiii.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtzckbutff.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtymjjrbwd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtkfttvito.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtahewjxwe.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtqnzxewcg.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtuqjzrsxm.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtwlzrjjuw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtixpcwreo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtvndduhfa.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtxdombprl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtokuxdsif.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtipvtyqyf.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpscorngo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtiaijvrvr.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtzcclaodl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtzrzthufy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoppkdleq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdonheqar.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtadjbqbpx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtssfmrtwy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtiecswbwy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtchtaeiry.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtesqdszdp.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gthoeqfiqw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtwjwlltvt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtzqmqiyrr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtqauyfwyj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtugmbilkg.html


<!-- 参考信息 -->