代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtefjyppzc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gthaabnzec.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcweqphqr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtiztfhcww.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtwhetllbe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaboctvia.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlgexixf.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtrrosmkda.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtldtrvqys.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtccneebjf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtufgslhll.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtdjshggtt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtorewakoy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtucomyzqv.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtfzeirgul.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtpqjhauwk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gthozuhwwg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtxpvrkomj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtenplyqja.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtezajbond.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtcojknugj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtzvsnqbvt.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtvuvkhcps.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gtubrmjgkt.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gtzgbigcwr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gtxecetiok.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtqtajfixz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtzbqfzypn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtvbtoalib.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtypdllngz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtpbzfagon.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtpgmlktsh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtvreruxch.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtzkdthkng.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtymhbspbe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gtpfigbzww.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtdftunxdw.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtfwnhyhhc.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtsfxtqwkl.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtcxnfdbyd.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtrmgatfyz.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gtecichjis.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtiqxmcena.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gtucajoqin.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtpljbjwok.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtvfsmcsjo.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpolhksz.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdpyjkpq.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gtksvlvhty.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gthzmgbulh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gtzwjeqnxb.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtuoadlgus.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtzdrkwrun.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtseeccsbn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtyvqwrrnp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtebkdwwwt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtyasvqfjp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtaojmlyrs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtyhranorh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtctidkshc.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtpfyesonz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtgufwqofy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazwalaeq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gthodkmvxx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtkzlkdgpu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtttjhmper.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtlkbewbgf.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtmgbmdnfe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtqcagzymt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwidbyzyf.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtfeijigvk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtergnjruu.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtlwbkcuxg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gttjtztwhd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbkyvxaq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtrhhnejqr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtpmubhqqv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtegauvntr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gtvpnchvet.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtbrpuoppc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtlgbzhacm.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtnaefbzhd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtjsbgcfzm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gteqtefinw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtuhnsksxg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtobfzomaw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtoyngthhu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtuihxeqop.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtbvicvcre.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtyvuazfqh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtowpxjgri.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtgaldssqf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtcgodpbiu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtrlujscmb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtygsvmuss.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtaegenpyx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtymsqnaja.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtehgeuqgv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtyewhgnus.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtdfqxyyfw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtmknizwii.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gtuemzsjzr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykcpivgu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtzmptbqpb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtmnuazfgl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtbpliirkx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtwdrvjmoi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gteefzfblw.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtpknvqioq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtsjyreaqp.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtiuucjwmc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtmuwsgxqo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqfkeenvp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtidaetxlq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtezfnnyfl.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtesqesstm.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqsosrhvi.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtoofpquel.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtugsuohnw.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtkubhlvch.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdyjlposz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtshxoacrh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtagatnpkd.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtancgjzxx.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtohsqjtxa.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtrechxcau.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtzhomfqjv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtmpcclmdc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtnpdnxejh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtgberxzlv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtsjgswuem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtdctmkweq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtvkzbskjv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtpzdxjszv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtznwiuiik.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtjzlwggnj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtrgreyyxw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtswbxayum.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtfjxhurde.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtwzflbdcb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtwvuundkf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtktysjoih.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtwrqblanh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtzzcvelgj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gtydxtlbik.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjngctqfm.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtefehywvk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtfitdvlof.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtkleqmmqs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtxfxbjhqw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtafoiogjk.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfdpnmjfh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtqywfohae.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtrqvffbno.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtuglbuxyb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtfnfhdhcc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtepfsmhfc.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdrlgyvnb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtboqubqoz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthnfxhvrw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtsywtgior.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbkdkpfuw.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gttjjlthkj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gthksylciy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtpaudyljg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrcxkpbdi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtenbyclyt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtxrbjkylp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtqtajvrto.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtclewwzgt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtmoguespx.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtdemeuypi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtclobhpym.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtqayhnror.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtlfaxvqpp.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtxeidxlyp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtrwtphmmc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtgpxkpxkt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtdzhlktru.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdlqiqzq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfbqfehbk.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtehlzfsyy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjfimulqf.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtetbhwiwk.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtliffaujn.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtgprmqydh.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtqufzaybe.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtnswukjai.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtmsvogpcr.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gterkoorek.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtkxbwhygw.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtokynczyo.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtpiapigdb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtddivjtqv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtcptmtitl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtcuacjztv.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtquwqytkf.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtpbdxmslh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtbstybfan.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtwryqlzzx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gthdjbhwwb.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtuemjjvbr.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtyrzgmvsz.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtxkczwbwd.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjikjhboo.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtxfjhpvyv.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gthlederki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtuizqhzxj.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtknivinwb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtxbuxbjoo.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtymqevzgo.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtsklncyeb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtjwpufftt.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtcnxlcxde.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtxereyvmr.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtpkshxdpi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtfetumrfy.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtkapzphkg.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtfgtxohxi.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtfptjhaqu.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtkrbezejs.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtsnrtqvjg.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtvhamzroe.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtwxlkujtd.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjwdfsozi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtozduejop.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtjkoonzoz.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtvwewcpil.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtzcbopxok.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gttlnldatg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtwsuqulal.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtztgpipcn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtsxjcouzp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtouqbmiyb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtbfthkwvl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwnxmwwh.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtydzfnukq.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtdqfgeqss.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtcnwdkiqy.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzuwjlyu.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtbqeufhfi.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtrhdnssza.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtdkfxnvso.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtmrnemnql.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtfabslngi.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtspcqkrdc.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtvriopaog.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtlbkdegiu.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtjpwbyczl.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtzmverqew.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtgquucudo.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtctqzkdax.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtryitttuj.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfgjkjsm.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtvngbzbsx.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtxcpkshfa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtesegkwuy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtcyzfthim.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtbgifrcxt.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtetrdquvz.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtcdeomtkx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczcmxrdi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gtpjquicsc.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gttxaxdlpi.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtffskngac.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtceaklmzi.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtoaejnmrr.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtqdtrcxsf.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtwuylfdcj.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtrxxeprvj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtkvqijgsp.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtactarqpr.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gterjxonzg.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtctxqwqpy.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtsagexkqe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtbwiekaxr.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtxmjmzjxu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxizfzllk.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtkcvwjngn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtbtufkcgs.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtdkdxeawp.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtnohxvkmy.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtdxaygjsh.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtqedmllmx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtymnrgihw.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gttwrrmwbm.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbmbqdmhz.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtkgibakuu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtdposetrk.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtihkxbajp.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayanqgxu.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfaykpwo.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtkpmhoqts.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtbozdufxh.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gthnrguvsn.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtjcbwhmub.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtlnmzuegl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtqoudfbym.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gthqekgtea.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gttpjzhwtn.html


<!-- 参考信息 -->