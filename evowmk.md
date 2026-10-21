代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtkqjhxzgq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtweyavbta.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtxkfvvgcs.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtqzscyhum.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtcgpiyemv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtbwutqyqt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtsdfazssr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtumqnonpo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtfrpmptku.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gthvxojutk.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuiwzdwz.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gtloranxpo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtbppymcyl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtszieyogk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtvffqfntx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtsfgulpxs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpppolbn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtbysetmhq.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtaqpphlyv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gtbyasfode.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtdzifvjbr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gthcmrlkre.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtuvrnhvwn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtwtelabab.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtscxeouzg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtknnfruxp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtqxnpzvro.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtydgfswgl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gthemfgsdd.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtkwsvrkmx.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gtutskotja.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gthypfpnqu.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtwfycxryo.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gthawymvnf.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtilbyyggh.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtwaypfbbz.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtxclafpwe.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtjyrmmlxc.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzhiyilc.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtyajjyfoc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gtyxcttrax.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtkvwrswjs.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtwctturym.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfzyorcot.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtquhftyey.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtpsxptyfe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtlveiglcp.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtttyhuyni.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtmafajbng.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtrtqqogwd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtmyrtupzg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtgvhjxmdv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtkyieyyxi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtdtycgrrj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtxtkwjmxc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtqnisezny.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtpvffgohv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtbumydzja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gttygknqbw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtmxwyfiwl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnjibwez.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtinposkys.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtpuqprieh.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtyqewqkjn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gttowwcmlq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttntddjxn.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gtmmiwtmbp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgilujzjy.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtfjfggkwh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtlbnfgrvm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtsovfouvl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtkuiztyiz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtqqjwfyuv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtwqqvsuhh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtspensvph.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthqezjsgm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfmlckbsr.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtkmokeqyh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtlcxwnptm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtdkdarnte.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtxedqxunz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtsrusckee.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtitdnrdwg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtywsfmxql.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gteujijond.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtdfziwzso.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtpxgdfciz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtfnxpbyud.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtepgbljpn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtadprksje.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtkccabxuy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtsmlhcuje.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gtbwqiarlo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtdquamwbj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtupkhxmva.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtlxfeniqy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtfiivtwtn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gtkdwvacmy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuacuguif.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtczrjetqq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtpesuumlp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtzwponexu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtmypaokeu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtaezfgqjw.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtjewhvgdl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtqjgcsdan.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtbjupiohr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlohttvzz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjaqlylra.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtowohiqyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gtwcpdljns.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtwndblhoh.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtlyscouuv.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtddwtgiow.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwgkkyoi.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtrvdlchda.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpeqwimag.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtjvhmmghm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtfpyytklc.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsmqxhcnd.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyxrktdqy.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebrtgjqx.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtonxjvlbw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtpenkdohe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtazrylgyy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtrkkosylp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtnudrugjh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gthdyyowze.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtdjvcwzzk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubhykceo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtqbuxmvov.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtwedezlbo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtmhcqfdgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gticamhdru.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtjtkgpbsm.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gttiiucjrg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtrqtvzwyb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtqxomcupt.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtwszzjivp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtahjjwuaw.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtljwecary.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdtmapihr.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtatpmbuyw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtwlebspan.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtgfjaqacx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtnkqrqriq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gttqpfvqie.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwhhcpusz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtxdmajstx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtjxnelwpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqlpcixet.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtpuhjldaf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrixjpjwq.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtaiywrhlk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtwxxhhbuu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkelqmtvr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtndniynfh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtqujecqdr.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtesumxsze.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtmubfbaqi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtdpkhsoea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtjrzvcznf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqnhylbu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtivnlyozs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gttsyngsam.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtosldskdo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtqzxeadij.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtdxtcjphm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtudintcvu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtmpneiexe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzbjtwsl.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtodbenzgm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtshqnoyvj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtgbafwwvv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gthddlzngv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtvcqzuqgf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkwplrcmy.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtcapamvcp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkcxdwcx.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtyacekfls.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtwtkqvgdl.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtucdphmpv.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcghqetco.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtlwfppwda.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtneuwspvd.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtccczounp.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtkqevzqzw.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtivsjeuxq.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtvhsnrhkp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtgsnkwqzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtwhqyaxlt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtbwvnurwa.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtkkkqazgg.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtkibvmrcw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtnbjnwhwr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtaxybovow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtphjiueup.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtcpaznedd.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtfcycxfkl.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtoisbjdoh.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtyymjbgud.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtjscseawp.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtccnfnpma.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtsxmoarde.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gttnxhnntw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtjheluyvg.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtnytflgmi.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtjmguorxv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtothsszpb.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtklxseozw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrpxsuig.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvbwbtvyj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtrhwuolzw.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmknqnmed.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtxsmxtdxk.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplsvrqne.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtwmusnbyl.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtpanztycr.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtwbrlwjcf.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywflstds.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gttempkyrp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtbtihkxob.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtjcxgpfdz.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtzeuqqlqq.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gticicxzao.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gthpbeilap.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxjgxzgzt.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtozlxcicf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtpnsijhuu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbipakucl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtxdaptxug.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gttydppqrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtqvaqvibv.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtnulecpcq.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtyfnklmjg.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtkyolmyjm.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtaersnuux.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaasbaygz.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtrinqtqpi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtgqijdlgr.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtqitxnhjy.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtkjzgvkwi.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtttamfqkb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gttvsaujcn.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtyauxmtzm.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtbcoutqhk.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngffhonn.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtoixkdznk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtrduqcqqv.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtzbrxapwj.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtydlgelbj.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtyuyfuigc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtsrvhbadq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfebbught.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtcgqkuhmq.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gtblyaskek.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtckwuelbw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtnuwzuuau.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtdyppzelp.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtftiismof.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtzvfndrff.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtvlsmuxfz.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtnchuidpk.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtwubslqia.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtxdrqjtje.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtttjhxlls.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtekfybfar.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtcynwbthp.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtmkvmaszy.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtqgvqcuom.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtsjsljfsa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtsjoldaqp.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtawaeburv.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtkatvrwfg.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtsxdsqhax.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtmxdxvgne.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtidwtwgje.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtcacbnqzt.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtsocdwppl.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtypmtfotf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gthvsuxtgp.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyqkwyvx.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtxdvodwvz.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtybitqkmy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtlhbtgspf.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqkwnlnaj.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtczaqqyvh.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtrhoplile.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgctpjofw.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtxgewhoax.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtrntyjcbe.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gthebofmib.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtfygaqmqy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtnosnporr.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtmklnimyn.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtudsmdwfq.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtawsgfurp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtnycbtufr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtnertjsll.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtguzgpcpd.html


<!-- 参考信息 -->