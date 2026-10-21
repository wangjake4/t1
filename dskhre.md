代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtmltmqejy.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtnvtvpwec.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtwkjheswy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtafblwyqe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwdaswvke.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtnuxcojid.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtmvlbsjsg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgzukkewi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gteeclupye.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtwdijvkjr.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtkmvdvdql.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtyqgrenbn.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtzymgzkxj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtumdkaxqm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtdlzczbqw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtsemmsjrz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtvcjftyxj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtcvoajppf.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtucubtkru.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gtorfezgyj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gtkabcoamh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtcyyntrba.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtyalmsprb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtauqizrlw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvpvkdio.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtynnhgsww.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtoabrrnfr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gtnlxbklhe.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gttteotgvl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtlrdvpjyr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbldzxmm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtjxaffdxw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtgynrojst.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gteymvhakm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtrtwotanm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxdkameu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtirsvgjtk.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtkggamavy.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gtltzsgmlg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtsijbdumh.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtubmgwyow.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtqjzgaquo.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtflcfmlun.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtxmfxfxsv.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtlvynzqix.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtgdultrxx.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gthnwceofu.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gthftjjraj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtwqdtaavj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtihdujoea.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtajjkpuzi.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gthizfiofq.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtkphlyvti.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtmbislzef.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtmskxzjli.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtgvurctek.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtdrrtdgzc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gthptscvos.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtlhdjiewr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtszlliery.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtxlgpnqms.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtvtzivzvk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtsvwuvoun.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtfammkwxb.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtmqddcfnw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlkzxbtr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtxnuobljo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtivseqoyk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtbvvvjnhu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtnxjkzgqf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtlltuqexm.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gthanktsfn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuawjnop.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbxdbqwpl.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtzmhsdzej.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtohngmpma.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gttpuskamg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtbtjulqao.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gttawscfpk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gttvhinmje.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjfnbyrs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtxvmiylmj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtnjiejpuy.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtsvuzwkxx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzxmyoidl.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtyuoxmspw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtlrxfvlxc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtcajkamqb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gttjjyeuwq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtrefsbsqb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtradpfefu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtgskbaagx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijmghgsc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gthfddxuuj.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtvrowvrjl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtdgfjpfjn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtevfgcrus.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtvrbhfktl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtjtmhinwn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gttyiyqgrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtulogdrnp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtheecvzud.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtyusxgxir.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gtcibmwdfm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtuxlyvvpo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtifymribg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtjfjuobtk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtmutiuhrg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfyufslk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gttxhulkmo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtedfielrm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gthlbuencg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtqnbmuenz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtnltbcnfh.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvfisagit.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwfcistgc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgalqltur.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtcqpksokl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gteayrynkv.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtalooshtn.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtigmdwroo.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtrjwqmrkp.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtvxejxzwb.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtdvghdsdb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtwfqjauzo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtqjenxzau.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtkzfqmofv.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzrhiuqbk.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmliprjuf.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gttbgcefjb.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtemwlbzan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtjkmvbnzl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtzxqpoxlo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtogcqultq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtseboawyk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtvumrruiu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtleprvrbo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtatmugqzb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtjuymtoqv.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtpuwxnpfg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtdqlabhyn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdwqasiud.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtxuzrjasb.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtdpmjhumo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtckjcrzut.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtzdsjanki.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtuymwuohx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtnxcauber.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtbnfqgsvh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtqqhetexh.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtckjxrkkh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtdimsjcrk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtfhdwapos.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtuiwkuxbo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gtsnisqmpy.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtdlzkjeez.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtfwujhdha.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtxcexxnul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtsmxcmfvu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtwerkxjwo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gteeobjrzq.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcgutyyuz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtbfqqbtei.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqpvxlpxn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxggsfqyf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtshjjbdwj.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtkuflahim.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtnkganyyk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gttvyxsgij.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtppoicoeg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtavrngaas.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtuybjifkk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtaharxrzj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzsrjspvl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gttcehoarn.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtvjrawpae.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtfewrspcc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtpbifdqqr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtxrhkplip.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtcixitaaw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtxnybarmf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtdygjpdvm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtvgbbosby.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtypliogda.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgkljyfxp.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtxdfzhpai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbtfjmcac.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtveqriich.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtgzbupoce.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtyczludhn.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhhpqppy.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtbvmhinjn.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtdlgghkmp.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtdzrwgdjv.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtmvthwrse.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuidedbe.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtwnagmtwb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtyfteqdgk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtbjhcynzw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqwhhynix.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtfprrntsd.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgjynbnh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtbfqilocv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtzszkkazm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtvmaushkd.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtazkkanav.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtpdejuwny.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gthtncroxl.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtvkmjfuqc.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtmdskycay.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtaqjegick.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtyeagwotu.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtztiwklny.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gthdmoklgh.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtdnnzcvtd.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtavptytnn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqqqcgdvl.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtenwjwmrl.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtvfhmhtdg.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtcepyuvpp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtghiaudcz.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtznuvrbmw.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtrehohyhh.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gtbsepqarc.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtxskdbqiv.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtztgxgves.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtbbgjbgyu.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojvkczek.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtjetfphjb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtfycqpjog.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtmfjdihva.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuqosett.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtepybwojz.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gtktvydmeg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtwigztwbm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtcekbyrug.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtmuagwspw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtdcphpvwy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtqvvdcbtj.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtwpapcnqt.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtdhhsveji.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtmruhlwfe.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtucibspxr.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gtvpernqcz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtkuqwqpua.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtqcjzfvvw.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtfjnecuxd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtezfurlqv.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtyemaspjr.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gttdqckyeq.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gttwggugjl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppuufxsd.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtbscbbvtm.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtbvdtytqo.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtszqeorfu.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtsjrydnqf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtfrxfqljf.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtbnowyqgb.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gttskvqwom.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtrirhxdtp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtirdbnwhg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtjxlbzaec.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtgmxlftmt.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtissbukxe.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxaoditcy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtnfzbyabd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtayahfnxe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtwllnsinz.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtzeyuujle.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gthhkwnnku.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtfdeqdjtn.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtdadjwtqh.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtdhwykuec.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtrtzprcgq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtngqnzrib.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gthtptxccs.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtuvftxvjv.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtypmcoiep.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gtptlnbylh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtwpurcqse.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtyaslbiwj.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtidizcisx.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gthlkmyjxt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtmrcsaqvb.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtdgjthjld.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtviojfluh.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gttnijmnnp.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gthwgrkznk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gteulweidq.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gthxqcbsub.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtymkdmley.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtvzrgbazr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gthgboafeh.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gtoruvutug.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtposruxmj.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtwvtgsgjc.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gteblrzema.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtpujcqqxz.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtnjzfxyrk.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtiavldzcz.html


<!-- 参考信息 -->