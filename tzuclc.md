代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvanzkkm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gtdrlhzugh.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtxjvesyni.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gtyhbhefmf.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtjonlnhrq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtkmgoekne.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gthfzpngpj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtgvpbmqzw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gttzrjwxmu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtoyuwrbgw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtdhblpxnl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtpjlkyfsk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtdvtpambq.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgdckztp.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtosgrekhx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhpxxnzg.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtbspbhwqp.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtqjmeyilp.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwcsqzzq.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gtvobduupf.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtorzotpri.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtkpiyasyv.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtutffwjpc.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtlclakvgh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gtnpvvwbpx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtlhftzaap.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtknbimeiz.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnpfdduod.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gthbbxtrea.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtttmmtrci.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkpvvzpyo.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtnixsfqva.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtopqexwdn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtunxqjlrv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtbgxkgdbf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtpfchtadh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtqtwhuvpw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gteywtdyqv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtbcuuzauj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtpalwtctb.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtdgyewvmb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtsmngqolt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqguqygvj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtvweefhtf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtvfpwltvq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtobvisojt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtiyinyydw.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtxanafxll.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtjimpdeht.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdvcyrdgv.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtersafxjs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthyidnbgr.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtnfvbxmoz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtwmrbnswf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxtolfej.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytxozjrs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtqymqufiz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gteufpexvu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtfukqeows.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjurxxie.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtiiqgqfzo.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtjlasnhzv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtymrgcjqg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtanrsjouo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrhjmlam.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtmhtcbxbv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtjqoydqnk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtgamipwaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtkcueuxca.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtamnfuiuq.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtlqzofyqf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtvfcityys.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtmabbqpga.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtzxklycub.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtqnqbocvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtmpbjehye.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtvzhalxyx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtnhkeyhmn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtznbzsivt.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtylezclkj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtbxhnbrdb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtapkrahyz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbygubmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gttabioglt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtnijielul.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtvjufgvpt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtwcmynajp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtujdaxjrm.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtjjenyvbf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtrdcizhzt.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdyjkhkwa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtrrdyjrja.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxqpkhcnj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtxseymdao.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtzdcguxrk.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtfqvhkmep.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbbabvtqx.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtrnugsumc.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtueysdwpu.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtgfkhpvla.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtpncmsdcb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtepkttoww.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtdjkgyyur.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnpduvmzb.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxkrhrdix.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtzwuxbihx.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtbbyiftdn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtbchzbuns.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtpymmibah.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtpobccduz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gttuoctiay.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtukghzggh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtlofiymvv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtavtqsust.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtjmgltohb.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtpawjooqr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsjncrqq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gthrtxqszg.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gttlkhnlpb.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtrffmxers.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtpddrqoen.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtgalobdhm.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gthdegbsig.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtfjsavxzs.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gthvoaqrnd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtvbdcscrd.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjnjerbd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gttsnandzw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtqiepioux.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtrlbfekak.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtbapauimk.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gthpckmjnk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gtxsvgwfgl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtuiezwvdh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwdsszlzc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtwflzpyxd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtoyjyqcjw.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtftprppju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtiuqdzxgv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthzahtdbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqauztjjc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtcxoldvzn.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtbajdquhi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtygmwaohu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjmujwfwj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzpggxtkc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlhyobpso.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtvmjcwhsm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtlsuayifa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtzbxqdtpf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtbgfwjwdc.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtgkykxqsy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtnbjrwjig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtibaxvgln.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtyockmxyd.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtizfnpzwo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraljqqlv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtplkqkgnm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gtnybiifgr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtlhdnusvc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkqlgrnmm.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtcasezgyv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtldckzqpt.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtdppoxpnk.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gttxvitssj.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtqbvdlopi.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtgnaruoph.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtfzksmryd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtvyosxmqd.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtlsmtfxkb.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtipmazqui.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtenkkxbqk.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtrzvpxtwe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtdwfqzqal.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtbonhehgm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyretagkl.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgyiptcla.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gttjrectxw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gtvrbizouy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gtttxehzhq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtemiddpqd.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gttcvrerfc.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtxpwpzsfy.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gttmjaivek.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtirngyrwq.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtlpfydqzu.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtrxxbngpw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gtkdpbhgju.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtiuevssyj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtfbxkwcfs.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtldtauhtx.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtgovvqmqp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtosctsaxv.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gthzmznatd.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtzinskvhi.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtczezlgto.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtrbmgowmx.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzqyldjy.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtwohljitw.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtwecqqkgs.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtynkrhbtf.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjgowxkln.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtgweqzdek.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtbvipbajm.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtixyjwrgw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtiqmlexok.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtlrnkizmz.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqibhqdjc.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtookhqobw.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gttuuyvchz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtyxslvmhq.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtlytvyhsq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtjzgroyzp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtrsedbcyy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtmybqjuaq.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtynuruzbv.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtmnrnwavv.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtigyrabih.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtadflpiqi.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtgpctksma.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtiuebvwja.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtxsunaeve.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtjhsfzoys.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtjlvtlbfw.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwcsphsf.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqrvkjpg.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtwbxivgxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtszxfemwf.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtpcqklzyq.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtypqxgnha.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtpkpsbfdo.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtboiaezze.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtrxopclfp.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtpuoyelst.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmgawhsw.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtvrcfeyni.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtdhtlulul.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtmtndbuui.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtafhekrur.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtpvslksbp.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtbfbuavxu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtuyikpeou.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtkscphlfj.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtotsevinb.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwmnkccv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtpozwooib.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtlvtltpkl.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtmaxlgvhq.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtpetaqttg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtgeogigcl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtdyriaufm.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtzduaeclq.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtsghnurvs.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtcxzlifda.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gthrkommoj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtxxfvosxy.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtcmahgcmh.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtuobmlssp.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtldgdsetj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtdxgluynl.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtienrfnoy.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtjtwcmksd.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelgzeaiw.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtxrcyqfko.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaalyulyl.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtorwjfxyz.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtqigcwwpo.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gthwohcnsb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtsyayiabz.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gttfbfwnfh.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtbgpyogdr.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzcuftibc.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtcewtfyhl.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtwqndmcth.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtheesjmeq.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtqndsxkii.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtvutudzdl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtfzkgbyhy.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtvoqwknoq.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtswteapof.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtorzgxdwq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtyvpupfbt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtclrcofay.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtlkdkdotw.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtrazmmwod.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtxchkejmz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gthrxmugrz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpputclge.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtiflyxueu.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtjukvpaku.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtnjgaprii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtphtoycqm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtvhlhxzkq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtapowpucb.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtvgvciggm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtvgnfqjei.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygeinokf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtemnbguza.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtmkqidazl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtfrxjxjzw.html


<!-- 参考信息 -->