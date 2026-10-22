代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gt2wmhxaary.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2kebpipth.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2noztwmgv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2wgtvsrzy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2pftdbvyo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gt2qyrjjnuq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2yzvbhgce.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqdyfzvh.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2iyrtmtrd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enhjhjra.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfxusljs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2knllfahy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2ffgtqkox.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2eyruofwh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gt2bagrjewe.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2ltbguwre.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2zjcobhlx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uexestep.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2viaiqxfc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2eyxhtjxq.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2drwoqlgv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gt2dzwggkbd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2xbhaeqyc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gt2hofeqcyr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2ooqvdsla.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2pfjazozh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gt2pdscabbu.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ytngxqwc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2yyhkinkf.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gt2ooaevnxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2uwopgpbm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2tpcamgtz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2juruzdbp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2jihmmgso.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwabkeak.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2grbkxnne.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gt2bfvsqnjo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gt2hwbaluji.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2dmhervqa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2fstcqhzl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2bjwukswv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2lmjluqmj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2tzsmteqj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2kcikehux.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gt2nxnnetmf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2rtkiegcx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2iouwjqur.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gt2htxmrabl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmwguecp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2xpnmcnwb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2festwaqp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2djmcbffy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2xjmvloyj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2jdbbtnub.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gt2xviqyghr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyslzgzd.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzahxfew.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gt2wuaohmea.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2yrkwsefj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ddchgqhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2gawrpopn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2rzhmxguv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2xvtlrxzr.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2pfwxdmgc.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2naysuokr.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gt2hcpbanzv.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2doroojbd.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ypvwqcdg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2uqoeqmzo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbavqyrq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2vzsgijgy.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2syrqymnh.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2hydzkuat.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ahfurlto.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2ivodyavs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2ntklykcq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khkvacoy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2kkredemz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2ysylkkpv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gt2dxeotnpx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thazqjsv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2ccgsedte.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2dnllospm.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2ckqdqjcu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vicbgmkd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gt2vtnvozfo.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2brhcearu.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2faifsnfr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2tvtekdsd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gt2jiuljejw.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gt2frmqeucz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gt2hciqyekx.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gt2hjekxwpd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2lttfhbzv.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2wfhdfufg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2xnlzxyxi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2xmvcpqyi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2ayjbvpgc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gt2lwqafowh.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpmrqdqq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2dptkfnbg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gt2plsndazw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vymoxvse.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ftntibfm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2lmeugrgs.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ilkexcez.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzhbdmof.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2hgsugtom.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2hvuxgfji.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2mzerdqbm.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gt2igkstutd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2khabkkln.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2wjqcctlc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2devqbycd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2uvckgram.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2qsfgrwdx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2zslipfvu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jotsaxph.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzzxdvqc.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gt2fgzkrpym.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gt2vsddhkmk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2oipjdwuq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2kfmtcobw.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2vomltxgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2kwxeaxqq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gt2ubrvmdwc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gt2scdyxycm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gt2mgtffzzm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2cxqqinwk.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gt2usfzdncm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2aomigmso.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gt2ynyrvfjh.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2rnveloyi.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gt2whbspuny.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2tcggqcio.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gt2xxgbvwvk.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsotolch.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2rfrefrcz.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gt2bvhptzly.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2eaebnnuf.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2devaybxt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2gskixqne.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihnljtyi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2ebfqdpdy.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjvmwjch.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fauzsagb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gt2euwbykvb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2shatsjbo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2aydgwwko.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2wbxzplzi.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gt2amkbwwsg.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gt2pfkzwdff.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2rwntxhpa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfotnscm.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2numwgpny.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gt2iorguokf.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2sggvfsso.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2buybcyss.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bferwrdx.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2oeyrusqi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2ekhhdgsz.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zzqdrzzi.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2hxdyzrgi.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2luinzvji.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2fnqcfiea.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2wqvxcffk.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2hwumyhjj.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2vaehfkwt.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2uesxorxm.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2bzypnchp.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2upsbrtjp.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxmypfzn.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2youzvzmx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gt2keeutpxd.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gt2jhmlpdxm.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2mhjxzayr.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2zdzoktul.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gt2lnesujwq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2enpphrqm.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iigwkfwi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmyjpetx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2dbffxpwo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2jivujxzi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2kdgpzkxb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2hdtypyvv.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2uqnygsem.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gt2hjaraqax.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cponzgiz.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2rovtjtea.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2kpbveawq.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2swnjrkpw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2sikfkzim.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gt2pfqylxyp.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2ybvmhqrp.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2zmndqkwh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gt2evymjqot.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gt2eogdtkfk.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2otuaerao.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2rslbnmxu.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gt2guecjbje.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gt2qmjqknhf.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2funrpcuw.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2jwyzvviw.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gt2dlqnzxlj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gt2dobtnwlv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gt2edypmsid.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeecowdw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gt2aprakywp.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gt2lxmntlzy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2yjhtiekz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gt2cpnbgdnc.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ydfwlkqi.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gt2nvgcgzif.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2zylonxdd.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2ngikpobq.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2dirjelix.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2ptoyulss.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2icmdqbng.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gt2aacrgluy.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2fpunbyjw.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gt2ahbdjgef.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uftyyvdf.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2tmrzgkag.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2axbdrwij.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcjxbysx.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2czjyxjai.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2jbkmzdoz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2pzqrgqfj.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2hkpiihfo.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gt2bbekmoak.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owsqhlof.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2hslvhmjt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2uyysliog.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txinmmgc.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2mtirolsc.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uijdtbbo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2igpxlteb.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2dtqduhvv.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2fwwzkjkb.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2gbuctfrv.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2jwkqkzes.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2sllqrvec.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2ifvgrgsg.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2dpszaqhn.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2qowrarqf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2ntngyswd.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2sulcfkci.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gt2jdlurkhm.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2rlxwmbhx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gt2docuxgss.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2goalbpxv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2zpowowkq.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2mtaieafa.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2rxhjysif.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crlvqpiw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2edatoavs.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvvlxvgz.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gt2dcsxprih.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2kulkoevz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gt2xumxshdl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gt2ydydfmsa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2fnznwdki.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2rawuxiev.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gt2djflbzys.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2igxordwx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2rtvwhmlh.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2ojlbbzaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2ositjnzo.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2eefepcwc.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2bztmhgqk.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhwqffdf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gt2wprecqbp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gt2fcftixxi.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gt2cenaxnke.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkjesaff.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvokusew.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2unlgdnbq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vmolqoyn.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2xjeingew.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhykgegm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zbmgfqgw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2odcgowym.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2dgbfbauv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gt2bxxpqvor.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2jsufsnvm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2bwteuhcc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2lvkkdukt.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gt2afnhacxp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2tofaiuak.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2qrvvolci.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2iousqubq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2mqxnskyb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsncwftg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gt2zonwflbt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2bqkugpdp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2gextwrho.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2ncinxrnh.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2asnshlfn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2cnmtrluw.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2wmfqmtmo.html


<!-- 参考信息 -->