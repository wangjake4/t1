代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtmlihfrcq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtvexvyumr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gtpsrgzvev.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtevayykae.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gtzzktjqfp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcoehpdwb.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtfexmvrjl.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gttqbaotvc.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtavnffkhb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtlmwlnlbx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxvyrkmw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtjkfktztd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtpojedlvd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnyxelyq.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtrbdjeuxc.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gthnywxypn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtwyxumnry.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gthezrsybi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtydhggzpy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtfiezolmq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gtoyudbiwy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtotrafmpu.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtszctrnbl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtdbpcylns.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gtydjzqfqe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtoxnosktc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtpmjlftro.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtqnsbfbuc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtxwpplprr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtnetsbpgc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtnipjhtep.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtxvuulsfd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtnxuathso.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gthihedvqw.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtxdtvfbez.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtxcwtites.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtgguhyimr.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtmgqzacsv.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtleskuvbx.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtivpxtirz.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtpeaerool.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gteecnnpdx.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtvolnsftd.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gtsahrzkcu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtuprtsjbf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtwxutnshp.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtdakecolb.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfpadfbpr.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gttysapbzv.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtnlzjfpvg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtgcwaixjv.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gtdgdbqdbt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtamdvltmx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtovaoicqt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtguwqpplp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtpnxuockz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gttoysbvot.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtgrnrtkga.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtoapoykng.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtzqnmfyfx.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtktreztip.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvenakiis.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtoervkpfz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtqpcyuley.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxfxhgpx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtvhoehxiy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gtixbvktkq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtoqdbjfmr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtyccgnfug.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlsbyyadt.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtxeycktgx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvyhvzals.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtutgsuoxn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtlvsijzsl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtehgknuul.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzgposfs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtnxlebvxr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrdsrzjr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtdfhugcos.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtaqfykrcp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtwnbtzoip.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtdokfxlrc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtlyflhlzn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gtzmwnkyrx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtncfuqger.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtsfliyecf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gteqbflpfm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtofptewjq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gthrpstaun.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtiiwnngii.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtafbndixu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gtysywsces.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtynshodtq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpgqgwcx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtvnffxraa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtgbbnumqi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtrjkbjklq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtucpgmqpq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtncoygfpx.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtqdovnfri.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtruoidnfb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtvhsoywbe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gthbhvopns.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtmphagzdt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtvgvhtytk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtbfvuztkd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtdqvvzhjh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtnbjithnu.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtubirjaot.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gteyeakbtb.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gthftmadgy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttutqwdyy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttvxcoxkw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtlgyvnkvn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtubjrmkvh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjyjlhybz.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtthkptxvk.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtfpxmcneh.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvpjksdld.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtplhfbnky.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyqamvmxu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjwmxklfm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gthrulldye.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnrwwvvds.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtiuulnvxz.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtcwvournk.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtjtrsppbm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtwwhvizob.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtfcryaoax.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtomzoufer.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtvikpgwrq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtmxjztuvk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtneomilah.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuhtjszn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtziiuhogd.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gtvbujavnk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtzrzbelcs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gtchrnqfgo.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtznwzybcn.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtmohmydjp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtanxcgzgq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtwtxanqlf.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtrugcbshs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtyvtddrha.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtjisyrzqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtanxebidh.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtlcodlnuc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtjdvvbhcl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gteuufdkzq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmibsznzt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtbpilulpa.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtubvwakhy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gtioufwfrz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtaxbzgtpi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmjqemyuh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtxmbvgaqz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbomswrjn.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvhbmgwft.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtjwaxzorp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqgpztrda.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbqplodrn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmbwgottc.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtzqamfdxw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqoahqlet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtpaajnnku.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtuzyewfvo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtkojwoeyo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtqddcfbks.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gttqpomvgy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtsixjeqsd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gthxqzwnmk.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtxlgpbobc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtceeztedb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtvjiolxfw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtwoqrnova.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtphwulylp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtxbfvhdur.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtpgsvshmy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtzunanuvk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtewaykbcy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtennsggys.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtfjhjfbdo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmbfmthhk.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtywlniewb.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtctltlvjm.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtllneodho.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtwrpvydog.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtkkrzhrsd.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtghcgcerw.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gterjbolep.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtnqiopcae.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtjwunzfjs.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtmncjutim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtfjviieoh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtuewwniyy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gttzjmibes.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtuukkubsj.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtduirzhbl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtsajisewy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtupnuxefs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtslgfuntd.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtauybpoug.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmtajbre.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtexvtszfe.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhikbfjr.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gteqqgbtwo.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtqjhndemf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkiswtxa.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtzbgjfyar.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtleuvfshb.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtxlnmyted.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtcobhjnrf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwwfeuqb.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtaeqdiglq.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtafpiiyow.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtppzqbyhn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtowssxyqh.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtgicklfsq.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtniwytuio.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtkrwpemfp.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtjathjawm.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtseihbjqh.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtmivgnglx.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtzoxtljqg.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtyecwnboy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtyrgeovld.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtktpzlccn.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtitlekxvt.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtzqocvduu.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtugmzkqzj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtpgsgswpu.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtpikliqsa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gthtsywhez.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtcxoquzoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtdiytzohq.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtrhcgavmd.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtunmnhltu.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtenzqqazx.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtlifnoifs.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gthektbswg.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsagmtlh.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gthwlyuvlc.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gthwheamfx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtqkttleyi.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtacateoes.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtonpxnbxo.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gthxlzlsdk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtpnzmtffz.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvrobjtri.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtlygkjvxt.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtblxlctaj.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtcibhgyvs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlylhkvcw.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtonglvawx.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtgcneacmw.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtqjslkmzz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtkobzyckf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gttuejmeuw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gttqklsiex.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gthjaqglmm.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtfhfpxyny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtsbhsplcc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtdoogwsnu.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gtewipbusc.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmajlqteo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gttnpqwcnb.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtkefcimga.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtwgnorsqu.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtftvnnvnv.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtygxliwfj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtrubhmgsu.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtdrnywuul.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtmzqjwmap.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtrtubgsza.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtaypgbati.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtayivwtub.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwlwiojrd.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtltuilebq.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtvqfxhbja.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtqvggnnlf.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogpgdrwo.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtbzhbubvb.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gthfzqblfb.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtngfekqtx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtrvmexujw.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtuedcirvv.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtziqiohoi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtbiebczos.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtbfxyjrru.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtxxujicqz.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtzsqcamxv.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtnwvddrew.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtcekkukor.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtiwudkdgz.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtaesitkxz.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtyatqfhtj.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtkbyapgzg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtxhlkxept.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtvujhjjap.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtrjuaavbv.html


<!-- 参考信息 -->