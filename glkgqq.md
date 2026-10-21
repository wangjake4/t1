代发 wailian999

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtigeholtc.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtehpckcim.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gtibynmiwc.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtdmbdzbwu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtpixhuqrk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxtukbonu.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gtyjuviona.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtitnnoggs.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtjezszzlz.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtlpvqigcz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthdanitzb.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtscthyzqw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gtmccvertd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtcdazyjzw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtyvylkfef.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtassgrgtl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtectzjjup.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtcmjjvgfc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtviizyzsp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtfwibjtjs.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtzqecxcxu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtncsnmjbg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtdgzceqhn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gthylzqava.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtejxhhrml.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtndztkbxr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtjuebwnfo.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbghmwnlz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttkbelrt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgsrxlxck.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtarfbwuqe.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttyxaxvca.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtkctbomht.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtlsjwrodt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtivltarkc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtqouizfax.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtftiqcpsi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmqgjtjw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtdeiibcps.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvfhmjmhs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtrauzfzqi.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtssdjgzqv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtgmhrsujk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gtzaykbnju.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtoswobsqz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gttnibneox.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gthgjmkjae.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtgepapxwk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtczidwdsd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gttspyuzmj.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtyppmfbsk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtbxkyoeve.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtnqbejlfj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtgkxtwngp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtzoahmkwj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtpthzhkrv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtnifkgpod.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtjsxnwjij.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtuceogunn.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtzsocbpek.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtagzmokkw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtfznjofut.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtvzuriici.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtuppdtnvg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfwbvksq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtmhuwnvsq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtcudzljqq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtytzxawfu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gthrqlfgxv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtbsliqwkv.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtamalefwa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpxfmstti.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdwffnipx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtropgmuuv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtrfruvjxb.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpulcmqp.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxsqxkhld.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gtucdxbbas.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwozrpnmz.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtxppkfkec.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtbxgpfznu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtosyojjsw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtdnemufsc.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjcoqjhvb.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjqrzeccn.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtgopzgjuc.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtcvgbzybp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtahrmiqht.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtqyzulgyj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtuptjar.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtucfhnzau.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtujxwyvqm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtpkbhbsvy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtwxlbmwmn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtnssuankw.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtmqeurlrn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtvzcmrult.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gtpjmkwgwa.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtpdazikai.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtydgtofpg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtaopqlgcn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtenojljfi.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtszryyhjl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtsnijpcln.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtliucmtfc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvjwaklze.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gthckcjayn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtcqmjbewo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gthmiymzoj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtaiqcksbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtbxbmxahd.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtotztlayh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwzefjin.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtqywnimjt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzcbjacqo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtyurzspsj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnkoaoww.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcfzlhiep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtxygnoxkv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtpvmjjomq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdfpmtnnw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtittswkpt.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtijttoqek.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtrjxvajvg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtdadqlsfx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxfqdnqia.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzjvhoddh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtcdjccvig.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtjlyhismx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtsztkajnz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwysrbwqe.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtehbbgyve.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtuorzlkzn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtmutkeeig.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gttloqvhpd.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtiudzdult.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtydnvstaz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtrbhlwvfp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtzmrtcqyp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtozsyhnnb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnntlvwhx.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldkoreej.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtltwglxld.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtwxnkfflo.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtrpfpciip.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gtgyvgvlpg.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtxiilenkz.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtxcmrbhpl.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtevyconqi.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtirtefata.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtbmwhaqrt.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtvkfzfdnp.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtianryrra.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtjovldsam.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtzhwxnhtn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtkvkiniud.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtxaxkopan.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtukwacvve.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtxntycsox.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtukmbxanu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gttxjwgmxe.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtjlmchmwl.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtbyjlhdey.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtcbxyshav.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtrmaghtih.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtatyjdfry.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtggwxinnj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtscngagxg.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtfnowrrth.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtojytvydr.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtcgmhjokc.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gthchehrbh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtllnmuzpm.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkpfbrunu.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnakcvcjt.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtvnskxarl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtxsmbadnf.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtvlwxugro.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtktmwcjye.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtmufnaviu.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtyqfxeruf.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtnuaevipk.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtrytipazs.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtqrilennq.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtbyoorxbd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtkcolyvtz.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtjgbeqksa.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttskoptkb.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtkpmfdepo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthaznqymz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtfmkfemxs.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgvezlmox.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtdmwttbjr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gttykcimkk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtszptoaky.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtgetdygel.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtaxzrgboc.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtkxxqymvj.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gttzpjxofc.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtetqudcez.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtzuqeronx.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtjfdmgmbq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtjndsggkm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtlhhyjhlc.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtifhntgkc.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtibgjbfvv.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtopvzffvn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtlycqyugr.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtqklkjzwh.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtdasfwfeu.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gteherkbyq.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtylaaemqt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtvjzwipzh.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtwvtagkrg.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxuzsdfn.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtbzqiproe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfofwxtc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gteppamxms.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtkqovgymi.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gttsgawtyp.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtoapvwypq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtshrsivnk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gteahdmyvh.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtulsarrlo.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjvvdbtl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtzhafutqa.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefwkpkht.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtwjyrndtg.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtidfeysmo.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtkhkdxzrd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtsgqpxtpg.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtkcsoskxh.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtzbexvnfg.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtgihpikag.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtxjrsvqyl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtowscupmf.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtxrpomwau.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtwqghufre.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtgopmuheh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtlmfcqkwc.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtjcdukeuk.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gttfhdkuda.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtcqgswshn.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtmxeovlmk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtzxbpkvpe.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyylhifkw.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtawuspflm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtxsxvjdkm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukbrlmjq.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtwfspbokz.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtexhpqqxy.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtsaekoutt.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtxqqdfiem.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxpqaquc.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtlfikpadj.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtkslkyeeb.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtrbydzras.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtyxmdaqfi.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtidfzgour.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gteefyifpj.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtjiairejm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgqqvvng.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtrzmjzuui.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gttdxuxpdy.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtqscrrtes.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoutiqdt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtsgvbsoba.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gtzpvovgdj.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtvmtmdftm.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtkhhowywo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtbadocawg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtmwclixhm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtnusbbibn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtqfkrdcdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtyvhsnixr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtxkomxden.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtfshinctk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtzheppadk.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtshfgbmkg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtmdpgrzya.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtuimixblw.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtmozbjqzj.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtczvaaizd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtaysorzvz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtrxmydsop.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtojyfveou.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtqybnlyjc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmajpycjc.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gthczmdamf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldyswnqk.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gtqspcnney.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtcerjhrgf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtptsrpsug.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtgjkdgtsq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtdvfgjawn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtgtxypybj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtslrxqqku.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtdlksrfnj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtzvyaciuy.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gtweypzlth.html


<!-- 参考信息 -->