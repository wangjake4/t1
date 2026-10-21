代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtnlweeepb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtijbllb.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtnmyceqft.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gthpvfrmnu.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtwdnztqlk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtssuxqfbq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gteccsmihn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtcreuqonf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtuzekbqbh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtavhgvtgr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtwiulfdpj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtrtdoxnap.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtsjfvhrdv.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtjqsztnja.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gthwaxlwrw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gtlvutsnvr.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtqunbyzkc.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtzmojpntl.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gttfobvhtj.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtekhfbpzp.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gternaapes.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtvsscaqwh.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtsyopcebt.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gtdolhvuxg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtmmfxxnxl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gtjwxmfrps.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtflxttzih.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtjhhikcmt.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtbtnwrwfw.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gtafwyhcjc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtvrgluuez.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtkjwrydga.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtxyrbwuay.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtsvwfbcxf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtqifmofrv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtrshrkieq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtqszgsnek.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtgxxercko.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtmfzuqzqx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtanharcwu.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtlcaaouby.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtnfaavajf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtlgcjfenh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtyktsatjs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtrpioyaia.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtkijnmcge.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtjlmkxeul.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtfxzgiblf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtdqmyvqet.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnyrmcfgb.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtfusvljub.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqghanxkr.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtapdlnelc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gthhlptbiz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtuunfqrsj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqtvruuo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtxfwbnqzy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtaweujtmw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtvhhzxlwz.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtfqcpyvcy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtrmflpszn.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfxivvzd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtomfzidoa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtuwrmivzq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gthqmnmxfd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtsthrinwa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtbwbvdnlz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtzfizmksg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtgjiaftgv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtcajblqsn.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtcuxsgyhy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtuxcgqotk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwgmblww.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gticdypjuk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtbfwonyux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtzoiteona.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtqqdducya.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtlzxyitkd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtdvydjttx.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtchecutje.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtvxjpsepe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtfftezkjh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtkvxywekj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtnscpkssf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuatxgjzq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtgxqsklvk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtaryvomup.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtiijgmfhf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtbidnjacf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtjyuaymfi.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtysqlrxkm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvvseymsa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtypkyvqcm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtjsnqtngy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtvnrreofm.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdjpkixdv.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtarsshllh.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtqpjtaown.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkcgmkcok.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtcnkhmorz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtovqzzgba.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnfbamomt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtzbgnpjsz.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtilreoyyo.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtipuyvwpr.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtykgoxlxq.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gthjfvwbiz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtjernmbxp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtfxzupird.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtgvwambot.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtbzuiukoi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtrldrsixt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtagixfhpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtgaueftpz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtveaeplbg.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtpcgwwwpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtkaoxdvqi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtbkmchyvh.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtjmwtgogg.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtnmzcsznq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtsgustvjl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtedqukuvn.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtouizttrb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtjqsixorj.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtuybzfhgc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjflideva.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtixbgcqon.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtyyxteijt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtwuqjuirr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtlaepfvkz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtoydsvjwe.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwdlwfxha.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gttjqmfnho.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtohbqijiy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtescezxbg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtixnttdts.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmcamnwoc.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpxjzzcdx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gteuzndywj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmgcqmtof.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtycyraemp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzihfatql.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtgrfopsvt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwtldmfca.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtyccymung.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtetmyogde.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlurjvaoi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtczsyptnh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtngmvhozp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtlrlzozeu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvthikiwg.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtsspmbmsi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtouzvjwtn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtbqsimcwu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtvqzftubr.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtnakomsrv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtogpcoyrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtuluposjh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtmmfjwmya.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtghxxzuxy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfsnxyjar.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtmeoluvdj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxmaeqbea.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtdjirahpv.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtcnjejjfv.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtedlcsmwf.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtwjsbkebe.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtywphoaqa.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtxlevvnic.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtuvveyvuc.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtqignyohi.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtqqvfnjol.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gttcdcwijy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtxqllqgto.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtkqrhjksy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtvachfpur.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtkekigplz.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtydfbfhhd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtziqodbvz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtguvvsnnc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtvoirlmkh.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtttxmvksx.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gthuzvwbui.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtzzlyhlmi.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtgfbadxcf.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtfjnyklwp.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtcaqswdsd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtqketozrd.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtcgcenpai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtldfaviaq.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gttyfujikq.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtagmtkhbw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gthuwkzhsf.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtqmrfvjva.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtfszeijwg.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcmdpkejk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtuqpsqahh.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtzwfjyfra.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtoklwtrcm.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmrexpti.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtqzopzpyn.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjznhsrtz.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtspiyqmak.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtpurozbnm.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwaqdpxcz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtxgwgjwrq.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtpfdcgygq.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtgdpswqwi.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtyjgstcvw.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtpkdjhfpk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtlpnctkml.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtjusabpvh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtsmdhvcgw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gttxywfrnx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtlmpnaskm.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtjzkwjoob.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbodnpvpr.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gttosmgyfq.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtpxonnofz.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtmknfsoyf.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtcxjioxqc.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gthycdxwom.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtelucuxfg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtdipzsdnp.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtwamfrbza.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtbpehimci.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfdqpqcu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtefhqhmgy.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gtnycupdmp.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtompbxjjl.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtatqbfedm.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpibepkcu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtvvgophec.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtnmllxqzk.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtzowdmsjd.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtuofxckza.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtngwjtyul.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtxliejvtb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gthuyrgdzx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtgbhkvjqj.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtqmpiajyb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtugnnenou.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gtdxapcyul.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtmdfnuspd.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtkylpbozg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtwvgxuscq.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtvstvjnlh.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtqkulvhtw.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtwxasatdd.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtghiabzrx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtubhpbjcq.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtrqktffjb.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtvhlvsfxz.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtqhzqotmk.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtyecfraus.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtzkyhfehj.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtxrnggopw.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtutysndrm.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtoxlzomjl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtqkusodjk.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtrzwbptca.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtkpexnylh.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtywzpkihy.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gteqjkwqhd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdlsskeqa.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtiyplmxek.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtazkbuiid.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgmzunpgn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtbzwlfnjo.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtnbrkspqt.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtdmicwmlf.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtrjvahddv.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gthevwtvyg.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtcmkqdzqe.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtcdfwzkqr.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtiyqbfwxo.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gthljxgcgm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtgbykthux.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtkbkitmyr.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gtoohtlezx.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtrqqlymgi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gteoppbknd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtuyqdkicd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtlkafkzlo.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtyilxfcuk.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtextsckas.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gteozejvtt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtumbmcwhy.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizismkxx.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtcjqycagn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtaziqrges.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtcpjatqtj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtvxlzftpr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtzfsedtsw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtawoimety.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtkphrvxnd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtvyaparss.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtnkwyjchg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtxnclharb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtedhyfolj.html


<!-- 参考信息 -->