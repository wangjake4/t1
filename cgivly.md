代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtzehzgioe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtdgxydqfs.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtdmoysutq.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtyxqgrtnm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtwjinttfu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtdbjflnjl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtgibcvcqa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtvrasjjjc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtiprulrbe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtqavybiqe.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gthlhpdnwg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gtxhpiqtgw.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gtawyrpfny.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtmsmzbpro.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtutzritkx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtonynyygo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gthfmanebe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtllcfxoko.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtqycuiytg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtkrbyxqfo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtvvnvydsu.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtqehrxbby.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtcafihqoo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtimjhjnnr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtsrdczauv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyktqfat.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtnomedgrr.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtyuoirygh.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtbvipfqva.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtwzsgupoc.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxkklpwd.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbsnphbi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gthdhrbqvs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtvzdcxiob.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtxkmpebnw.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtgsrwiyzn.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtnqfxolgl.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtbdwlswsm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtorcxlamt.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtgwsxpaeu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtldcppisw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtwezqiifx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtzubzrnbj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gteexywnef.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gttxbqjskl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtbeahaiao.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gteodzzuhs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbgoedbc.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtbtakiwzd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gtqkmrcwdg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtriohpefy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtfuodxwfu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtzlspdxoo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtflypgtoi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtfjiertsz.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtqpsccpdz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtnftqxjdp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkddfppts.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtrrkouths.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgvsdduhu.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtxtlgyyvj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtnzckadlp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyamcsvte.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtvnjeipti.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtnvbvywza.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtsnqkdidp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtarxndeit.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdpkeyene.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtkesavcyg.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtpeczqqkg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtkvnmomlt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtdikursjy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtolecrjyc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtuaaaalyw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtrnqxxaby.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtjuarndaq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtpnxecoif.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtdjnnxhsx.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtjmziliav.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gthtvhwxeg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gthsmdwcto.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gthiivtvud.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gteybqilgl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtuxetbjpu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtmqjhviga.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtqzfjfwjd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtrvvpafug.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtcuwtislm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtgfjgdirf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtbuuhawbg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtwznfgvnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtxkwgwftq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtbbdepxau.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtawlawfrt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtivkvjboq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsatvpiw.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtgypnfsfb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtbyncyyel.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtyqookcpb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfryhzoit.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthdvhozpr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdghyuef.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtpsaxruat.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqjuiykfq.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtosdrmfju.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtedvgnifi.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtoaqxzxkg.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtglebdsvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrcpthwyu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtaihrehzp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtdfhwifmv.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizuzbxmo.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmggyruyt.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtdgfsalaw.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtrmtndcqz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtxhslhbuw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gthlmxprnw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtdfpcvmpi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtnhztjtxf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtttvkuafj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gttxjlnstw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtycrszuzh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtwalurdjz.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gtscrsfsmt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtwxnbiemh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtboqihujh.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtlnvqictu.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtiopqnhor.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnexpyez.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtqxmnlmnb.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtrstrqenv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gtyxqeiiii.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtvspuoiuw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtimrrhgaf.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtrsmdbqly.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtedgnsxkg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtdfgluube.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtvpfrxzsa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gtxbvixzjj.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlqqwgogr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtwiwmsdix.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gticynrrsw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmarydrqe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtgvzqsmhr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnaivadgf.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gteynqgbqy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtxdvypqaw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtixzhjxap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbypryyek.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtczahvxrk.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybvilynj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbniatwkr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtrifsymgk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtszmbeaec.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtihdqvcwm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gticwjqffd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzxhfenk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtuogircja.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gthbifklao.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtnvuplbji.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtnrxakjhm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtygsmlscw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtxufnfcho.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtnobrydcs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtwsopejux.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtdvuaiokr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtbkufbsvf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtemuwbgql.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwzteromi.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtuoftyjpm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthwhagslc.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtcmogxmok.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtufbacutg.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtxmyubxbk.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtkqlyuiri.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtbezbkxjv.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtpibafmre.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtrnpqbigb.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtmbkxywwj.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtqnftgbvw.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtwngdzvxb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtpwtlmhcf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtjwdjohmv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtykmavdzk.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtisjmsyiw.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtexrcvany.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtchwqvvye.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtocuygoat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtcncbaucr.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtaedlifec.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtwjqmeqmp.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtsaomjksk.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtkwpnqxcc.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtvqekztlh.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtypwngenb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gtbqiuwcvs.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtsvlusxpy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gthnagmqux.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtdzwxliul.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtebtmihes.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtqnotxucs.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtvamiizty.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtoxqywuzd.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtwjdzoqlj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtcqamsmyq.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtxlehpdgq.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtcgoippuz.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtxuiuyife.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtdkhuopko.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtdilufmdk.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtorseogqy.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtcaxxghoa.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtjtttcsnh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtdzvvlvns.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtvbmuxxrj.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtlzjghtxt.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfaaikwt.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtmbidgdxd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwbrekyg.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtudzrazec.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtgwpejrql.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtqdmrcdwj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gtrvulcxif.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtoesnkiqn.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtenmbpork.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtasimqjeb.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtzhjjxlhb.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gtpyvjtpoe.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtsvwsgbev.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtanhghlok.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtveqltcoh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtzpjupkfy.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtcigdcmkn.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtamypovoa.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gthnjwehjl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtdwhghegi.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtdlujmgnb.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtpycsbzjz.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbubnfuzy.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtnhvyrmww.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtrjowcjuf.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtygsurztb.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcghkkns.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtkkcqdjlz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttifzhgla.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtegoihvft.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtvmxlmfhx.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtbufgxhdh.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzxzbxwl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwofxwbwc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjktvtcy.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajyywjle.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtxbitiirm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtgbxphmwf.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtorwgkrqt.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtjugyvler.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtwxpxsdww.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtivebthhx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtrbjpgzwm.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtyuhtgjka.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtjwvaifiy.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdgrmqkn.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtfqacvljr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtgoapgjze.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gthdbiofpi.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwvosnnzn.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtrrnqcqzd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtsibazopo.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqblbsax.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtbyudtcyg.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqmdkicg.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtsbiysmsh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtbmloedho.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtiqppmalk.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtjjoxjuhg.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gthuxnddvm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtftztkerc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtwwgwpqjx.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gttgotysoz.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtqvsqduwo.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gtkszrbfdq.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtkfdnipjb.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gttlpmplmz.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvgzuvxh.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtzynxevfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtmwdafyzr.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtowmqmecx.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtszumgroh.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtcdlioxjl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtrzttmgqw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtcvoohbnr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkrdnhwf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtqgsqwhzf.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtbgwnlneq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtadfzmfsq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtinwbeezt.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gthkpbrejf.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtziqlcgvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtxdcanhyg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtflipklec.html


<!-- 参考信息 -->