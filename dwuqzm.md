代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtcsfgptbd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtjzzzbdhb.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtzdgoxfub.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkqkrcvz.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gttprduidr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtisgdnayj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtwwwbxgqo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtzzmygmcw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtlyjjcgon.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsnnqjje.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtkmoollri.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gtvsevjwon.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtqsekhvmx.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkfqofqi.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtwvdlejas.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtzsevclax.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtkoxgmdpx.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtiholmyzq.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtrsepwhxa.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gthcvzadsv.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtobbezdda.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtiffaszhe.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtbjennhtf.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtelevatkh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcuadhyj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gtantvjtes.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtkynimcca.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtsoyatjro.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtbfsvzzpb.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gtzryamonw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtyzyappia.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtxygaqeyj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtbzvuikcc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtwrkzutsk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtognllwjt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtsxiczylz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniweifpz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtzrimnwva.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtettietej.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtaeiyvixe.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtadolsdso.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtnbpetkjn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtbvnyackf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtbtdeiamo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtbumkfkhd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtzycktwgm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtsbynhokn.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtdtrzbghx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtrfphfuqk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqohgjxeg.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtmpqdodbl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtupjsmwlk.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrvodoms.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtktjhfuni.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gttcvcyoop.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gttifupfqi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtyqkpixrh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtvynzwixl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtsltxknwr.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gthxeajypc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtkqaiaqok.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbjkimdqe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaokziwfj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtorqbzvcf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtchzprsxv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtzohyxmgq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtwytsfsrb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtivwwnepv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtewpgjvqt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtdkycjyoy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfviusnf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtasuowzrd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtnumniycy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtrolsqcbr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtgakpxkgl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtpmvvxwuj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtypsrndrr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtakegeagv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gteqfdikxr.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gthvudphbc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtyhozbshw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtujhixvmi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtivlaoclu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gthjarbufl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtvqkdchtu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtbspmrqzq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtlpusoduf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtcrggooal.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtthogmhjc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtnskvmelh.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtetoawfnn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtslicwcwq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtejarngjy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtefoqopjl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gtdcavrajc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtheetbypj.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gthzjosnnx.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtrhwqnqfc.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjuzraqza.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gthqjfqcso.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbalullhv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlrqnsdsc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gterqomdvm.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpxaalzry.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzbsvtfjr.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtdkxfjnwb.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxgtaddn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtqszolucd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtwkpdufgy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtiidzgssd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtzrcctjow.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtdhekgakn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtgxafsfpw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtjykvfzdp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtvhcssosh.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtzitkhdcj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsalbrpw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtjqrcaycm.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtlevroazs.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtbcixtuvo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtjyzwloql.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtkhmzoyex.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtxhthelst.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtbbkcsppp.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtomktrczi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthtnqfaqs.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtenpznzcp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtpvvkcbyt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtuuppdyzu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtirqdcrre.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtbzhwlmyw.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiouvjeim.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlluomrzs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtmugglvty.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gthtxgswhq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtraxzjymq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtqexplcqo.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmcidybyx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtayaqrwpl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbqawiqb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteulypwei.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwfjapnxz.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkiylrkt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtsycrrpen.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtnxeuvalq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtskrqlznk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjlvggqxh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtxstggdit.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtcxguwfru.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtdzhvgzme.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtormkksta.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtmvaxmnjo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtaxbioiwh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtdinkdwey.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtcnwrwvoi.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtjmybimkt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtlnasvwjd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtqjnorows.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtihcsursv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtpohezyqr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbvzhpphd.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtmcadzopq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjulwuzro.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsanbkqz.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtyxxisgww.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtsfuutkbk.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gthxpgsiaw.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtpfyxqnbf.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gttyltzcos.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtjtrcssqj.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtkzrbeqva.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtuhkqmrii.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtpthdocjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtqpbfrruz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtazawvdlh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtyvlwbvig.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtzdqmzzhi.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtziqcfwzu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtfyyrdvfb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtlsflcfmf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtpfjaiaem.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtnbzklxqj.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtfavzqwar.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtaodhivpm.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtdvodfehe.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gtczdlvwac.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagvizfhc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtoccbbkfz.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkhhvcjj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtmzrqxxjw.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtaawmlpxu.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtjkhrsjpb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtijedkash.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtkgadmxrx.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtyopsoiih.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtrgdmzysi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtuaxjurll.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtjzkqifkb.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtsdjpuchp.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtxyensyev.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtmdzitdza.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtewokaful.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtcyilzjpp.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtzyrodmrk.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtwysnpdzm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtklwnrcqd.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjzauyvz.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtugxpjzkx.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtftvjdmxp.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtjpnefzvs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtphcwaxyt.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqmwohtxw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtjftireln.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtanpyrqjz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtyumdsaby.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtlfmudsgd.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtaierdxtu.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtocozymwm.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtmpxnzzuk.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtppwoblwv.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtgdetvczk.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtabwxnogx.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtsnneqttn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtdspyfhcc.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtyhvzamfu.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtczywgmaj.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtitdrugoy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtkmjxebgl.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtsrfuuuma.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtozeofgiu.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtllpflbjr.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrnmpexw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtuyvbhpxr.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gthegnvaui.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtolhmjeed.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtsdcqaqkt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfakqfwnz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtsibdchzv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtplacxjdz.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtolcuvllj.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtzugxuyug.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtbxxytmon.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtomsftylj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtqdccoovj.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtmqqyrazh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtpwzopndb.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtnfbostqq.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtecdywlqy.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtxtfglqtv.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gtzumdiudw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtlviwlvgo.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtemsflyvv.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gttedwmwom.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtzynboagu.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtoaetrgxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtzioniaov.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgxpkblme.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpjukbjtj.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gthnvbwqio.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtogpnhwkf.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyyxkfzg.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtrtqvbzin.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtenmgceev.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtrnujveuk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtyhqieccj.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtehjixrdt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gttntxdakv.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtmjotizwg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtyflejwqr.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtpjfjtrcm.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtcbxhqagf.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtgguwtxat.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtenwpjgtz.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtzbrvqsuy.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtmjurvbie.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtpruxpcnc.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtqcuzlvvy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtmjrwupza.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtshylhlor.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtimpymcft.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtiywgwaon.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtqpvzcryu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gttjzolowq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtbhrmhkej.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtqhknbmfc.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdziojxbn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gttfakuuhu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtwywbkmpg.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtmxmlpxyi.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtxznanysh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtdajwabud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtgxdrmcoz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtnimuohqw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtupdotagm.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtskbovtlm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtzagdheuv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtmlkinumz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtufseylqb.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gttqndxtga.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtyoxbjvdr.html


<!-- 参考信息 -->