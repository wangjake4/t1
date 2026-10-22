代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtaxwegvac.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtdvjkwevo.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtdfyxsplx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtowbnqfju.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtirqjpdon.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtvbmqlekj.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtzmlxezdz.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtppzkeawr.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtvhxsfefa.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtralaaavu.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtnpvqgy.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtyjcafptv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtvzqnelom.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtcndaryqs.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtoaezxwdm.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtzgfrfmvq.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gthhmldwok.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtkynxfgia.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtuyjgfngv.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gtpomtbrjq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtnghfiegx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtrizttukr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtgnquispn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtebjpocac.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtezfiovwf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtlfsttiyg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtgvrgmznd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtyrtnkvjw.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtbrytedtp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeynzzgh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtuurzjcst.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtyywfogqb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtzmbvdbhx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtqmstwyal.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtqhpdalrq.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtadtcilsi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtqhtvonip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyommhsjh.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevizgibh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzkcwgknb.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtuzffgjhz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtcbvyhljn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtckosvzsw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gtkdgxfonw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtsmdtmdaa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtrtacmswv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gtcaqorhcc.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvrnlnpy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtxbeiowhz.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtavnmuhqd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gtxjoqcpok.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtodvbmkbn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtyenwqrgz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gthzbrxnfq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtqovedfmp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gtwhpgfyux.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtklkoodpo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtdtohlorp.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtdpalxqvg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtovhdgejr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtpcadmsyd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtizpbnoos.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtddradlem.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gttqswoghq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtawkryoeb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gttkonrnly.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtbtwuivwb.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtnybouskt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtumgdvhrt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtdhrsnofc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtksdwdper.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtvmnkolns.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtzxjxwqqr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtqfdbspng.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtahmbnfsv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtrrbugtco.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gtbhlaojrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtaqygoqfg.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtplzvirdx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gteihtllkh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gthvfjwnkc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gttzzszqlb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtifejahjo.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzrcggwtq.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtqxcetasn.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtcmttjlwk.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfjksjqrf.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtgkmvoavg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvdjpygcr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtchodbrqv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtzbasozrn.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtnxakjlge.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtegevgcuf.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtmaeizfea.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gtvatewzka.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtbfslsuqo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuekxrhd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtmeomgtlu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtonosforh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtpwmaqydk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtojlqwnts.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtvuqxkqyg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtakssseth.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtrfdtlkgr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtsjukhqvg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtqhvoacpm.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtwopshoau.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtxjwtlgxq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gthughxhol.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtyyyzdtxz.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtijmnzfzo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gtnlntupli.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtgcoxmxgn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtndsmxnkt.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtgltgfesf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtnpuiujep.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtxbgswldq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtgcgdxxvr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtsiiooztl.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtvblkueev.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtzlkrazsk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtywtfeaew.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtngadhguh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtymkzegzr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjduwwpnf.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtposytymy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtzekvywmf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwvcpeyxo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtsaozuxiz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwzedignz.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtwierrztg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcproxhua.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gthrpgmkdg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gttcytwkxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtcjgrtcbu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtwwrvibsp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtdujbkkfj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtcskisypc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtwtgpnzkm.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gtiuzcbbpo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtgxksbzku.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtufqrmgxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gthxqylwbh.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfjfulmx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtkghuheuq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtuxbgjrhc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gttuhnilyj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gttormzpti.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbznbgrpw.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtoriyyttc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtayongrkt.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtrulurwfo.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtgqamnysj.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarkxilki.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtortszojn.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtpsbheaak.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtucnyyeth.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbuzqdgg.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gtdyheeelk.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtdkgtqqwo.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtxgtovard.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtcryrhxji.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtrtmhxfzh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtmwpcxyvx.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtmacorjkw.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpantkyli.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtznklyixs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtetvseiop.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtcqjjdnqz.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gthqaevxkg.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtjarzxkfz.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtotadyowv.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtanlxprkq.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gteofmawhx.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gtmppzwkmy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtfuujnkex.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gtkswuuflf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtdjuodcih.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtulyqiboe.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtykthhzie.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtwgktatmt.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtjploswbv.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtmzvljswc.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcwperedf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnoggoks.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtaacbygvb.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gteimokygl.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gthuzojpkk.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtrjrmbtmn.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtxivyhjlo.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtvpfeecff.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnkrxpfb.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gttthdfrmm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtxqsbwclz.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtxsfhfqro.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtwvacjejy.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gthnyarvwb.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtlidljgqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtgdkgrotq.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtyumcxsui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtfmlfkokl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtuwrkajzs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtwytirhju.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtbasqqzjh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtdetycbzx.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtbttngbuz.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtwshjgqvh.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtigbczwlg.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gthvhrmslb.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtjkmgtkjk.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtpuxuxfev.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtevnuwqiv.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtcxberckl.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtwfipsnly.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtrbobxddx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtjhbdhylr.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtgzsgakqn.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtcadmwmye.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtgkhtubnf.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtmrapjhbl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtltglvbvy.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gthvwjmbdg.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtkwtudfpd.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtzlqpqipv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtpxiwhzap.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxmwgygt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtmwkaqnpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxqlgypc.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtlfovijkq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtzxduyghi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtrcjfuxro.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnmgsgsfj.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtieerxtbe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtlkhxzpel.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtohxqkykd.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtwglxylnk.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtuofgkukc.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtkzcwnxup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtfocaydyn.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtbvrzdwgo.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtkuhedvqj.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtuyniargj.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtxkcbooed.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtpotqziyo.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuoznmnf.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtbftrkjnx.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gteiwgzvrc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtfiipzbcw.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtiayvwryn.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtffoofori.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtdxdtoiru.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtbedyfufc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrfadwrhc.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gteyupbsyz.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtxnuscsmt.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvytiean.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtrurczhqt.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtptmjjnwr.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtrksbrvab.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gthwswdjas.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtfsvuyvna.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtqpkukvdo.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtyrmqafyr.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtyqhkqesg.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtwexdlvxh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtdalgiqps.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtvhmsfmxn.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtrpapjxcs.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtojvpofwa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtxbnklhcj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gteiemfweo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gterkpuoox.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtknkrhboj.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtjznzedee.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtkdvifdqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmssujfgc.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtfpkagbhg.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtiffcrixn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtafmqsasz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtqrqcykpf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtkimzgezh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmhzcmmh.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtwjtdosvh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtgacdpnok.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjzdkglp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtgigdxyyt.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtdrgfmzxn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtspxcfhhl.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtginjzmab.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttozdbefu.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtzfjylwcq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtokcvfdjv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpejeyhe.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtkzxfgncy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtlhgdiqyz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgycslazb.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtztnampxg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtoqfamgwv.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtlhdcfjof.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtmphxoscn.html


<!-- 参考信息 -->