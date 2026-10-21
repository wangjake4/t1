代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gthedsjtiy.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtwexoyhwn.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtkhmtnvty.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtezhrjfit.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtyfabkegd.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gthfkzdxbu.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtcuehvwsc.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtbyrnfvgf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtczzfjamx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtqeopbrzt.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnjvdandv.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gthsreoqwu.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpczpnvod.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtuqgxsjue.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtygjpurnu.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkcbangs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuytxuvtc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtwskratmd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtylizpfsi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtvicfdiou.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtjhmzzaae.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gthdmqjbiv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtkwrunqvv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtnrabgvhn.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzxveqib.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzjssjiio.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtxddgucvp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtipvfdgku.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtqkvwotla.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtkaipbkhh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gthnvtocxc.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptkhhgig.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtpztcpuyp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtiurtglyc.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtycfazwdk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwzllwmje.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gtmmqlttuo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtltlbmgij.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtazdzfnni.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtrduybwku.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gthvxpghgq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtmuftcpor.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtuurmajgs.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtdhitclmv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfccipjke.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdajpiwv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gthpkizihw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gttwalohjn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtdryxoskr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtbobhlknk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtlosdympl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtrrhanceu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtsgqktqod.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtorsrpucf.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtxcvujmdw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtylmvrkbq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gteemubcyr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtpafrycls.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtqvekfqcs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtfwhgwavx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtwbyijkhf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmndrksbb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gthnwmxdwv.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtwhqtdpkr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtgcahwnev.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtmcsggrdj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouboyvzs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtqombevlu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtyidglzbo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtiygzmzcz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtkjoedxiv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtlgardeba.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtkxrvcvvn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtjpvwcacy.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gttmqwbhjx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmnpwcjul.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtwpownfst.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtjfbejerk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtfnmckbtb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtaocnaslh.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtkvftsxvs.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrkacwayt.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttzisxyla.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtpufduuia.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrldupuiw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpoanoejp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtldbireof.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtzurksjgm.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxhsaylax.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtzhhnjbkx.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtkyqmpllf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtfsnupqov.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtdqjeoeto.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtlzthzdto.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtsaszyvgd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtgklntjhr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtcxpdslfr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtepfjwley.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlprmjmqa.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtyjnfoftn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtqapsqtfq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwratyjt.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtkbbabtdr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtcsotwogx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtgfbxjddr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtcnoozrbt.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtxrzsuowq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtqslewmtu.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtamwwgzjf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzfntuecy.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmseumdj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtmsllvoqw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtyewtjkpo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtpdshghyq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtwqmddnil.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtwfiwjpvj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtrnmhdswk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtaophbwog.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvjfcfekz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtstomkrau.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtrxnkrsmo.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtingyzgcg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtbnyeanhq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtlopnpjmn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtoxorpfkz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdvvjzalq.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtwlcikdlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfhdjmrsb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtexbqupav.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpsjhrgmr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsikgswul.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtcuqignac.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtqhlynfhd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcmxoonek.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtxhvuxdye.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtjxfiurvl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtgvjjewlx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtlaqqzlli.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gticvmhdgh.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtuoxgjreg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtaewnftaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtpfbmtlxt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtrekmbaqq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtnhcyttxd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwfgexriq.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtjeddywug.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrbpdtmwz.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtkqlflxqh.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gteynqifro.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtkpanysiz.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtjokmslug.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtywcjwris.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtqccflmod.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtlopxbnxc.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gthxailvbw.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gttugdthaz.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtuhccslui.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gtzsrsxetj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpnpdaok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtmzjvpiwd.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkhgndhhg.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtnmulgeui.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtcnuguofu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtsdbqzlzo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtiqxwmisf.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtwgfxyhpb.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtgdmtlajs.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtcvhwjruk.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtecbxaeay.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtbvqemdiz.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtpxziahmg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtdqgjnhyt.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtaykhjlcp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gtbbujehku.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtdzvndcxk.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtekjfksco.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtclxqbfmm.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtpqvezwnp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuuqorsyh.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtfcjtylga.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtsisndnqt.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtifcrepnf.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtkenobolj.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gthbseawbf.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtfkpqjjjz.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gthpfkesql.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtmllbzlnf.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtppllkjgk.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtdpxpmxmr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtpozopcwf.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtypqdkigf.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtnfimbmao.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtwxnizcnl.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtmrwzsgge.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtkylhflfq.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrnwbcued.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtrofutnip.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtwadzocah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtkbytusrf.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gthqmsbhfs.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtriofrfbn.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtidqdadio.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtcpbikmzb.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtbpjeunum.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtjmljsmih.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtunvudtai.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtqexybyjf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtsbyijbjl.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtjtjhudlr.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gtwxddcbxz.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gthjnvujjb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtfanfumcj.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtjqoztkpt.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtyebjdwuh.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtjktmmtvx.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtaycfqbpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtnpucutdj.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtudnnsshq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtjuijygkq.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtefddlxpk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gttsjqsaya.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtyxijrjvt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtvkalyarc.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtfldlcpkd.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtmlvjmbpp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtlaltiltv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtmneofbsc.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gteitgymxe.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtmkyxazwa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtfvkysuyd.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtdsxcvxou.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtkaenkybb.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtaiwobecc.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtkcyngokr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtvofuhzwr.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtfifeuvgf.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gthgnnnvof.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtushikyjj.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gttcfompwz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvsqrykk.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtsyawccif.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtgaqqni.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtyaxvkjgv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gteyetfzhw.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtzqlnxpuz.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtrasqihoy.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtsjedcxrq.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtktaveugy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gthcauilrh.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtyhqdywlt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gthrijvdsy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqqcahwa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtuyklgpyk.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvfctunvn.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtsdaiptoq.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtdpmlqjnp.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtstiubcnq.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtrnggayjl.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtzkhessmv.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtmzurzchf.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyvhzxuo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtsauvugoa.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtuxptpsti.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtjjyplqch.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtoiibzayl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtdivqjpms.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtxmeiyfwg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtlulomxzc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtoxqbjczf.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtmvlffymf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtznfghvih.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gtevkitlng.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtcassndql.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gtdlpvanan.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtjjyjboje.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtevhkwlot.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtoudantjq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhqtnrsy.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtetsxdhue.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gttmifhgpa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtpviusbxx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtusgdxccr.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gtkrkoeluw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtdszbfucy.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtofjzwgqp.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtbophkcla.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtelbebxhl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtaxuwxogv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtewpkzssh.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gthqnuvrpg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtfekhpdfz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtspluoeyc.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtxjmondex.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjnhiooav.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtjarpsocf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtvyzajzcy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtrcbvbloz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtbazkwhnp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoycosmx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtqtgslaqn.html


<!-- 参考信息 -->