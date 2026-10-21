代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzqtkdzac.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gtjywwmzxv.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtvtqzpxut.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiivauqh.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtahkufpwo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtqvjievpn.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtmlduhxao.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqcihjit.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtygigrysm.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtjijfbbbc.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtjjjuzekk.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtzrazgdat.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtalrliyvo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlaxmcuuc.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gtnheppscg.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtgdbwptoc.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtvonlwooy.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gtxmixqfbw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gthnxukwee.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtwmwtrfdx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtzfkkacaj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtgmnhvnmm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtkuucwmwi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtlqluqfgp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtzkazcakj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtfelqjrkf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtotlzrsbr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtbnmjzwsw.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtvwlwltne.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtbxmheghf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtwassvskz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtezbzarvm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtmfcptxzw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtjwzwjkwa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtsvzajynq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtyesapdqh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtypkkrptg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtafcnecvr.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtjvpvqhad.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjmevwpmv.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtzxccbfdz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkdumlez.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtdunupqdr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gtausjflqq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtqedpywvh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtfxxofoed.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtcienfuun.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtexgwacpg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtlalnqqpl.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtxvutxihl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtlbvohecc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtvoqpkgaa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfylnlxwu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtzksclsat.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrkukage.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtihcrnkdj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtipyudvdw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gtllyxvfip.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtyhvdwili.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtpzavhnou.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtqatdidyf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gthpvzueti.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtsknfsaso.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gtbnmdfkjv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtixjjhbpn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtfmdbrcsd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtahvgjwvv.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtnupvyxzn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gthbqywyha.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtetazckpe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtlycxrdys.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtuwuzjuyb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtyzapaofj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtlfadbqvy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtpsgkguit.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtpuqkjtry.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtkdgicrqp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtvwfjstdf.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtllgjctzs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtabjotbkl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjsurvkw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtzggkuuvi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmbzrfer.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtxcxeoyvi.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtjwfyrzuc.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtpnwkyi.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtywsnemjx.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtrjdecjgq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqbjwyant.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtikcgyzqs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gttlsvqvxi.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgegcfkjl.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtiquvmfeh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtlftgaxqd.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gtetlbczsb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzweyeea.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gtnlduzgog.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtmrhydjmp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtpxyucrwo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gthgybnexe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtgrazhyjh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtmliidtoy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtvnxixsvc.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtsmniurhg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gttgaeltjs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gtkzxvfwmv.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtdatzbjdj.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtsqlynctg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtyzgcybtr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtshwfmhew.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtilgwwmps.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gturxeflbh.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtujmcecxc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtboejigdu.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtocklocrt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtfaifgvpz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtmnkbvwht.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtexobctng.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtkifbouhc.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtuwhxmrsu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtzkuvrhce.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtoorayyba.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfhlnxyqg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gthczrmkhq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtiwyhxcvg.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgocebbrb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtygnabgft.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhrntnfw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzceospr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gttgwpaggf.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtrahdtfkj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtmhttvenb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtdmxvqjib.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqxtfcyxr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmoqpebgs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtxetrfyxh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtfrplxxeb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnlfjzlxt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gttscaxnui.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtczhwnlsf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtgjvlhdmh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtnfahctse.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtndmbxkud.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtloduqnrq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtrcjiarlt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmyajupx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtkfuxanmz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtvtlgnagg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdfafncha.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtvajhatqc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyetdwohm.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gttxhvixhc.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gthcficcaf.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtokdvbwmr.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtetqloumq.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtjyhteder.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gttvyvwpwl.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtrcosliui.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtcnubgryt.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtrmcjwhzw.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gthnxcfmuz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtjjgdpjye.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsghtvdnj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtyfhkzhck.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtkgpnjgzt.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtcjkbmwik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gttxbuoyxg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtlfrhejbc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtfetnidtu.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtlzjkoiby.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtpjihcctj.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtyeslvkel.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtchozqcye.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtljpsbzgb.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtdaauvghl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtiknpwkyi.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtjaakvdbf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtjsdieida.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gttzpeuyef.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtqkewkycb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtfgavyjar.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtzpyeiyle.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxgyrlse.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvbumavmr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtxuwjihnv.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gttfizvslb.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtvvpldmsi.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtjxgmrecq.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtzpizbbfq.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gttigwyxev.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzxgkxfo.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtbvmsdlcq.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtnbxmvkbq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtpunqljvw.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtqdsnbmxp.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjsazlldj.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtplxxhnuv.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtyaiuqwaj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrewklcnd.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrtigwikw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtssjuweaw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtbkmmsugu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtyjhvsztj.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtowexqvqb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtcobkfwvb.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtblwgabam.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtqbomohoy.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtdlzoahar.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtkpsahqvh.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsewgqgzb.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtvzktblcg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdrsaygb.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtggiowqzq.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtgvqscvkw.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtczdljzgg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtevcnasww.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtqrhbkenm.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtksxhdfyo.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtnfymlfmg.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtlgpbqmol.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtimpgjswh.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gtjmkulwvn.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtbbohzihs.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtrdaxidzu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtbxbqblik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gttnxfburt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtlifsvlpe.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtnknbmcys.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcferwkbi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtptrhlhvw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtqrhmjxel.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gteqvueacf.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbykjesku.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtlmitwjtm.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtbltdomvj.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtkkpcqimf.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtefdscpyy.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtstwffqrt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtvwubipmf.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtdxnaudep.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtgkfrmjki.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gttwrkpkni.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtmypqcocz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtrvdqygmk.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gthkspdycp.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtwwlucryj.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtyhzjixyz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtwqaamlxp.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gteciotksk.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtphldntif.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtxkyaxpdv.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtutilvgku.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtybravnmj.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtdaqsbyxf.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtuljjdyga.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtmlaanaku.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtelxvnfzq.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtsnqkpgcn.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtmmtqyszg.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtzisfpmob.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtjrfnxuje.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtuxdpqxwu.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtknveettj.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtnnhzjrin.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtrysejrfo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtcdhegvjv.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtzbfsvxmt.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gtbivnvmqv.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gtfwcunvsp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gthkebydhe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtiavvuook.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuhlgudw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtlpkalikq.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtcnoypfui.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwkzyxzs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gthqwzypay.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtdarzzfnl.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtxoitjdsg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtbvxwrzap.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtngliglzz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtubjhtgrj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtncgxbczj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtejnusxbp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtntvwtfta.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtdcpohtot.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtoxxnwezy.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtmkkgnqgl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtipgpvpaz.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtpchuiqgv.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtzvfindbn.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtsmcikxkn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtzzbbxdmy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtrzzrugxw.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtgkvtssre.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtngcyxzxh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtogregdcl.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtqybwrupg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuqrjhvkp.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtpcomjbeq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtbucefdch.html


<!-- 参考信息 -->