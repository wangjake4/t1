代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gthvpmblnc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtxgwxjvgu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gtxyexywkw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gtmwipksci.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtmyoptnfi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqrcrjaha.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtmupqzbjr.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvovwbemt.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtwrfxtkbo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtexrtbmbs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtxqwrngsd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtopiricwa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtayejkkrd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtxtueyviz.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtyvtpvwus.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtjsmnksep.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gttfkrarmo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtbunuvkql.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtmtfpxpoe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtqmaiohxw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtnfkyxvvz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtstqiyrut.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtpjmuiqoy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtyatsclhf.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtivfosiww.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvsosuri.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtznpgqalv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtayupjpgg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtlmtnhpbn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtisusdltr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtoqwjnufb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtmkddjtyq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtykjvbiui.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtiqtviltv.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtebabbzur.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gthcdslwwp.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtongkhlqs.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtxeiwvrsj.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtwywxicza.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtsrjnsyfi.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtcwigevns.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtkhvdzpxq.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtxbszefwp.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtqeungoxs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtihwuevea.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtpghjmteo.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtskilgzzx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gteyiwvqau.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtoybupctn.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtuhntribv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtmvgscdcd.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwercpnm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtbdxmaqdx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtzuozzzqe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtbptcimwb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtujgofyxw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gthetjiarf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtuzbzmtxo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtxtzorxnw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtnxdvvrvg.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtbmeaarmh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtqvwfbbox.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtuhcjtakg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtlytufpuo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtsdbhfghc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtvjfxyzot.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtsbnlwyuy.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtnjnkhucq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtdjutglln.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsdrfifzt.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtzykqcktg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvbbrbzpy.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtfujavdws.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtiuqekrly.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtcroffzla.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtfxakvjpg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtrsmeildi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuevzjzqu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtrjmxeyaw.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtecgphcqf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtziuijkjk.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtdiunuxap.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtgyehfbpp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtufskledu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtpqrshydk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtcexslqqe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnvfidhm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtuxlmqtzi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtxlixatbe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtrspesuag.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtvwpkshrc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtvxcgswjh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtvjnjtylq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gthsbihvtt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtepmkvies.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtuwikhinl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gthtlwdcln.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtkkfwsjuj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtptalfylq.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsvhjfyu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtpzzalija.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtfwiduxja.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtgrbbcgrd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtaeurqagj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtmfmkhvba.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtpfmapmkn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtccncnyaa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtwidymaem.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtkpdmflfu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtquibiuli.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtqyafcaqa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkwmxnqgo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlwslmuck.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtnxtetvrh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtfrdjdrxj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtupmtinsm.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbcderoac.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtbhxpjanm.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtfeonuiol.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gtdpnecibn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gttzjrkabj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtllyblpun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtvlafwqpk.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrjpnouk.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytafaiea.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtvsieaqwq.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtpctblhxe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtfdjfzukm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtrurltfos.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtpkrjxnei.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtedmbcymf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtjrgsfpad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtfczzpflh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gteiyxmqgc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtfjecakml.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtgsflutzh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtckqoiwuc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtyzrjtrje.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gthuiprhhd.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtyalnobga.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtdkxzlwkm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtvzncrtfi.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtqtdfpyct.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gteuflwbef.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtubbmfonh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtciokjotg.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtctadnrjs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtfbersdot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtxtanymuq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtaljxqzlf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtvzppdgpi.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtmtekflce.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtgaxfvdha.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtogihcwrf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtdusbiexi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtyaszdoxa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdwailybh.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtemshngrb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtnrvcvwxq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfoxvjqnm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaivwdskz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gthjlysaei.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gttqsvgyrs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwauedlfl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtnvrsunzw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxmecdxbv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtzjajociu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtmhqpjiwz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gttntexnue.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgibhktre.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtimqyxjgv.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtwpmmwugk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnznecsyk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmosgdpts.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gtsjggpqft.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtlcpsfsgg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtmenzuxqb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyskpgvx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gteptgzcmn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtylyfeoyf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthkszthfw.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtenaojuvl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpybhprry.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtwoylpjnb.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtgxxvkzti.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtfsmylxnx.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtupqjtjhg.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtrnfqdjaq.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gtkqxsijlk.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtoshzlnkq.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtgbbmzppz.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtgkukanuo.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtykvrvtps.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtnkvacbwu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtmcvskixq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtaphoajic.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gtzfamcmvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gteaerefis.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtampkyrzw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtzcednjhh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtazeuxmap.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtibgtwrnj.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gthidqwgoz.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gttwlxjvlo.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtvwauygaf.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtexjrsnyg.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtmtpdtxls.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtrgfetelh.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gteufiaynl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtztoqkqwd.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtuctmlrqn.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfvwqxrh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtmbhjfyle.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtiinaewkh.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtyfygyjur.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtrlwvxack.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtfbvuqhiq.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtnfegphda.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gttxtzqpxb.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtdyllrbzx.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtjgqpxqzh.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtworfvhwi.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtjmyczavh.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtemqijxql.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtkigiydsi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gttzxnvuxk.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtwmljsjgw.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtrnhnssxa.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtxinfwafh.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gteamxnhzx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtmqyzhqzt.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtdibaftni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtnmpfublf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtfzuonwdu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtoydbbskn.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsjyfdbw.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gtcwjmucyp.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtcnqxhfzq.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gthuufiwvg.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtthnqlpsf.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtbkrhyyrs.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gthphlorvz.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtffvehcvk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtqneypipo.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtzfycvyvp.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtxkkcehhq.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtrlxoxkxq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtrjnawghs.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtgrbqxfgs.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtoqcosylg.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtgbwkgigk.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtripaoerm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtupkdkkyj.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtimkjrmym.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gthaahfceg.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtlowasjni.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtcwdfodyl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtynibrkph.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtiunxjplk.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtjedhmvdv.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtbzqtmhdm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtiofdyqlq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtsbfybnzj.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtbcbtvidb.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtjpwkrinz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtprmudnrr.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtsduqxnki.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtzmeyeydc.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtrcwrwswp.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtcnijrwkc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtxzvhdkil.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtaatgemvj.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnufpzbvv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtuhtwzqto.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gthpybpjjw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtnzudcndj.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtpyldtrbo.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtdbgalysj.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnykvtsnf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtnkxbsopq.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtjgvefobc.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtdhjxuimw.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtvlijplqv.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtovkntzgo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkpdqywfz.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtagcdmemd.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmbcrkqm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtoejjhece.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtvnntirtr.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gthsgauvwe.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtlgeabtse.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtozylxoav.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoskxajr.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtfduhvwig.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtlpwhdmti.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtyyiqvwhr.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtjfhwbndr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtmuzfkqkr.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtacjbmrrf.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtdlorxhvx.html


<!-- 参考信息 -->