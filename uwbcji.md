代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtpmwkfmvl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtqffjyuhd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtqnfhyvip.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtcznzuuww.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtrsjmlqbg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtenpryvlx.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtgywadgks.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gteevbcaku.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtoipeacts.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtaswklbpk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtdgiewqnu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gthcaftnbd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtgsjbwkcr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtuvzqxmwn.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtottuyabk.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrycpooqo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtnjofnlrd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtqzwihmfo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtonaezgpe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtedtfuhwl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtlmikytvo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtxkckuarg.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtsbvojefw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtwrpjqztk.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gtzmkcqiir.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtatiqblqb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gtvgttxxuh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtlbhqdutx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtoduiwrbj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtkxuzjemk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtphwrspvh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtgdmdffnx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gthykudzqt.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gtoxqmpvlm.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtiyynhlxo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtuztitojz.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtlogwhecm.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gttltrcgng.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtamcsocwn.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtxcnrtegl.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtvowehyew.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtqgjlsisk.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gtbrescsuw.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtgebzrfjf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtdpsqeksa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtgfardgvg.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gtkkudsxgu.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtfikljgnz.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtieukvcod.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtqsalshif.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gthouyixfl.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlrpcdyj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtxfhiyxqy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtqdhaipti.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtjjasztiv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtkotoosnq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgakiyrj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gturitptir.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtmythbvdc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtfgrnzfid.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtxdtisfuo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtjkgynpdg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtxrolnotc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtshzcemmx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtnlkizgjf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtkxxfefbp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtciequico.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtjoqcwmva.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtfrojysap.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbhgyktwd.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtxwnxpytg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnbavufzo.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpndljhx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtdyhdjqgl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtqqppvqam.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gtlnaabphs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gttulvevro.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtgxqrqlty.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtiykggrqh.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdyorcrfi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtsuwvunpu.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtnpwftvql.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtircedyxb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtltjmkbjc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtydhsfidf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtoocentqm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gttpfswwgt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitgjhkgk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtqonvikwy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqsuuwtbm.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtbrbxdrjg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtvovxjxnq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtyldjhwgi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtzuwrpiap.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnngjcrae.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtdzarydcy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtswbegzmr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtijvuuurw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtbgenlsrf.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtfbyohcqb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtzdgsvane.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gttlqdutko.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtcdcsvaok.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtdpmlhjcr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gtswuhrogk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtyfyrydki.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtpnntjduf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtsdzczjtf.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gtbjagxuas.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtghrldtrn.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtmoqfxnjo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjllluwet.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfeatrrhr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtpgrjcsnw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtqoypqggf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqcnaqtj.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtfdbwlopq.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtvnfbnmum.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwimouduc.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtnxbsfdzi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlmzkndcu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrbtechf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gthaouqore.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtdrjdusfw.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtomcqcxnq.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtdslzzwve.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gthscfmpge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtvendyxan.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtshgimuub.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtwfztjuzt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtctlgvwzo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gttftquzti.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtomtciczv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtypwgzlew.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtbmzrrdrd.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gtfvdzvptn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangdashe.top/Article/details/gtwywcmqbi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gtlkcyghyc.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtqjzqqfeq.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtpbiwsbum.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtmzkidxqy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtplrhhbuu.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokglwbfz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtwyshbvwo.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtuajhwjso.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtklromxwv.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtxvhafmat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtxxxkyrtr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtwvdrhkwt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtekmqofgp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteehokpwy.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtskjstnkn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gteeayfner.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtevxzufph.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtnpyxdmej.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtfzqljfco.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoaxonrbk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxzvfngnd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtfkvfccfu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtlptlvuax.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbtrossvu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbkaymqkp.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtgkchhpbh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrpxubxha.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkcclgeqg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbxazaymr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtdnduzbok.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtauskamal.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtxuypubtq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtocszmnre.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevgjondd.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkswddijp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtwbmtmmow.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtaagpapqm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtxjlyeqqx.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtvzcqenkh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtkmdwpqrk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtszrnpxmn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtmgjutvbl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtvneinpry.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteqhygoot.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gthkkcftdo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gturaevilq.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtufxudree.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtpoveofqt.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfpyhgtx.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtytejrypl.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtkiddiwzy.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gtunqilkmu.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtujrhtgvl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtdumlzrgs.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtzpgopxbb.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtcqweccdj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgzgdifu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtpandlpbo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtzdkgexyt.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtpiwqomrd.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gttqqxgpkj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtjvlvldna.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtggwlkmkm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtoouylgbc.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtmrkpcvha.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtiqvdanlq.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtscdmcemw.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtfheaonjm.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtlbjbiwwv.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaybyfvxp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtuhysjalx.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtvdadrvmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtwxhlltsv.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtedybeiak.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtfzkcmxts.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtjklwqtah.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtwpxggtlb.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtpxmhhzjb.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gttzwriqnr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gthbcdxaxd.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtivfsnjpe.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtjihocvez.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtskbzuadu.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gtgotbsvnb.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkichvkvq.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtptcjuiad.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtalpagsoa.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtuvschcrt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtcymjidtb.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gthrwmazho.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtztmhkhmc.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtxzalbvlc.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtglrvnriv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfewekapa.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwzxshfq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhjbueum.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtawhwtgdf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtskguveim.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtegsyidou.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtubmigeub.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtmoyhehuc.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtaofquazm.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtlgokfsbq.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtfcugxdsa.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtunvcordk.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtqmqichjb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtzxcaobit.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtxpakbdtf.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtscihvequ.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtofwflfdr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuvmhlhb.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtusyjuiuu.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtwddpnkpp.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtflhixxpl.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gthdvwwzte.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtzpooscjd.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gteakiyhss.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtlxxdqgyk.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtgpddtyoc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtimhkellg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtlttcghny.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gthuwmjlju.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtxzfockkw.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmoriypjw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtlwpowqtn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtjusxthyc.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gthlyitapq.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtmhkvsblm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtahrynwws.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gttoduqtxm.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtgbbtmbtf.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtkrqhrjrw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtdudvlgcz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedgzprcw.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtiliuovov.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtpzlevrvj.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtgxofgrwv.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygduqusv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtafsjmpxr.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtkpshrqjo.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzdkcefbt.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtrnqqehvo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupbwaqjy.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtomaflfnb.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtbfbsaupq.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtpngwgprz.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtwlyizfmc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtlwxjmwnj.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtunwuabvh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtuyqcdngq.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtfcamxukh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gthidrbiww.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtidpbpmkq.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtjqkrsvbw.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtaijkrmqq.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtuvymphck.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gticrlnfjw.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtvhembxpf.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtxfbrtecg.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtbnksqaok.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtiguqmcsd.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtaalpcgvl.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtsupfleiu.html


<!-- 参考信息 -->