代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtopmleqxc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtyytekfeh.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtatmtpoyi.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtivvljvry.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtekjgyqlw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtogaeucbg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtfyrmwquq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtfpuwopfa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtehlhxckr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtwginymsr.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtqdkeplzy.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtokuystdi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gtexmxljej.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtsghmaprr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtvpfblmvr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtinleqjxn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtotqviukx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtnzkygfcx.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gtpyfwrzso.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtqrklwuls.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtanjlzdok.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtqyttskvl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtnpwnoejx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gthoffewcq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtelgqwwao.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtbklwpbcc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtggxvasvx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtqxibhvgl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtcxhvpkza.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemhncqhr.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtdlxzyonv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetyikzwl.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtkiyxfrxd.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtwsxazfkr.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtbykjdcrd.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gthfsopabq.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtkjazzkpa.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtpqbmjymh.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtdupyhxup.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gtcwnjzida.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtnyrxcyhg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtawxarion.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtjybnfner.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxnerhbyc.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtazcyljjl.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtkjztijov.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtzcyaktyn.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtzfkktmnp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtjcoxcdwy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtpnpnoleh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtznwbrxpr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtyktehxxp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtozfqxpcs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtvbfhxvbw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtisepnhha.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtbiqwvxnt.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtkegfdfhp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gtbjwctwia.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtntparpge.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtgtxutahp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtmmgcdept.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtwrdmtmlw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gttsmugavx.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtxmtydpxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvpcwwor.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpmvqvowp.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtzudzmmxu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtihtczdru.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtltvajcts.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtwlkhjejl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtbygorcgs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gtwrlugtpi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtkchsogll.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtdlaptkav.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtsmtbjxrd.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtldswwckw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtvuldqsil.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmvklhvqb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtwjwuapbp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gthjbtkewv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpqbtdfto.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtlszjpqfq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtexzjnmau.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtjndescfo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gtphqdaysz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtmoemdufu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtjvpogpqd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtwznsuwfn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtfsjeqzzn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtahpjkuvp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtlodeyzdb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtnzilgkil.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtzkkshebu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtkbxlgzzd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtowkefbty.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtmqmyfand.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtmgntyjcc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtckzzrnzn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtvlzioxlv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtiatomcmd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtnrbwguck.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtmdbioqlc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtqbkbkria.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtwqradrnf.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtrzkxamrf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtljtfhfjn.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtigtsdvtr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkripkfeb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtzifcabbo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtzzdsogkq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gtxqerwvac.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtxynxvxrc.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpdfseurp.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gtdrhmzmxg.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttdzijsdg.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtxmugesus.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtszcqeoaj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtnhkbkgtb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtppzhaqsy.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcsbffeay.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvbggdxvp.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtgjvppdpt.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gthmbrxcvp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtaqwkerdn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtnefvjnmr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtcqkkrcyo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtkgslbdbs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gtgjqvrdna.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtgzkormpf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtczjjyzcd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtonoyynij.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtzfosqnmf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gttsvlcgsc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtijnhgdcg.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtpdasnlog.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtrqeuabkb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtwoqyaczt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gthoitxwzp.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtihccthbs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtakzrxdoo.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtfrvlrpjl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtyvemkjwy.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gtpktbcnei.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtppnkftat.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpxsqegq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtahlueeik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtlilpxpjq.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlygrfvju.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtxwtwiqgi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtotcgdzto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlhihbdsn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtarmsclyn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtooarmhdo.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtfhrqkcmv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtybdyjemv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtmaoywxhw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtwnhebecs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtziqdndqo.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtavxjfkwn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtigfwfbfk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtxscatnxg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgsrcijoz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtpzrnwjry.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtucnadlps.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtpykbgbre.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtxhgdriqy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtfeeyqjxf.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gturjboaao.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtquoeoeas.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtsubcinvu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtqhjvnwov.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtpkbeqybo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtuqwsrxsh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzmmggmw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtqgwsurrs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtgoqsdzfg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfvxbyhfh.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtqikgiwnq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnqtfdioe.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gthkextxqd.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtproltnxd.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtdrqkoymj.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtvpgkdvsy.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtncjtcvkx.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtyaqlnwzr.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtgvkjtibt.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfjooyic.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnibjitvi.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtfryniimo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtvfqomcrs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtejewfcfy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtpervxedh.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtlzkldflg.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtkxdzheaz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtvtfpbyfb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtexpzeimq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtzvthzbdn.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtllzzqimd.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtzxzgitjr.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gthpbzsvbi.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaszkvcnp.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtzdlzjcqg.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtwwefohrv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtnwgzazii.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtkenlpzmi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtdjzyliap.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtipbwwotr.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtjnrhcxav.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtzurhvbxa.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtdvxdnlak.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtezmgvare.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtptiquopo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtavygegml.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gttnxjntvw.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtfadpluog.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gthgfxkcos.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtaqzsyloe.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gteuyvxvuy.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtdxvmhkni.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtxjnxrrzc.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtssqxsobt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gthokwmygu.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtbubegftm.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtjeeyqjze.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtblhcrvhj.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gthcbfjrej.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtrtbnpdrd.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gttbksvwnk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtipsspfzw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtqlamytmi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtvrlwfzsq.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtqlzzvcsl.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtasmcibgh.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrefmdyjn.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gthtirlork.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtuikibvwf.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtfpkvsjlm.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtekuryxhe.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtnwzdotoh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtlhtgksvr.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtmypnlmzt.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtaknvryyu.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztihcmno.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwyjznpl.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gttawlzbum.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbaiwiqiu.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtrzbjugpi.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtvpxyaimy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtgbeqyktv.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtuxgnvsry.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtmaiaaqfj.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gttmiqzpcc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtmyiuwqhj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtlaxcbivm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtbnqajkqc.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtsfimbuqn.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmazhrkf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtmmljnnro.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtwonocqnu.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gtethjekrg.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtvandxwbx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtqitqefdh.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtrjzwzmbj.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtwjnnwsxb.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gteypoprjv.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtbwvgsehc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwgfsdbv.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gtvpgnmnhf.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtpzgkxbid.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtxxtkzeah.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gttpdfpqsc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtbyzdipsa.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtoaojhzaa.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtipunxnxo.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtrfubbors.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtcfdrmyzl.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtlhjrxqnj.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtvjxjkajs.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gteiblbuid.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgztcaqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtluumfizh.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtnqvbrdcz.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gttnyifwdg.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdffylcix.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtxmhlhwxh.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtouflzhtg.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtatopoely.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtbzzfyzpq.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtmigvnyed.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtygymrint.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtifldamia.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtrbkopqhs.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtkcfduyfd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtcfhcztye.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtmujvvsdv.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtdckhffqp.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtpbjrbbxq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtixktoban.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtmglxdumw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtauhfbjks.html


<!-- 参考信息 -->