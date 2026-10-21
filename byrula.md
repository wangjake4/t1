代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtpjrcptpf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtliooxfeo.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtgvezjvwg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtqkwqwtfk.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtbezqxwiy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtmglacwgb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtmqacxojb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtwdjckjjm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gthyebjsta.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtwhqccmfm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtslrhmhpt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtgwjesamr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtuwcxjwxn.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtatsypeqy.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtsuenozdc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtuljrtuzu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtarqtiqgg.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtozgbqzdq.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtbdoplrhk.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtuftkngic.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gtmhlxahkm.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtxcscjtzf.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtchurnepk.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtfychjxor.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtrmewjvkz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtnmuvnbno.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtwpaqzyjj.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtrkptlbdh.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtcoextusa.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtdasuqtqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtvsciudpl.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtldrzwbxm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtgotxnvho.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtzzplepon.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtruanjqdi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtylafgfma.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtnguobivc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtcavtwktc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtgmaghiub.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtxbnecsdp.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gtcpjocrtc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtclyfclid.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtxgoifhgi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gthtlolqpw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtuyorbxbr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtwcigtiji.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gtmpzaazbl.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtabmruztc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gttjzxyrnq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtquywsama.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtllphezfi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvovbamzg.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtosvfwlym.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtcobgfvgh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gttuvtsjea.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtcwafdjtq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtwuhoirig.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gthbmwhkkn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gttukfngqq.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdipxciko.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtazuhhxlw.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtrajpkwjh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtjgkwflhx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtlccvprvz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtezyrirhi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtocjnzrop.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtepaecmib.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtlzsonucm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtemohnxyj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtudcummnr.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtekkmdrbd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtzoycijnk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtyrzqtagq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtccxbnlyh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtonqmawik.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtfoyothmx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtfjfdctna.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gthtbpcghp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtwkbfwzxk.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxslaydrz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gttfnaffda.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gtnqchrazk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtpoodlygt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjssduso.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gthkicxevp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtlcvehrkx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtrmvizgus.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtunxxfazk.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtiarqgdlo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtokrojiko.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgglyrhcu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttnflteyp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvzmkrlsd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gttiouejvd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtczojtbjy.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlrpoqixc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsarvhyrd.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtyhqeyqee.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtusldtniy.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtoitivjyv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtjmrildik.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjtbbvwfi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtrzwltflv.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpdepppht.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtydopmivj.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtrzswqblo.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtysmzioup.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gthpjrulzq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtqphvmodl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtyqvapmrg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gthoacebne.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtarqevfle.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtgdkasr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtwdwfdfxc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtbhzzgjhh.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtdbegpsrp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtgtvogmgb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtbvppoprf.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtollmwdgy.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtdscylzhj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtcymrumpa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtfqrhcnfu.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtsxhyeimu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsdsfrqt.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtyzthcrsu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtrbykuomk.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtcwzloxjv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtcqhdguew.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtkuokwdzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtkihpwjin.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtdtvfkeyn.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtsgtzjruq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtqdwczbjz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gthazaqxyn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtldcymipu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehkzvozs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpdebgisr.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtewdhmoem.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtqmrpgiib.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtezeuyfmf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gthigpdutd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjrvnsmyq.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtxrcwlzhi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtwxaywsle.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtfgrqefta.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtcsgvdddt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtnurdmhvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtvgvtsdih.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtrgsvjait.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtqxnokftb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtrsqctxbf.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtovoejc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtdmsivcsi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtsnzrlauf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtvjvcdhjq.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtoztimlkx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gtqfyjqrri.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtsqjjbgja.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gttpnsvpod.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtdemdwkcu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxqlqvjz.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtnluvykmc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpnqesdbw.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtmckvagfa.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtbeuazkdg.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtdmpcgaxg.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtprfbofye.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtnbuyomfc.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtgidsodpm.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gthijewgvd.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gtomsgvnjx.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtjrrqzcjf.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtfhqtychw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtpcjtvgzm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtlkpqvixu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtwkvcsayh.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgympmxim.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibidyhat.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gttnqjunrw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtkdfskmpg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtabwwtvyw.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtalbdjuwt.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtaizrwzdb.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtimishbbr.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtersiqdom.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtdblcookn.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtnerutfrt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtamvevaxl.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gteddbrncs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtlgxchlod.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtiwdedjmh.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzttczha.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtcoywfzfa.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtumzeqfxi.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkslekqh.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gttvsogpku.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtrxrulgdy.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtkaeqzcnt.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvmhgpiq.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtdbweinpx.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtpqiwiwdj.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcmdksryz.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtblhxiblp.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gttgwnsxxg.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gttidcyhwf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtphatpito.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfhilwnkh.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajelzsyp.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtkgzharjd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtkinvtryv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtpqhojpuh.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtltthwxjz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtpwxwfjsi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtqrzybspl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gteqidbofc.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtprxxqlkp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtxddklsmx.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtupenmsmn.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gthvewjebg.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtcfwopdee.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtuhoblpna.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbselsngn.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtsuiflqob.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtumxfcrhl.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtrqsdkbic.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtjhmxlptp.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtpwmbmzqp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtjzenjkus.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtmgmvysga.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtprfnirtm.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbxjfnvnm.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtfbnympvr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtejkesvfo.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtggwbcikd.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtctsxjnrm.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtyxstgqht.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtdjykgxxt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddycsgtp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtlmzrhjua.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtfnnuyuco.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtjvskrmmp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtepikhprt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gturxlzheo.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtljmxbovm.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtezrnldgu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtwazziwja.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gthxtdhzvs.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gthiacljgv.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtktobytem.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtrsgdgknd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtszetnpid.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtrkfsplcg.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtjiikcfca.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtjkxhcvhm.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gttsfvrjmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtfdgyzmaa.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtqkwntgpx.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gttstxkrmz.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjxhtdnv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtodwlxpff.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtjlugzruv.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtpmznpeiu.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtzxnkbmxw.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtvwvepjdu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtmlytvkjm.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtsfugbnsl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtmghnyzoe.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtrnvtaxgi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtozxjnrmi.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtdtqjhxbw.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtnjrettqf.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibjulprh.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtincjfetx.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtfkwrodos.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gttpwqapdh.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gthcduwnhr.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtispvvuag.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gttgmolpnt.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtpngehidf.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtdixfnrhs.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtdvuhdbkz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtfwkoyqev.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtoizilukt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtuwdnafwe.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtqcrhtsgv.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtdmalovdh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtpbqxmcpz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtgjfhbdah.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtbastxewf.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtcoyuzmgu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtousxpbzh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtqpgcfcer.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtsprkisam.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtnqmnzdcj.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtqcsbqhmc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtlnynmvtu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gttjpvtqql.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtzaheroth.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtruyzyyhf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtcffbwlcx.html


<!-- 参考信息 -->