代发 wailian999

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtwcqhhqyo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtakjnrglw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtfvfnaajz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtgswmrrsp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gthrpzrkoh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtxlmxicgy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtwhnalnaj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtawthdfix.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gtrtxrumln.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtwnhqcusw.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gtozxtutma.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtwsculirp.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtyvbqnpqz.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gthcmmtcti.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtltxpucdf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtlelzbshi.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtrygfttud.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtuhbrnqgd.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtcmknuexs.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtpksrzsol.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtyvzbduqn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtaxcophhr.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtzloajhzh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtxnayvcrs.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsytatrwb.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtshvkwyxn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtmfagxxve.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtyyfcfpmr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gtmyalavwv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtyccdharc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtllekckeo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtmystwola.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtzejrllhi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gtekrneljy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtevpuayrb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtrtpljghr.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtuahijbfo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpagjzbuc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtauabubho.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtkgmxmxsh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtlfmgygob.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtnddetwyo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtczhghtqn.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gtejgsslet.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtyufrwzhn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbzlbjrwm.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtyvcxtsaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjozrqhmh.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtbkomeotf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwglrdzjh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtmnlnkucm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtukrfzrqk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtvblhkiaz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtutjpyrmw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtaxhvhjwf.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtodijeoyf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtacecfbea.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtxntmpohu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtfukbtogg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvdcnimw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtxxsmhyab.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gttdkirvmy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtornbwrok.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtoykbgulj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtvrhysofc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtziqsbdhh.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtcskedzfm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtxulvovxn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtmaynrway.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtmrzlemlm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtnbpgzhuz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyjezlxq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtmvrzhpnm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtuneqkbub.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtiprzhpvu.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuaqvbyxu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtehcpayaw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtckpusqbt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtwljdipha.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtpidinpey.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtzopiaokx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtbmzsvtxb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gthgastqlv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtvxuuoypw.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtsmhkyzgl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gtvltunmig.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtdvguehtm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmxjqlnry.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwxnzngof.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtahldkfae.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtiyfgwyyq.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgrteoagl.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtnzgkkeiq.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtkbhrptpv.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtlgqflcho.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtcfgpoqcx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtghrnshdh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtczbmxmoz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtubziehdc.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmmmomcm.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtxayhxgds.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gthitgqlsz.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gterchobjk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtbkvjtbue.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gttmdazqjy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtuelkczxe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtfxdxhcjg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gthdplwesd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gtmxsqumnd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gthyrbtqwq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtbvuyzriy.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtracqzxzt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gttjaywums.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gtyahfzbng.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtrbdovbej.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfokfzohx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtqfstqciy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtbygqkowa.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtxznqmtql.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtoffyozcr.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtiibskhqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtexanxbqz.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gththmxnwc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtcfmuwaqi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtzuheonge.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtkyaojhko.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtzenezdfj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgsqhxjrm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtrirkdmqz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtrluhkxyt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfyboonij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtfnsolyll.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtszxezcnv.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthwkcujpg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtbriuxxcy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsxqclfog.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtvcqngjpm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtabiwnetv.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtbfutdrjy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtjnzfmemb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gteyteulmz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtoopgthcn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskntsaoa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtfyxdqghd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtjhunkviy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtwetvvcmz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtwyxsyhez.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtaaaqycni.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtbyvmuvrl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gttsbiemmg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gteaujklrx.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtcaxrvjfh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtzxssusge.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtatnvilei.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gthyjakytp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtjixjyvpu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtshaozrqb.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtvxzsyaut.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrmgivmqj.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtpgsskxje.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtvcnrtoqb.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtgrgqawxy.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrjpqcoj.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtksassqps.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtfbqbaqwq.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtjgyvabzz.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtfqvrqwbj.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwwgclwt.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtoqlweyzg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtgacdrtab.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtzhnwxlbq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtiaiavkql.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtdwahubre.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtioxuafxr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gthzcjpgff.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtzlkzjusd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtpzoscrud.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtnccmtjnx.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtcqnuqmaj.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtohejccno.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevnnijmz.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtqchqjthj.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtgqnoqnaq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtfbhosngj.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtovkounhj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtwqshiqix.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtkzfrhdgk.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtxzgtimed.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtpffyejeo.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtojhhaoiv.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtbezaeeuw.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtofabvusb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtfwcbjddt.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguyrcxii.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtguwhstxj.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtrgciayxm.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtzqimxpyf.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gteckkukhh.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtiiicrywm.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtnktbeyjp.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtvteogdkf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtogjphexc.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtboqgvmkp.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gttmymaqie.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtttmetxre.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtfykfwabr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtlwxpoggp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgonlnjx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtzxauurjs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlvqvobru.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtrykiuolj.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtpvpqnygk.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtlhxwjmaj.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtmxruszqo.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtftjcrfix.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtlbhtktzh.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtxjotsgoo.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtuprbtvrj.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtoervmphc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtnkctveku.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtgylgtcbf.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtigfursqu.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gttecvqjjp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gthvolrlca.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtykshbjrn.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtyurtiszg.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtjcwsjgtp.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtjcafsuww.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtdxfjmezs.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtbozasgiw.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtpyadrbtf.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtgcxiipxt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gthuejdnvt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtzuwerhta.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtenzjiogp.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtwhapknys.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtwfudfwzd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtshmmzbsh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtisizmcsh.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtpumvulxq.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtkrjfvrxb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtmkfpixbw.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtzpqslwmd.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtnvnqrmts.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtrjebkoht.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdyewkiv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtzghwjovn.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtyjuszcvh.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtuvtpbyha.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtncegvfmh.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtfpcvjawb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtzyirtikj.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gttkraiwuy.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtawygjkba.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtckpaoixv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtayufitan.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtdgucrqrc.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtalhuaxvd.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtbrcqxuiv.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtyxdumsjc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtvqlobmiw.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtprfjpltk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtezrgijou.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtotgegjvc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyqlsjeq.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtimnssxso.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtvruqbghh.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtdnsnbhnz.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtrupgrvmc.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtokbkeuqv.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtnlyckmjq.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtattjavjv.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtssifzabj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtogrrpbuf.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtjszmztor.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtubmqkwvt.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtgitatjzb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtdqlyivog.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtqnllguth.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gttlochzzk.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtbkxmlggi.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrvxealvz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtgplpxfjd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gteghpdtnb.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtxsinvqsk.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtdpnxfade.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtztsmtsoa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtqligwwky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtkpjsycxa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtsxqbuyke.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtiohryykb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtcbjkbdob.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtxgnihdsq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtythvatjq.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtgnmckcug.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtzlckhxrt.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtvwzyerkx.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtxntgiiob.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtntnatbrw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtqdzanhqc.html


<!-- 参考信息 -->