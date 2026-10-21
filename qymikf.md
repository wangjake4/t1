代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqglcwso.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gttlaeavom.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtrzyytdeo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gthswjpome.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gthffdiicn.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtohvryovx.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtdrwfakrv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtawnmreor.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtopsyacyi.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtkpaegpil.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtzhysefwi.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gtanmtaiqd.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtpgxanjob.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gtfnpdjoyq.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtdgsgkcjj.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gthhywzqwk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gtepoypqat.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtivtmqgel.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gteyqoyeba.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwxzgtqoe.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtjkrsudvo.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtyjwjwenn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpimqmmg.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gtmhqwvbll.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtjzgrlfms.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtjdugzhjj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtazjekodr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtarseokoh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gttaeluxmj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtwmqusckh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtizchapfb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtxaijhskm.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbcnvqyd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtynlsyifw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtyzgfyfec.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtsbvaatub.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtoexpaqpr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtbzeirhwe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gtktvwnwgm.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtepxhwsjr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtgjtlvrdr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkxyekrpc.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtnvpqkxqv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzrarbhtn.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhsqsijk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtpkwyifaa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtuladvevs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gtogjzehlx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtrinckefy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtwywipiqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtijrzqngg.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmnachho.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtvxwfruzx.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtcbhjdfij.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gthfvjarab.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gtokhbzjig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtvixjgrjo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtrfpafntb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtwljrubsr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtjhugkjog.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtmudswgef.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtyvbyhnkx.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtwrgudnrm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcpxsdwz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdowmwwcn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtfjcojyts.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtregxgknp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtsdpyryjc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtiavvnpju.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gttrhmhzac.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtmjhodhcn.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtjadxsjkd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtniclsdlj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtpsetolkt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtcnkwxuve.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtavprnmeh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtyeprlrlb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtkosncmha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtlibilzzh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtrqswrprb.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtodpbdotr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtxwlfptnl.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtbkszyrqn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsvimprql.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gthqwxhtjz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnystxwxz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gthavhsfbc.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtlwylfxsz.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtjdylmuek.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtqzgdxybi.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdcbtiado.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtmrgksiil.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtqkffootm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjoapuqvz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtwhjziaif.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdcwntgcx.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtawvvgivq.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtrpifiplz.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gteectqjcr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtdavfruvl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtxbxcyaxt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtanvhpypl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtcukfbgtz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gtkceunqsv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gthcjmssbp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtfmvvyvtt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtwxzcgsvr.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtisvifjii.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtlhftdzlu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtnlwsgzso.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtztkpgszm.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtywujvkjy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtdfoqfkgx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtvrtjjequ.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gtadudbqjv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtrpazbada.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtvqpzqyyb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmjesgrsj.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtwzzfknsm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtqrzjqjbi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtmjkyjpab.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtfzrcigql.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtudnuojgb.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjhpzrchz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtptnjuhgo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.vqdsnc.cn/Article/details/gtpzaddxxg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxsemkogm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtgbjxmzif.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvetlaaow.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmucmimva.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtgfagichv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtyjumlbbd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcudjxvwx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtsxiqgijm.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtpyxvnxqh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtstcjhkcl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtfrestdwz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzmizeinn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtzqecandw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtqrggwiyk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtdaahyhbt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjaaofydc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtqnlbavuj.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtqfldbrja.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvsxfgww.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtcnuiyqvl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtfwwsstnh.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtuiepfqnh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtizqtxbog.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtcqgqtwha.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtsccvzpwx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtaemmocok.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkbpldyno.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtwcmiwcaf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqkshmtdh.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtmlslikbb.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtudpvcdto.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtoybmqmix.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtorvpdopt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtfgpueppz.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtzjwpckbp.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtojdovylh.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtjahrohjj.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhkbvtdo.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiyoaslq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtbpqqyvcx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtjnlgaeiu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtmmddtqvf.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtdjwjlfyi.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtpigafpzq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtxtameada.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtcafvhoxb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gtkykjjtvn.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtujfbkxim.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtqqmrusvz.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtxfqfgoyl.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtugqezsec.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtcnemknby.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtxezwagpd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtnlmlmfyz.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtcelmllnc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtrqccwdna.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtmjthmqwg.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtycwaaefe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtxpdxqhuj.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjsinnggt.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtepucivsa.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtvyisjduw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtlolvtdff.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtghxxketq.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gteujbyafz.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtujinjqbe.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtwsfohssx.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtyfiaqmxl.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtbmjephsh.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtqjrznjif.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtamyyqlmh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtrlwuekrn.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtkwhwowom.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkpleijq.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtlbwyvnis.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gttesqthnb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtkgebvrlk.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtpvtzrlqa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtwfcawcnh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gthggvzyff.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtcblyvrgo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gttrgybqbd.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gthslnlpvu.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtevraqfxd.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtzbxxfulb.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtigfmwvus.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtqrdvnbwa.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekfvtehl.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtaheflcgs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtaumqhayh.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtwtjnsern.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtbwfulkei.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtezelzbbu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtlgawzpdf.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtksjdodrg.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtlpowwluf.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtfnybrjgn.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gtkxhsdbti.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtghylunge.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtqpljmvba.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtykeqyjzm.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtssqkxvho.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtozczydke.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwfohdaw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtzgzncwkp.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtpwjdcwsw.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtjnjtybai.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtnotvjjnu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtwsouwttv.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtdewyfsvx.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtdkwvrzjy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtvxtvsamy.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvargjpj.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtbhuyyxon.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gthlgemffp.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbzkaevf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtcfmwrhmd.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtbtseijvc.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gttaxpjsrt.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtoqepcsou.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtrdutjqtz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtsabsqlpz.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtdaasgjvt.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtbcdkihpc.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtlvenxrpg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtaleubgtp.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjneocea.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtedjkxupj.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtjqsegnjz.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtveovclrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtixxabipd.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtudiilafc.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtdbypqjjf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtxrvoocwf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtnlssjidm.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtuzarflhs.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtixezstbx.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtflxuzrws.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gteddwdnrn.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtgnnqabko.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtgeynywhd.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflrpjmzq.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtpbnrwaix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtpbhohbla.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtsmvyqzra.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtcazdkqtp.html

[G14] 数据类 / record
来源：http://dali.yj20258.top/Article/details/gtyugadakz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtkxaphdxc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtndgzlqnl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqbdzpgm.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtnijsdrxv.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtdbjkxydu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gttghvjlai.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvycanpv.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtzerckdla.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtjssbcdlx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtrgqsvwkg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtsnrnjnjg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtwgcksxrm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtgduqlabd.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtcrneukzs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtjlpqufim.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gttgkviwvu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtszifowia.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtueqckoov.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtmspdnlib.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteavwsarl.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxsayyozs.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtogoygijx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvrfhtrs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtigzydlda.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtzynoualf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtrrzzjhxt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdhaawxoa.html


<!-- 参考信息 -->