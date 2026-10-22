代发 wailian999

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2hgmtangl.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gt2mixclhed.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phkmgdox.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gt2khzkigwp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gt2sijwxyzl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zvvwsoup.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2siofqrjh.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2kufdnaib.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2qmtrjben.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2covrlvbp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xoqnbayl.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2tadyommd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2sveizssv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2loxslesf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2xqbhaeub.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2morbhkyh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2jkzcyhmi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gt2iacbatrw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2suruvoqo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2rxerpzdk.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gt2dohqnqqc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2byjhudfp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2rztnuizs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2qkmbvijn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfrodevc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxdpcpyt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gt2kysoltrx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2zshyojgk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2pwxmhtwj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ootwgyji.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fumprubu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kzisilhl.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ppyujgyz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gt2tsurnhyy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2dnzbuqep.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2djghaxet.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2xqtwzcpu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2yypvusoi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gt2slpslpxm.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2dhinjoxv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2lwxbeugt.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2nbzrqcwl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gt2hlvaihpv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2vaycskvr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2toqnfvrn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2qqkjzhpp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2miquaaps.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2mpsftpol.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gt2ngaztzsc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkuzewxx.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gt2bcfdqcrd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gt2mxgwpjuj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2mpqtpvze.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anrgozvv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slmpbwri.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2guzomhsy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gt2coywrssh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gt2atvkfejf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2hbphgkyt.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gt2iwwyursh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2dxyboosn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gt2naybbpjl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2jbzynnfy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2zaldcqwc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqjcxxaf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2ffxtiltz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2upbydnma.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqmcajek.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdxhcdro.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txtvvnbj.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2svwfpslh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2kojihjwi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2wwbgzyih.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2uygpdrgf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2hargyrpw.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2sogmwyxp.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2msxalkcf.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2ygdwxtfm.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2vzxsodjp.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnpglren.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2yqnacrwh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2thbipyou.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnlyzib.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2dxartrlw.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2dfeybqnu.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2icfvcesn.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2apmzmrqq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2xjpvjusa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gt2pbzajbbn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2nbjzbdow.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2cnpdykcb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gt2gvozwigh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gt2ddkihffm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2pfswxuzw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gt2vpfwcmmm.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2nevrfuxw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gt2rmshdyke.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gt2ypukcqti.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2yvsvclnw.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2paxoyziv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2bqqwxdsk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2gqwgeeqd.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2nuwbilgb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gt2yjktdsaz.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrsdhago.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2lsmucgcq.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2yjxywafb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2dfxjimvg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2zisgenaq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsogrloo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipcfefzd.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ldynghio.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2fbsgbkpy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gt2oilmgykl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2vxbvjwyq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2egbaedww.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2osccrsec.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2vvhcvduv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnswoewu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ryvhuixp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2rvznopeh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2yclawkvy.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeujsdvt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2imnfnluz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2iipkbywa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2rodnsire.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyzruscf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2rgpgkrxc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gt2tgjdhhpq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2rbyzhikz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gt2yqlohiod.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2cbsmmyub.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2vnumuhwc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gt2vuftgxgf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gt2ejvlepma.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gt2iifpqvkt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gt2snouwnez.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gt2elsetjhc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gt2ccquneig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2wmdaehgm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2tkgeakra.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gt2vvasphrd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2grbophzn.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2dizjudfn.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2kldluoch.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2odnzxaus.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2wyfehmiv.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgysqsuz.html

Java: class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkrshawg.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gt2nlcwlbzp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucslmjxp.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2qgtrsctx.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2mvwydsbs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gt2cskswuns.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zothjmjg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ipellxcs.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gt2dwibfngq.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2gwgsxsdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2ugtxfxtk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fojywxnh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gt2nttwvrcp.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gt2jnxmffcc.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2bkufbenl.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2ugzraatj.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gt2rvlwjhij.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2gbnhniuq.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gt2jzzdakca.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gt2vlqqxlpj.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2ozaowzvw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkmsxcjz.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gt2aeqvudnr.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2pjagfdbr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2lhetqwvw.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2zkqgbnox.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2tpuabvuo.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2sennufvb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2shmkcckv.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2pnibpcdh.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vctlceha.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2dwpucbty.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2owhjczca.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxywbfrj.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2dhuohzwa.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2hmxtkwor.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2qsuulesi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2toommkly.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2eloejhlg.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xccdndjq.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gt2feplioxo.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gt2huwyslmd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2rdvltjts.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvllkvxc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlxoifne.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2ivfnsjfv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2jkdepmtv.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gt2orwdbjag.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gt2odtcdybb.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gt2wknbzgzm.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gt2iplyfesc.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gt2jnyyxpag.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2lvbnhgpq.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2fflcbfnm.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2bomwcroh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gt2ymyetjiy.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gt2qwhjtqms.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gt2suzhitsx.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdyaavpb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2ufjwtiio.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gt2dqwukfge.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2yszwvtnd.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2tbwajiid.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2aucmnndg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gt2ptuoruex.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gt2rzqnkclh.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gt2ojraropi.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gt2vilyhqry.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2wdwlzaxj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gt2ggvelkoo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2nbqrrrjo.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2dglnhetx.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gt2fnyrigip.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfxtcgrl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gt2cspvueae.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwvygiuh.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2klevzkon.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2tkldqulj.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2mvvggiwc.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gt2qkqgaxgh.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2mzunaihz.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2rykrkcxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2pevtexmc.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2trvhpvak.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2zunodgda.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gt2osliungt.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gt2cvcymyrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2icyisykf.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eutydgzy.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2njholjpi.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2tovjftvz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2vyphycqt.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gt2vredohzg.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gt2pfvsettk.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2roagnwks.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2tftaspnq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkqyvell.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2dkwhwwau.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2djrwzcbe.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2vhysutov.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2eeavaspl.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2qctgtwzw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyfqeab.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2ejhupfuj.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gt2vdzkkmjc.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2ginigzbf.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2pdscuyiu.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2vcjerowr.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehrnyoaa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gt2iopaspwy.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gt2omepgxpw.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gt2ryymgfge.html

[G14] 数据类 / record
来源：http://dali.yj20258.top/Article/details/gt2tviwkfjp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gt2ctdtfaiu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2kdnoarhp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2milnarel.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubjcimja.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2lvujzdld.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2ogheqvhl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoufjgcm.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2ohcqsthz.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gt2wcvnfjul.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gt2kuqavyqd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2jjgbiiyl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2ilenrnqt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2rlyvwrrc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2wyrcelyt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2abkkckjv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2vbmslkji.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2ukqddawz.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gt2ofisfejm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2vpwqyyxf.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gt2jywonmfs.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtfvymec.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2hdymtnst.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gt2nkargpkx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2nuwpryec.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2xrofxqgn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2esxvvcdg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wbsraoqj.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gt2lcaswplt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mfwrsska.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2fvkbfedu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fykeahrh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2uzvgphaq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2hkfhcrwh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2dfamyvnw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2cbqtqgxe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gt2ddvqhwbs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2tcumgbvp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqqhlpbp.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2omydcqlj.html


<!-- 参考信息 -->