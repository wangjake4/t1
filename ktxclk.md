代发 wailian999

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtytuhtoau.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtvxlvnhhm.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtuvxlxmzj.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtvvsiwgat.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkpjktmy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtsiivqnge.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjpaqzmnx.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtasvmawsu.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtldtfqhvv.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtpcmhzghy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheffhdnf.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtstxoacpb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtzyxsoors.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtmjpeqdhv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtiizarwww.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtzlqinpqm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtwindgilc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtwjxvzerb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyazhdlpi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtmlwvjknt.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtaicnyxks.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtwckmajex.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtentohudw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gttrdlglsl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtvsemcvnp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtrnylducm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpuereod.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtoznrzgxs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtylznmjsw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpioeuktu.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gtkrcerrpa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrknultr.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtithshbdj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gthzoidxer.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtowmjnuhf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtxcdoqlpi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtdvzwofoe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gttexivmqw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtryoatrzo.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqqlxevf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtwuxesvlh.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtgjtfjamw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtejofjzbe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtpfekddgc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtdjfdtjxa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtzpucqpfv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gttawmofav.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtrbffsnbs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtzmpghmkx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gtnieiqsjo.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtczfgzqyc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gtdyxahlfv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtgknxgmsj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtbnstqloo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gteevubtum.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtliwsczcc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtmzdadqnw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtwyrbvajx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtijywtbiw.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtwxxvmapo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtyuiskzzj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gttynwjull.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtvclcxnnf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtlvwwvhvj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuluhyent.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtsboobuda.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtigfqkrnv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gtqasmibhh.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtjrorkimh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gthzkvycvu.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtqadxkjzz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtinjhwdvh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyuvpgjro.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtcqnlhqfd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtpnwzzkws.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtmgsfeyfr.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmxaaffpc.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtmjihewqz.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdcylgode.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtkbmbzmzb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbvqkuhgk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjdkbnnon.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtllfbexcf.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gthvjrzgnq.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbemqhtca.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gthkxpkvyi.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gthswqnlvu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtlnunyvmx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpghclyuh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtgduafkhg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtbshljlom.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtpllsezwx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtoqnwgpxi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfoxdqnb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gtjnvmdzvh.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtkgjdzynl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gtwvqpdryo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtkabknoab.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtukujttcd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtidaqvocd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gthkcdvqis.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtfkeregjq.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gtjiewtodz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtnqhomeik.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtysgzsffm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdjtppoba.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgesxszuf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gthboekdie.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtbubcgkgj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtonjozrpo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtiiyuqyiv.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzmkpagnb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtixdbxrnl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtenticnag.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtyydlaolr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtpeiibsho.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzxvsrcj.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtattdwule.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtqbmtllsv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgoykorul.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtabdlbvnn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gttgevmfli.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtikytzcpa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalxvygls.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtfjjotuyl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtxzqujovu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gttfmciwbe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtnxummzlx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtqnxrcokk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtlmitirkn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtcqosaixz.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtagcdkriz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtfuwgrftt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtpxccmocn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtoscozuyt.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtagonbbon.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtabykadah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtuxvutwqo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtustavwjb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtvggneybu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxidtgudf.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtkyuyneii.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtonkawwxf.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtwtbvxueg.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtkmgttisa.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqglcckl.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtfvtmqpgd.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtkfegraxq.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtcslvlflc.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtdmtsqvoq.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtgaakagcv.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtiqihuelm.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtgrmfnzzn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtydaqftrx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gthbxeccqs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtdtjewsah.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtlubvefkx.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtztayncca.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtblwftqmv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtwgzganfc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gttugnlhgx.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtyuwjmwxm.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtjvzerlxu.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfseehvvw.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtzcylmeih.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtiewgaemx.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtkesjmkzf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtxmwrlowd.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtxqllhppx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtyyoaatik.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtqkmqnptn.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtfxlmutqk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtgvtjeuog.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtmovdcgjl.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxchjuefu.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtkwesfkoz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtfqggiyux.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvmrhyiq.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtgebkxpgi.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtgsctlyie.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtqduchkvy.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtvxpmoxia.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtqhbtxiqc.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gthqmwwgbh.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpofwjqcg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtanxxnrri.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtvevmsjmc.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtabzrpsso.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtgqqqytac.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtmyjxoazn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtqebvmsyp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtptgxgemw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtrqszolqs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtsyagnmid.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtapdpbcsh.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtdgyhlsfm.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtdpovnawq.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gturwljoja.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtajbecyap.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtvvlezoge.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtobxbunir.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gthfqheybf.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gthvycyxvk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtkihrayvk.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtbewvdlfa.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtrtzafcgg.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtunwgqpdi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtxldvcygw.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtfsafidum.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtfurzgczm.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtygbkjsou.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtzauhrdhm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtnopobwot.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gtohugqapu.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtlqgpgyyt.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtxjknvhoa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopfscnzg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtxvvqhhhw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtwvaznieg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtwhcrrbru.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmsxqzzat.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwmwrhmx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfzpefcd.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtstuiuyti.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gttanestky.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtallaxbtu.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtaefotfvf.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtvcccfeaa.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtspzxjvhq.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtbjeohxdf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gtzvntbjrk.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gttklaugkm.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtrpccxdii.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtnoqixhob.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtnyxhixay.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtebdzyxzf.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gttijjnjft.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuzevwpq.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtwftirzmr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtufywkarx.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtecbmbozj.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmtougqk.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtvdjdiwkc.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtiqxzmckd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrykcmde.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpbxxrqu.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtvlrcympp.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtkelnwgvl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtxxlljggy.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gttmniuxdy.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtlrksohes.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtlwrmwreb.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtizcgwmcl.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtmqlvjnea.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtaowrsikz.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtyrnhkxqj.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtvoftmdqd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtqohpnvug.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtveuyzivf.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtdmmsficb.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtbcakpvxo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtafoqipgw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtlehmnbgs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gtrtglgdej.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtikoaqiqx.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtlzicwouo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtqdsylfao.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtlrpoobym.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtevxswtzv.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtphxnjhho.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtmrnrgwkv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtrkgtsjic.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtvyonxwws.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtqzaqltbd.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtnbtazrgb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtfpwunhgw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtorvrhgge.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqafppcf.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtslporylm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtfkuhpxtw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtptkopqkl.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtllttukwm.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfpppxoej.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtadsizszl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtgfxcfrqu.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gthdxrcdqd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtmajqmihc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgjihlnbq.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtgcaypfki.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfhmbjhny.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtoosdzkpd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtpkdffywy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtrwzshdyj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtcshyobda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtbdrttguu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtemyjpxiv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtzdmfygly.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtzabnkafw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtkqvwskuj.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtgcehtrxd.html


<!-- 参考信息 -->