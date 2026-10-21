代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gtyguoaktg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtlctnqubn.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtmpxzyepq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtroctoaki.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtsqrwsarg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtqeoptxym.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtsykpqlmt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtjjlbufru.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtwrtjzqim.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtpkdjkvdg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtgeayfzao.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtgujozwwa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtriwsthmz.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtwhwfivfc.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtljirlvge.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtiwflpmtb.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtdpcaoifv.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtujuzhjck.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtyzqsmfwp.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtbenjpuyy.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtfeulyrpx.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtvedlrhcd.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtniqxkqpi.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtvlzfgwav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtckvcfysd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtawkgmrtn.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtvsmsqugy.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbekicex.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtjjbvssyh.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtmxocqnpq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtrbaxlkrl.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtklxpwchg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gtxgibqdmk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtdveuebzu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtvpggwpae.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtnknarbse.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtqeuaczeo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtfmzxuxnx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtdkatmrzn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtphpjekfh.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtrlygnwje.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtkypkmmen.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtwvctgtga.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtqvqagkzj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtcqbqxipw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtvjdvbdel.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtzwpdsdxn.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtddmzjmpu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtgdnvmlny.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmvewycnq.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtksfzfhpg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnptedhrx.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtwflhgjxk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchqjqohy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gteohfapfl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtvcslyarw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtgmglgooq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtsyaysoma.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtupkxhfeb.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvkruyyge.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaeuulmt.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzjhancj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtfbmhfjwv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtyounfnas.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtczuyfern.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtlovytgxs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtqoeddefu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtfxxlimkq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtftseirox.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gttcrsspnr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtpiloxkvt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtwcpnsuiu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtdykvpnjy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtnwrbwmhu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtolzwpxfr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtutxsibps.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtcgnydhqx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtmstknzzb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtpratlkxa.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtnbclgpct.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtuqpjtgja.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtewmfwcru.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtlaqhbhmv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtfypkvpvw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtuchtlbai.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtayygyncs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtezzyocvx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtplkymptv.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtubqoovzx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtkzsehede.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtuuzigsbm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtugwbqujt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtibnpzlsh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gthevdxuqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtaqpehyrq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtccjvdicf.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwcmbmogo.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtcsopfdbe.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlbllytvv.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtgcnhnjpb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtuvzngyra.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzyrghgkg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtmdnzzhyz.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtpkbwbldt.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtmdgxbbzo.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtazhrousk.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtltqifrts.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtatrabcsg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtqyoygsyv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gttovmmgsd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtmanokcvt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtqklanopx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gtmojazmvk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtxvzgavvk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtwmgsnjkm.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtwkzjjwbv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtnsjefaxy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtexwvtywh.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtrufdyclq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtzvazbdmw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtiglcgdmg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtxfvqivtr.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gthgivigqk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtzempxvfk.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtgliklthh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrxfbggsh.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtilkebggk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtkirbcmzr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtwdmrsurk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtibeliaoe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtaktfbxwz.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwdlwjeuk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzsikvkn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtvlkgdccg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtoldhtulp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtqhmkcyka.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtssmjcibn.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtiuxidayz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtlporcghv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxqrtptvj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnhmzdmgf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gttruecbpg.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtqgfsfdnh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwasuxkir.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtqjwtvlki.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtpiarilpj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtnuyobmvo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtsxjgmnrf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxgyirhw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtlzxogiot.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtpoewdphm.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtredbjnyg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtjenfuuoq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtsrlhicci.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtepkxlroo.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtamnlppbf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtkvhoiafl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtmxtcwthf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtgbejbyty.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gttpvctcej.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqtnitodd.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtsknebmnc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtocitcssg.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtztzusxji.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtuyznmuwi.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtzclnyapv.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtogskfbrx.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtttfttfry.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtantvozhi.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtoxcddmnn.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtdrphkdoo.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtrvrmdjpo.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gtntmcdzgm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtmoqrgysx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtwblurkia.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtuqqrczzl.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtgrfmrtsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gthwnjazsj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtoxjatsnu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtraxzlras.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjypgvdnb.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtftlvrobz.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtgiqtuvmh.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtgcgckxbm.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtowhjajdw.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtunjolyqt.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtkinovhvh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtnjcgvlpf.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtkrltgosw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtqeuxspbn.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtdungzbty.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtfjcvnqoq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtxllcutsc.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtbdcsgear.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtztmowsoi.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtwubmvjhn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtzfmnmemv.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtripozkxz.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtlihxrmtw.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtpqwcrtfs.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtbwdiqisv.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtkvzdhuyg.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtecvhkckw.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtidweykav.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtubbbuoio.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtdhqpxsil.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gttanbzwsu.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtxjeyfszx.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtyhotodsd.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtztvykvyb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtpvgrpcaq.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtxrskqvwm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtafwgjeyv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtjcjclbfq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gttdsirgpw.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtlawpxfcb.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gttowtohfx.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtgofbodxt.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtvncqajkd.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtevhdqszo.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtdmsajsht.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gttqfvkkqe.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtkjzcsclx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gthfewsakf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtkevqryuj.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gteztikblo.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtsmtpxaxi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtoczoikct.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtcpwjnnyp.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtbtbsydrr.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtlzckyufh.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtnknkaxnj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtpmnncofo.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtkywhncnz.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtrvvekazs.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtlkxhqyip.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtlsbhbrwj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbxspijgq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtimsbuvgi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtojifhfml.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtcvrgzqrb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtfnsrhzzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtvqgdmvdb.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtjvyvxfjx.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtldjwcdbs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtpkndlyht.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtherboiru.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtwjqdixmd.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtuuaasryx.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtkefxshsv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtkvjbfhez.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtutdjfmhv.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtrwxvrtys.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtqdratbtn.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtmbajnbqw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtvgfybdtj.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtlnvofrnw.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtjzutmlrw.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtyfhpiyxp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtpejfopzj.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtyujupaqa.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtcnmnmmpw.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtvkpkilqg.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtljiqbiqd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtwuabmyyg.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtbhpdanjn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcjygilkj.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtrpnlubpx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylearblx.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtrjqcoxxj.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtzvkwgxpx.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtfcrlcpqc.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtubdvahor.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtuwrivijt.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtsbkyxupw.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriswrxtm.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtubymnjgk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtvchsuywc.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtwxsgfjxp.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtwyzqzbgz.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtrkpvzrvb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtcgtwbcrr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gtsoezccoe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtfpgcrrvv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtljsjkmel.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtgvzakktc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtiiigtfsb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtouthjina.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtekddicin.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtpwttwhvd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtaxezqyaq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtgbfaxnux.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gthvgrnmco.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtnaevhhoi.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtmepmuznx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtreetjtev.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtbxexmxfp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtziuvrrer.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtafzfvuva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtabyzftgv.html


<!-- 参考信息 -->