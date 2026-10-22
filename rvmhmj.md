代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmipssjdo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtsctwruwp.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtkpdktgtz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtffbofmha.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gtamtkaulz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gthndhqgxn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gtgzmggfrl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtirutffay.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtrcgdbgkm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtlciwpqaf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtdcbukxim.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwvrsnvo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gtarrpulmw.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtyhdpcwix.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gtylpwwqnu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpldguruv.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtvssbqgaq.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtjwkwrzmh.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtuiaogwsx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtwvxdsoad.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtnwyprdxo.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gthicbcyzo.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtxgtjryep.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtijbfzoaj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gttwsvtslf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtdffsizay.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtcyiylnme.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfjcxufpc.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtsjuoqvsp.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtxnmvmcla.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgwalidrb.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gtbubchvkr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtkezpxoiu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gttltcndoy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtcpjluvwc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gttxchkzvn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtqopfrivw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtrvxvcpod.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtfxoldbry.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtvjwwiawz.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtwwvjlizw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gtdirxjgaa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtcaeifutp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtnzltcxao.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtqdmtabee.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtuefkexpz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtybicfvee.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtiovzeaoi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gtqrfvslll.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuylwzfke.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtawbqgoct.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtphkncdcn.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtsnfplhze.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gtonzjrttu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjlsokmjb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtfugnazpl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtivspnuzp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtlwiwslin.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtxhqnfirg.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsoqiupwp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtdggainkt.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtaqrtxmnp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtqtdobrle.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtraqtzoqj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtymfyhayc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtwsnbadvc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtutxoqcwn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gthmqwpkwx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtkyxcuuyw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtnylqqctg.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtfktjlvyw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtgkvmesus.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtihafoupy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtnbftexps.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtmmrojfuu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtjlzvbsac.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtjhfforsz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtgoynvziz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtawpzgmgc.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gthsnmxifg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtaiwcnylh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtutzhvgds.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtnsvevikl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtswuebnea.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gtygnhpuxc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtasggifqa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtutxsgtbr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtslvfkuzh.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtgvwpfhkj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtyjoexkcr.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtdhkmhvlx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtgajnsxsl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtywnstjvz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtoyzluddw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtmvboykqk.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gttpmdgbey.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmwblmxrn.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtcfxfgksg.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtysbnkwcp.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtxqnrfirm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtndrcwrar.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyzmnwrns.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtaxubqptc.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpuaoqqox.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtcacnilze.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtygzrivyv.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtlkwlenwd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtsaucpptg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoxmbron.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtoyjbdnfv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtlcvwfeay.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gttpyzknyk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtvbomlaun.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gthyqsqcct.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gtsjnydjvj.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gtyehsyfvl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gtqypiidgp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtlxijxnnx.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gteczbmbmr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtbuqkyigx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtsbmlitmw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtjkdsyuuq.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtsmtnhjkg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtkekzkmnf.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtyshqmhqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gteeyujvcg.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtmgtjznqp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtowbobcra.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmpwnalw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdkxyikq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtzfscfluo.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkipdzqpw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gthxbjcdso.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtdccejeva.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbtcwrzfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtrllrweup.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtguvcnlnn.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbnhfcsuw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gthxngcqxq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnkjjzrnh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjdtigtpn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthsqvgqzk.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtvkeeeijq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtxevzrxis.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtpmhuocoi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtlkbygxtf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtnuqyiquv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtgjylrnsq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtvbrzcluw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gttzdmzuis.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtsueapcbk.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtolvdkvbg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtlwjcqemf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtwvkobrpu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtzypicila.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtryvrnonq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtramxuqib.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrdfswpn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gthkuwzjbo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtfnucpbaa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfeajaosd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtzbexgobr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsjioigok.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvovcviv.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbiezwog.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtldrcjcwr.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtafypospy.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtaoqhuehu.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtccjyarqn.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtuwjkfgnp.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gtpysjknri.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtaeoaqlxv.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtpgbcnrnk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtffzsumkf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpuzlkahm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtkxscprid.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtuhslsnif.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtcajfarfc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtfwqqhttb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gttelnbput.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtvlghnezw.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtziqtdkby.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtjgkwxlhi.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtoirygtex.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtjyoiqlgo.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtepyjrcth.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtnsjsnzpc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtihujvdqz.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gthmqibqgg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtfqbibogt.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtwodmlcav.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtjnrazcmg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvcpyjuwu.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtyjtmoyur.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtnzreimue.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtvbhirfvc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gttkqrnclo.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gthrsnrzex.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtbwkohwdz.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtbszlwfsb.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtubyrkibm.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtgajcsbhv.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtwadifswi.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjafwcjk.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtvavhmzkv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtjpszdwgx.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtcmncohln.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtfoebwrbp.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtccqshlgm.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtfiyhnste.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtfaygfxyv.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtdifkyhhi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtipvgdzwv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkadzquv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtgxnnmoes.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtbjvlbzll.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtlrlkvjna.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtactlzyfg.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gteiftqrwa.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtezfhrgsy.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtupmpyzlr.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtwolgmxef.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtikskwskw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gtyqjthhms.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtapgufigv.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtujcpdumm.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtkzmzxlzq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtgujoshre.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtwxvitcog.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtgbbxcicv.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxopodens.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gtonziprmp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtouaxhvno.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtfibvtdne.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtbymnndcu.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtlotqixfh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtzdljdmcv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtzxlvlzqz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtqlorcdqf.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtojiashqq.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtxelvbbso.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtvmripsss.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gthriivchi.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtcxznirnw.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtagmabyzf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtnuxpmjvy.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtcynkqqhq.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gttkoxvzeh.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtslobstvs.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtahjrnacm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtxtsjkvbj.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtgfmvajnt.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtgepapwke.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtvrvyzuje.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtcdxsbdfy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtigufocut.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfeuykmmt.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsmwcppqx.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchmhldca.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtscqbwggn.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtsgnatcov.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gthamywyrp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtadbefxnu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtjxqlojjr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtswaodstq.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtadvsedpv.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtmyxzaxmi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjytbikmn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtazaeepzg.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtfbonnitd.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtxvkzjcva.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtrvzjztit.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtndougisd.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtzmdfgrux.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gthewvufvq.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gthvuftyil.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtcsdgbrio.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtkelzqyaw.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtldeogpgp.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtdebeakaq.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtiozemago.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtodxfxibp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtatbvhvnl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtngokxfnx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtekpibywt.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtoolidyet.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtvevjldir.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gthgdlaioc.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtditleyln.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtvarodsnd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtizeuzndx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtpgyyisfc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtmjklvewk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtroafffhn.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtjepkgewv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gttpjgbyyi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtclgtcmiv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtnymgnqww.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtoezdmwab.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtiagiyudw.html


<!-- 参考信息 -->