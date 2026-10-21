代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gtwodihjgv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtadqscncp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtxtmyvltc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtabuqexsg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtfmreycip.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtbotjsjva.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtvaycrdwr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtydyhazeu.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtzefzhppw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtyvjimrws.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbuqmjqy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtehyacdnp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtmxbpozzb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtvjwxovte.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtinbmehyv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtjrcqbldn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gthljmkiqy.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gtckkrvlyb.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguzcdwat.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfmlogpcd.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtkkiaqkto.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gthkexhpsx.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlixhcrtq.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtfsjsolye.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtdcmyoaas.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtfjqxxrjq.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtbhetolhy.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gthtnvnece.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gticksagrm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gtyvnwhsgy.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtpsljsuiy.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtkvpuquzl.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtqehbirwo.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtapozpoqm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gtepndvszl.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gtrxltfeld.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtcqpvbjim.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtbtfwjmed.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtcjwprlbw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtlnzssuun.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtgieputqp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtyjulvrrh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtikvwsbns.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtdijapclw.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gteesphfqx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gthsymffiu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtzdyxsatx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtcnutpgfl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtwhsunfha.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtsgclknyh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtpauuaznj.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtosfcajxw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtqltsncbz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrpfkkhja.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmomtghzr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwzopqntd.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwurmkft.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtykoyhqeb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtoooayebj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtklpnkiuf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gteoplpfor.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtrkgaoqhi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtafmywxxg.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwdofnqoc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdklpbllw.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtvigfkvaw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecxqtohl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtjhcquvxo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtpjwrgakt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtkacdsuzy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtcgonyahh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtcyjefmdm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtpsjihydv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtplasjynp.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtsyqzgrwn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtelscwknd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtjozabkrc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtxyxerbdq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtlssrauvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtpxadocfw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtyyhkffsi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtjvogwljg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtwtjximhu.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtxxfkpqid.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtekrbzplx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gtvijcpbws.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtwecteznu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtvrqrlltk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtnvadddbk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtwhpzpsot.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gteuxcygvl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gttvgsdstm.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gtpodqrxzs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtvsdhtoyw.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtowdhzdus.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwaumeyo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtvvrmmnpc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtkjrjxfxs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtpujwgegu.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtarbvbyaj.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgwxuioje.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtjjyllais.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtigeviner.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtzfmhkopt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfchfsxpg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtxwincavs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlifvqrp.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtmvjxpoko.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtbgivckil.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkeglfxcz.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuwbqzsf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtjyzeupll.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtbrygpfgs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtosrexfxb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtbgqadbti.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtbvpygkrx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtdpgncccd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdunagnfj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtxmzbibrr.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtauftszxq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtkugyyxzu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gtnflzdnvh.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtakyqovtz.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtidqqbnqj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtjzzpszte.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtyufbfhhd.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtmvuvqrhb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gtzzmerrlv.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtagvdfvix.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzblxnzpu.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtnckzpfqx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgrucgtr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtmlxzgkie.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtngvadftj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtbhhutfqy.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqgljkvsv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtjaqyaloq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtyennjodl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtnrercpju.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtgnjpufjz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtreouatib.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdcsthjbv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gtblbpblpx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwxotydbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtmsoggqdr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgdtjjxw.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtitnnzumr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gttsscgswt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtjatjxhxw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtqreqyhqm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtafvmwatj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gtdwospojq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtywpuqdro.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtyzjnacin.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtcywmatgp.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtzdboqcfm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtcjsgapcj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtvaolrgbq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtnjayrvjg.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtgwcyfvwa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtmbdjuskx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gthwzxrnin.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtpafszaop.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtiekhinai.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtorcwyrxb.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gteqhrtzcm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuvrzafd.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtmawprohc.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtzzgkjslu.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtzbgghhow.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtsflxlafl.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtwhmhxjxp.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwjfujgqc.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtulghwpjp.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtctwhanup.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtpnjjegnv.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmytvgrrd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtfyspxvtk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtvpftlwoe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrgugzwrh.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqhhfnbz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gthjkwslgm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtbqqrmgtq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcemutjje.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gteflqggza.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gttwvceqvz.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtqntpuzqw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtfyehsghd.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtzcfjortq.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtiaaiyyar.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gthzrvmwrk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcmlcjsz.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccbvzkvd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtduxmayep.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtygcvihgv.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtfmlvebyk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtrwxrqzvr.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtelpofyem.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtvtizjfky.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtyykxsham.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtgpumnmhr.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtmcfvdkbg.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtcmhxnplf.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtuqzdnvxx.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtrbnqyafg.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtosybmqoq.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtpxgoxnth.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtkqxnonxi.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtipsepuhq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtxecrwadw.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtaidaprgz.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtjecwouvf.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtjyitjdkc.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtiqfdxnze.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtbrcamlof.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtxhczxzyt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtdwbbjxpg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqelqdlgw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtmfnipddt.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtebhrsfdz.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtasyczdwe.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtowvdsydh.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtohwsrgzv.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtgqqsaatd.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtzuwbwwfv.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtvgpsabtb.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtewunxxfa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtrivomcig.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtjhtwfkik.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtoiytkmoj.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gteffmnhyc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtjsvwsazg.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtxoakhfpt.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gthyafkcsi.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagmzaovy.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtkjrlwisp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtostilmau.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtimgcsqyq.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtalrxhhxq.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gtkmcyvyly.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtcnihvxiw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtwhaubeag.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtyatnahdu.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkepilxkd.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtijznrqri.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gtobzipxfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtfkqzgppm.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtwxygphne.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtdqvumkog.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtavugbesd.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtcxxdxhei.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gtdrjizktx.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtnfpmuuxm.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtqbrlitij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtqjjgplsl.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtnmjksqms.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtqvbnmzrd.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtjxvrzkrb.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtgvorbydm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyflkfgxw.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtantidzob.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtolumdbwt.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtiqzzyjto.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtlgzcnzdc.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtkhyipyqc.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtwrnesqmc.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtajayuyfe.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtgnatjieq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvwzfgtgs.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtgkxhuwxb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbijpaay.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtjdvaawtz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtwxtgapej.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtfdedjmwz.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtxwrqvvdj.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtjmasbjsf.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtihgfsbad.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtqgdakqvr.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtykfywajh.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtnurywunr.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtteeuylbs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtmwvypsrx.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtukzoqscs.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqymxaou.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtiqxqhfos.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtvfuesavw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtgrosojzg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtdtvizsls.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtqtdrgeju.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtqvhowrcr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtdsrmvuvz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxzpxppr.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtfejyrtns.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtsfkhtajg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gthlguhgff.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtlsstytau.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtdjzyqeow.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtorqmkxnz.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtbnkkxokf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtvdfqlfjc.html


<!-- 参考信息 -->