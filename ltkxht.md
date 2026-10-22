代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gt2odpydnfa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gt2tvfmgqic.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2elfkufqf.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2hvfeurjh.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emuccgdy.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gt2dyvxmaaw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2khesxtyd.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2cakzhlhd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gt2uclykbvl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2mvwgahov.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2edsgapzo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2jdbkhjlb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2mofkfxwk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gt2abtnoqvu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2dktbhnig.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2dtucycja.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gt2xvzrkorc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qckdiyyt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2lnaoqfel.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2pggdeemh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2uidapnft.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gt2fymzqudt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2kxzsbemf.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2lzrqibei.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2vjqbraqw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gfkpzzsh.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gt2jbqudomv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hqpyxvju.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gt2aazpockn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gt2lzokyloo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2vqwfwcrl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gt2rshdgava.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2rsxgwzbx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2tveqbntx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2cgxavxzz.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2vgolcksz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2tefwyhxi.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gt2rheadvqa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gt2bskkszio.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2scxiksua.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2idbditrk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2dmjaqwjd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2nhjfpbiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2hapxhfrj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqxjprtc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgyhhliq.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2nykblpwd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gt2mkitlasg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2rxurkbhq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2gfqjyair.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2viysxjpn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2hdrqhrks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2mhexomns.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2ejibstie.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2cnzklwui.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gt2nlqariij.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2erddlutk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2itxaoorf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2abjkixnq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2neqstprn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2oigxgwhf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2fydmypar.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rokitgtf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2fhhjltfv.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2ixkdprty.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gt2tbovpied.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2tdxvxrbb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2vcbwxucj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2wlmatuot.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2yiuejcpo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idsmtsnj.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2bwxnbkux.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2veiczuyh.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgqtgqqj.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2oriwcdft.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2lnvewnqn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ejedpwre.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2fajddzyf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2irgmcohr.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2cemssnbt.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fggzvbpx.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2iiwrkxiw.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gt2wwmtwnat.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2xucxwxdy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gt2lsqobvyu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2mizvmygn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2nfeqkgof.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gt2hwpyakar.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gt2lnjcdqug.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2hbsdetbb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gt2zoehszdf.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gt2opauvjws.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2yctqsifd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gt2rfbgvpmr.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2bmsbtsvt.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2vwfnhksq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bikyqxwi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gt2dwjadnso.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2ijaaujld.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gt2cuavhcrq.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnzlpoyk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2uwpefgve.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2suopkddp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2hlxelbxf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2vrqkgaey.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2clpdtybq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gt2dkayplbx.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2lvlfibuz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2tvgxkjju.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gt2bnjdlzmb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ehqxeydn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2fhmqkewb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ckahzqjm.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2gxmywymj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gt2hzuntuoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2pfmahbdg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ntmrfvlc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2zkmvkmdj.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gt2xxwvrbld.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2xgexqsvv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2xtzzfefa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2pgikgqnd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2aruoubad.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2rjnxvurk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2dcdksyzz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2jiqvbbki.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gt2hwdjmhqu.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gt2heognftf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gt2owbmmifc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smoncdaj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2atpsnfjb.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2njxymenz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gt2wvkntdiu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2pviqfosm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gt2fwtsfjrq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gt2zywyczza.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2joveuywm.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gt2lbwfaxnp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2pltrnzwp.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbdjyoiz.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2pgrpieaa.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cagqthuj.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2krjldxcm.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gt2zdxvfcgj.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2iwthiwvq.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbkvtbka.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2itgkkkrt.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gt2kgeaajcc.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ndcodgax.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2sfoufsgo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwjrxjvx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2omvcwhsn.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwvnwgzw.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2odkvlqwm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gt2qyanvsex.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2njqizoeh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2zoqyiiim.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2dtosjetq.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gt2igzxkmhw.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzlchudj.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2viipusgg.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2airbzawg.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gt2nidmascd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2zoaalkps.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gt2sxybxoxm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvtucbgj.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2fofykygi.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2fqzspedm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2itfmcprx.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2czcpzxod.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2abhboixf.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2gjrdswdl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2wkeblzxn.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2rfitjkzw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvgbtav.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gt2bvijwbhx.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mohypdis.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2wtfqeeec.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2xdhqnetl.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2qphtabvn.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2exyruymw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2tovfkart.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2nfbaxckv.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gt2pwftvmdn.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkrhlfsz.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gt2ptgqagmo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2dgqoztvm.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2brndwamj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2sawaelws.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyrdthrr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2mqcnzzsw.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2jhyrqjqm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2uofvxyyx.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gt2fymnebag.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kystkcts.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gt2laweklsz.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2zgmybfhb.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2twqceqvd.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2faosuiml.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2pmrnhnqm.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gt2bxizgcji.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzfpctju.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkbsujll.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2cvnjehwv.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2bprqbqkv.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2ftlfwjga.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2xvwedkqq.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2uqbwthlr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2ewqgwyxa.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2cjpzpldt.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gt2yuuxwjsv.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gt2kbjbrunm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gt2gmufifcy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2aomdltlo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gt2scxudqlx.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2eemmtssx.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2uijefbmg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gt2zmzioixd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2abwqooah.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gt2lqllwbzk.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2mcjizdzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdgqkqqs.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2eiqibctg.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gt2ffawswov.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2boqqkfoi.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2uaqrpjod.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2flfmzbuy.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2hndyyimt.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gt2iwyakgua.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2gllfwthy.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2jegfzdhu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2mkngimyf.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkkfrtfu.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrqvirak.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ietergxs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmesjzhi.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gt2fotxdrui.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gt2hfzkqdgs.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdfftfyn.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2qlwyrjkl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2zndikyoa.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2mcggbhxk.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxopuoxp.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2jmgrykxe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafakaaf.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2jojdgtdn.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gt2mvoblirw.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gt2gydcsqhh.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gt2uolbetlj.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2seajhzel.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2agvtfujm.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2dpgyipli.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbicwsok.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2fssadvmu.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gt2uxwnruje.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gt2ikjdxxsn.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gt2orbtzhil.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnfjujrc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2sfhhcmtj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gt2bcnppwcc.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gt2xrzmlusd.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gt2iviywrgp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2puzfzjmn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gt2uzatedha.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2pcvyryjy.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2fgsgmjkk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2ruampjzy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gt2yopqrgwg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2lnhxtuzr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2mgyaxhyj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzsvvqjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2fwdzifvn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2cnskbmhx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2vjfgsxml.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtyfdivr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2ckdnogaq.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gt2mwhrjeei.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2hfxvdidz.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2wtlxmppg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gt2pmnvjxqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gt2svezmdyl.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvfxxzbx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2uiybbbdy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2augfffig.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2xhmxutnf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cjjchdkc.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gt2okzlshzl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2gqtpysux.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2shaabtxn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2wrvejgmk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mppmolmc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2zijludsd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2xrjjifwl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gt2mhssjamw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gt2iihkciat.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2tybqkwoc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2rbpbzrse.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2oyedkqrt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2iseiinyz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2lvqbvnio.html


<!-- 参考信息 -->