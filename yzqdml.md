代发 wailian999

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gthjmvynjb.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtemhzdhup.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gtjzhcgpxh.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gthkppoype.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtmfzlhebp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gtkwkbubjc.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtpdrekklh.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gthjyaswlu.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gttpmyqksk.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtdkkfktli.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtwowovuue.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtdmndljhg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzzzbhqf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtrwchgdhv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtwsrlqpss.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtnwbikgnq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtqwucvkco.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtnanvgpcu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gttkrgghxm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtpjlxjiyj.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gtkozhbbph.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtnlnigdav.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtfziyqujt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gttnrbxbxq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gttpnnxcox.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtplgjukjj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gtlcjnrnre.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtpuazzlan.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtrliiozav.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtajrvwdsf.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtocxtxjjo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsvqwnjkk.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtrkohmesl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtttinnkku.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtqpainncp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtcsmfxyva.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtrfgjfnxt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtkwwpdsob.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfcdkela.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyxjyxhml.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtwckhmkbx.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gttdlaxejd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtjjmmhthl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtuawhdgoy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtavvlrilg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcqeqfxu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtcotolqqz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtbkbctxiv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtfncpfpdr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtjwqxshnh.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtfsdjofmf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtghthadfr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtfliqenpr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumxmdsbf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtyzuzaxmc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtbatnlogm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtfafronpf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtzbwgzdnj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtgbnfvjsi.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtasjaqzyp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gtnpkjmtaz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gttvithmpx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtmgrjegzn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtpimqjkcd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtoctctmvv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtgsvkaufx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gttgdxkyoe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtzauguibu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gthekhqgtx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtikfenaef.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtvzxpnaju.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtbhpmvjea.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtounssnit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtxglnlked.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtuqcpjdvx.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtyskoowqv.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjzomcjea.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtjrkoqtzk.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwtxyxfpi.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtnwvmojjq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtybokvhuz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxhtkgxup.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdgoycrj.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtblfqvsxk.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthhoymlgb.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gthajbgnmg.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtuiuertgi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtjuggexuy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtcpvdawkz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gttzbkhkrb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtptasfjxb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtzzzyyjjx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gthyyiqjzf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtvlrvzstm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtumkgqvqg.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtrzrhqcbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtnmmoorat.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtmmxqjthx.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtayxmyxtm.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtidxtnpsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gttkquazje.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtwgetabbv.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtjcvacmpt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtetkwyjrw.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gthzlyqozj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtcgqpshuj.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtebjhpvnt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gthqyxogov.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtdcinfbds.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtrihshkgp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtfqxqvuyq.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtsfjfkrvr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtttgvkybq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtagfntcvw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlatwzbfq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtkxuodifz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtcqwbocuj.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyimokmwa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtntxidzul.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtodedetcq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtnrrqeksv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthpocwwdg.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtuafmxnfh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzocqibtz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzlyorky.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtzfxkssux.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfcgbarq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtbhtilvyo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmqxtbaz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtccihtdft.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtgeukxxwv.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gttgtenwoz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtuihjtzvt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtrqanzfji.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtsdrafmta.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtmfzljlpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gtzqbpghbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtjvgwqldd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtjiercayy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gthjpiqwea.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzmxbjdxc.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtjkrysqrk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtviibskdy.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtuxfppqvd.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtcbkukbja.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtpmaosfgj.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtjswojiaj.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtrlnallib.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtzsuqcqcr.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtrzdqflwi.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtfltywqgw.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtnpljawfp.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gteicwynbl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtozwfvefn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtnuujoone.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtalrahtmx.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtctwodtfh.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gthjnzozve.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtlzdmnext.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzsaudir.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtkqmikbcp.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtawvxvqec.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtbhkntoli.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtsujcbgoz.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtubjfvhuk.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtzvkivceb.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtdorvsmvh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtfbtqkmht.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtkiczyzau.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtghnpmvxn.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtciaoyizt.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtdfphkhby.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtgmvfwibx.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtowrmgwof.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gttmcxowrb.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtigilsspo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtwkinqtfl.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtsybbmykj.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtnympfufm.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtatnuflez.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstcbdylu.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtylxmimgu.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtyvaeilzw.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtbfykokpu.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtozywpkur.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtoinlapkm.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtomxwijvw.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gtzfkdhwwn.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtqezpolty.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtsmvfyqkp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwhwqlxyq.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtjzhtfsnj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gttsfwdlho.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtvnsvybpy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtihmyshpt.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtsncqvnof.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtvjdkmwln.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtmbyptcol.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtmjslcedj.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtftauxycc.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtrqmbobmo.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtmaslhmkv.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtbpbngrvt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtahqfndok.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtkncqqtka.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtbahvwwqx.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gttiuhavpq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtmedcxaeq.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtdadybpor.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtjaqvcafx.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtlokkcaxe.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtsozefldg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtximeexyu.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtenjitcfr.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtvrjncior.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtjuittimj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gtpztjdpat.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtftjizfxs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gthktfwueu.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtkaxivhom.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtcoeenphf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtsddmrcer.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtpzlundhq.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtxcqqsdwp.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtmqjdomhc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtzqwkegct.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtistaxxyj.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtksiouayr.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtydpymtnh.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gtkxpzmcjb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtokxqldhe.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtpynlkfjp.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtijtdockf.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtwibjlcok.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtczyrphaz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtjnexorey.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtjioldlvf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtxbdxpbku.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtndnfzdfd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtggjtcnii.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtjbhvgxxb.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtslayeorq.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtqytwbrrv.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtrfmrdhad.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhzddskf.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtpqaaudpe.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtthvndhwg.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtqjsackfb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gttbqzeahs.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtohdgtret.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtfinfbond.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtmjfcdffp.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gttordfzei.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gthasswmsp.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtpjyxdkep.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtjneclger.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtjorlafdm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtbiinuyig.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtegtwdgig.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtnjbvurvk.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtvexaiyxb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtnjqeqwgd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtwwxzivhe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtkpazwzwj.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtmhfkhgrp.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtswrivdih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gttytjzczj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtzeawcrkk.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtedbahdhe.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtvwrekwdk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtnfdssbgc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtnkdepngq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gttkxveayb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtmmmwmncl.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtzcvoeyub.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtahumqwml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtblbsiuif.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtglowmlzl.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtlimumnsi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtrhwjipra.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gthgkjcimc.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtphbhtmsk.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gteflhipnj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtfnmdxpfl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtwmibqbfk.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtnymqchhm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtfhbxiick.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxudqpbqg.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtwtniripl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttkehyeet.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhxdookm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfihotbip.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtqphexrhw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtvmuuuoqi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gthdwhvkei.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtyfbfpcmo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtemuxahmp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gthkexfdth.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gticxdagwm.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gteqkbrapg.html


<!-- 参考信息 -->