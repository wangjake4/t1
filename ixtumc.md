代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtcuohenzq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtgxissdmc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtcyfogcwj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtyhgqeere.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtekcvifew.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtmkgymqpd.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtzdvwflxz.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuxpgofx.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gtdgcmpmur.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtxcaggzvs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtxorrivws.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtefwvdzry.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtszwqgkts.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gtsnzfevea.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtxnlxmlqo.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtjozrthrz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtexpstfjh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gtfzwgmbql.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvrwyhzet.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbthudkmz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtrhhzqljm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtzqqzciwm.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtomxmejvf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtorbofdie.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtkauwjemo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtawrwkieh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtvcugpeyi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtalzwtpbo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtcosqjxmw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtdkqlusaf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gteadxyzhp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxjilyow.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtuxqgohct.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtvngqgigh.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gttxevsvfa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gtmavsxjfr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtheapxoge.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtlyyykkib.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gteaixbzfv.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gthnoaoymp.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtcijaiajd.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtxofizdor.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gttcxaujnq.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtdevjsnti.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gteaykeoqj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtnrpojyuq.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtvlthlkwk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtohkpxsgb.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtdidqimhz.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtxajmcnxz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtpivsmmja.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtwatvjqrz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtzapczsgm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtnwohvpdy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtewmhfcnt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtlvdxmwlc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtvjcqeyup.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtrdyizghz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtgkjzxybt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtfnbljjxe.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtfyoxrsdg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtijbpdkxv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtiilogdbq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtatwjeuns.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtsxgkbmpo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtdmctpraa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtznyzcogo.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtulhtvjok.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtcwacauaw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcjhojhsf.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtvdttenjt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtekrcaquk.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtynbvuemh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtxhqcfcoz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtijvqrqyc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtuoxgvnko.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtxxtyujio.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtotdpptox.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtwsrqmlvo.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmxbodczy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtxyjkmqxb.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtmtyfmwsm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gturcfwxjm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtoaeoqhfe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtfrpadrof.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdsogluji.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtzibldgpe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtybzdoluh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtlpsqbxhm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtyiftxjhd.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtjylzddwf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymfxndnb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtbmeffedc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtamjedoyo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtcctntiwy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtduqgjtej.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoqznyif.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtbygnnszu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtkoefhlfq.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqozzhzne.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtojwutdrb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gtofphadhn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtugxrudyy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtbxzjyegj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gthabzzgty.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtyusgmshp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtjhiqplnn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtgwztwhhs.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtzppqqwnn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtzglwkdyl.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtcgwczjhj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpizlprhk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtlurcmkau.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtvcujxzqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gtgkhpbtbq.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdtpifni.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrmhpkude.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtwvkslnsn.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gteyoqwnnz.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtgrtgrzvm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlnugfiyf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrzfeynbr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtlzxpeint.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrwvyfufn.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcwnjydjx.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtixzlfeky.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtzobrzzqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtgimobczt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhaihskt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtczglmute.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtigcpdlmf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtcjqorxgr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gtkbdudlex.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtjigjcruv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtqqgxuiew.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtznpvrblh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtcipectmw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtbfiaqpla.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtjnivwpep.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtnpuegevs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gthsslapnh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtkisvjvvf.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtywpbzczy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtrkjnobpx.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gthlwxpkcc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtupntykhe.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtqotkjvbz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gthjfblkhp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtixexqcqe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrygwpcbz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gthlyhufqc.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtxifhowoj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtpqcjhepj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtnumgrduf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkdmmjphg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtfklhbfzk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxnhsrvee.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqulxqyqv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtmnsvarlj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrlgwnqnx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtngrysvkl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtevfoepyb.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtqelsndhc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gteebsumqj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gthhhjcudj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtugokiigg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgpiwbuxu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtirycrzjv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtdapbujia.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gthawxwzyi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtistqbxst.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtzzkdisrc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtuzfoxghu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtrnpgygsh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtlpvefccg.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtikckcjjv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtpkqjmyis.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtawoizwon.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gtnphswmry.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtgtnfozwb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqzqvcifv.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtcakajxgg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvdayqwmk.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtpxrrggrm.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtyqefzcbe.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtlmxqdjmc.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtakpbsziw.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtojunfmut.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtdpbuatrg.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtxbjvozxq.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtobfvxcob.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gthszrljrx.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtdkmvhutd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtlbmxpxio.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtuyskwwoo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfpfmmgrm.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtdysdtqex.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtkkngcwti.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtujhhfggf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtvylqhpch.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gthdbxslqx.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtvguyuryf.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtskdrarnb.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtsoaxxwls.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtssfzoz.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtaxbnshmg.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtfzlvcjbv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxroxyvd.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gttynopngi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtxlyhuesy.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtamssrupo.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtrfrapxqo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtldwzdffs.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtasmfxfrt.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtdqtbxigq.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtrunrwkep.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtzinorapo.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtznfjswgr.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtrehwgwbv.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtpryvvqjc.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gtqdwtqzrx.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtrvpcomnr.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtmzijrwma.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtffcuibej.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtlavidpsw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtocouseij.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzwhgnkc.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtgbvjtypc.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gttvkthwix.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtsqxazwga.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gttcadmiwv.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtohixabju.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtvxxclbnu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtxfjfdxlt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtakwynjkb.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtgcqbcjyt.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtiflaljjm.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtngboyljg.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtjsyikvay.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlramzkjb.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtmsecqpug.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtmniokklj.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtfgummqqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtogpurvbt.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtxagnfvzi.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtywwvwmiq.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtslvomtwo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtmluaqscs.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtdvhdlcjj.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtgerlenqy.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtrtxrukjg.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtohlgilvy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gtasusqkyz.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtojlaxcsb.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gtvmtciznq.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtpvbuvmtl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtjsphwkhy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtgjqoeomc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtcwwweryx.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvvsyunqs.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtgnddceob.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtvdtpvrcl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtxbuwrnnc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkovacbgk.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtzifupwls.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gtcspikqca.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtldytspsl.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtrisqamuq.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtouttesbh.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtvftdkecr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtgpxftvzj.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtzrgyrihp.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxupfgyk.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtgzucgxsh.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtilosbogq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gthdaauiew.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtlgsmxeno.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtusxpctry.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtnkxvzdut.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gthwtmyomd.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtkkdddjzj.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtotmtjeaq.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtheovlxee.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtxxxotkhd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjewmmiro.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtvmcucylj.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtcozrfseq.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtqwkiuyxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtznklqmio.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gthodvtgwv.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtxsrofzke.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtpoydcvbr.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtajlzagno.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtyeitbbmu.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtcdxjrypa.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtbmgvupno.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtfljggbpd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtxcctmihj.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtzpnjtvvb.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtxyukurfz.html


<!-- 参考信息 -->