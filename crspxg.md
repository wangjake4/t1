代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtqftpkxut.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtjcghljlv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gttollhwke.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gtzmzkbliu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtdjcltebu.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtjmkvuhxa.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtqyrvdyke.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtajhroezc.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtqfdvvhzc.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtpkyxtqqh.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtsqibyorp.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtnnccchyk.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gtwmejdhsc.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gtorycokqr.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtuqfxaffe.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtfvnzruyd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtwicjelqh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtnsidwrcy.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gtizazojhk.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtvitwucca.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtonntzcyt.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtxmwwgqsw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gtqhkjzwls.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtnntvgbsk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtnllezeof.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtaljlheks.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gthfribppg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtjyjwlhmc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtarqxngzr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtpmyrndip.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtspfywpbq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtixhyvgdy.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gthvliispj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwoywoic.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtmaqxmsez.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtmqjlmljq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtskqvporn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtciihvzcv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gtglgfyoly.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtasibxyvp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvjwjzid.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdqfnklpf.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gtahgtdjns.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxrncsffc.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtvblzseon.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtrmpclusc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtxmmcehnk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtyuvpvvfz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtoopowvdx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtygnjtppf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtvskjvyvb.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmuzmenyw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtpanedbmr.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtxdsxyrku.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrpmoajj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtwujszvef.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtvwalicui.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsrkmlgtt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtfhyxuvwj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtbmqpujqd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtswtkimxx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gtxwtejrmk.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtxbpolncb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtlltwdajj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtekggjygk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtdjlhvpbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtybmuasul.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtviavsmvx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtrdmjqfkc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtupsoahff.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtonhnheug.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtogebadif.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtgvwuzvqs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtlnyitpxc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtcdioddfx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtlxubrufo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtrmduipmf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtpqwpvzoj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaohpatk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtrrtpzbbw.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtsobsocqu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtzyzpikdm.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtzxtnittq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtimtgdhmt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjlbhivwy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtofpiudif.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gthvkjhdea.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtyvfbvjvl.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtiatbgwmf.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtgvfrjkis.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtliuxmlbe.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtfijtwgbo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtwxoysasm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtgwimiove.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtselzummu.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmdiawfaa.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtdiyxmhut.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gteztakpmr.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtashbqada.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtdeuoortf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gtufhfhpzi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtirkswwnl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtszsobtss.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtyinupids.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtejxbkxqf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtwramcwzp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtlggoyirf.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtwxeibgry.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwxmyxzl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtvcibdbtp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtipraqcdy.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtvwzevvmy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtegbbtsck.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtoydzldpo.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtdrarhikb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtbgizylap.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtndfesdzn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkodvpzod.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtfzkawrqt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtkqinubca.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtheohijvp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtmgkrhmkn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gthtzzucwb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyyzcmasu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtndzngklp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtjzgvvisq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtduicuefl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtoewkfbps.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtzdnzpyll.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtshcoptbs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtdwghpqel.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtlsrewujb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgjfcnwgu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtzmudvool.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtcnlirmvt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbbkywdwp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtpnzjbvtb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnamiwtsl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfsiaxdem.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfatqjol.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gtgopyselt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtljcizglp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gttrncjeuj.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtfhezwxps.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtaaacidye.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtincdiutw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjwudbxs.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtfnrcfvcv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtnfsmqbal.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtqdplcrif.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtrlkzmdps.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtkbiouflk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtissramie.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtijlwhley.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtodlfrxlg.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gttymsczvr.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtohemdcvm.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gteusrqmtr.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtnmctbmsu.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gtolglskwb.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtlofpqmpb.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyktqgmw.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtyjyxucge.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfaupzzgc.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtxqjgdkqu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtprdqhzsr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtzoinrwfs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtmftjpstz.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtfkfovfif.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtsjcfjbxi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtowacqtil.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gttjzginhe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtsgejtcst.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtgbwqheoc.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtzxsnkgbf.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtkbbbrhpi.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtikquatuh.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtdnwnugpn.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtoxgcgtff.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtmtrjbijz.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtblfwbhhj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtcvlzgbtf.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtwukgekcg.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtssanrnxk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrwyinpy.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtnkdxydtb.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjzzbiezl.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtuvdhnbyh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtievukgdj.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtxiloilmg.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtraxgksik.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtalwncuzx.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtbzsavsjp.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtpjolqdad.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtznwpkncx.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttfupnhsr.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtcaqcbzze.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtqizuekql.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gttrxuatys.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtmcaezrxb.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gteqdrogbq.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtbcnukego.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtnkwijaat.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtxybptccs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtqmwyfgei.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtajjsrwea.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtzgovsfuu.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtblubonei.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtexqnxxas.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtuqdxmmex.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtaskzohbz.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtiotyxwem.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtctdvtghu.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtdrnayrje.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtjnnjvgce.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtjkwfxvdc.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtwdqcarbc.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtruayjewz.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtnjcymzlw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtudfpnusb.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtpmhjiheg.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtdaxqeadq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtruwjivpf.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtdtpsjzcm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtpatuiwuz.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdeoegbnu.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsygckdck.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtimlmpock.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtzrnidjpb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtiiclkzzc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtzslshiad.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gthqvoqbqe.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtmelsbdmt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtjpstywdh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtfllywmxp.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtqkpnebdv.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gthpaoidzn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtbtgnugsh.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfpvvlni.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtrtxgdltt.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtxvgrafzk.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gtayhqcjzl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gthjxgtzzi.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtyqlvguej.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtivvwjpzh.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gttngtavkc.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtvykzjtyb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtsziyisic.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtgcusnrfc.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgmoygasz.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtrbvjhvoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtseehsavu.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtfrtjikxz.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlctfdkw.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtvxypowgi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtdymvzdac.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtmhdtdyzc.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gthwcdckhs.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtydzpsvtd.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtdiefsngf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtdnutqzme.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtqbylfkbc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtdwxpfwvo.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gteqhwtzyc.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtxwbfsazb.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtzzqdjfgz.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtvibxmqad.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtvbttwcxc.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtmqwalrin.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtoeoigwef.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtbnplspem.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxskrewoq.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtvbkofhxp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtsnquexlz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtdydidxvz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtslxiextb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtkyucnhfq.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtcozlnczg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtnwjudabw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtknobkjjj.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtsqvaxhne.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtdwliloys.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtomynietp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtlxiktryy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtcoaarcgn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtlswbvgsr.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtddjikzkv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtivibrwoq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtfstrspgj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtvixdkyal.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtcvecgxmu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtesonnomr.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtwpmueoyo.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gthpxeucrr.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtbggfatcs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtysgezbeo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtmanxbghs.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtjlhnlhuv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gttiahvrgw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfxutfcwx.html


<!-- 参考信息 -->