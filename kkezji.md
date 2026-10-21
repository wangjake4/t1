代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtzedydgwe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtbtszxzcf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gtjsgnzpwx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtjzacphkj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtseosxkjv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddxtbsmn.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtfpzhrror.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtiebecwtb.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gtkjlbvira.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtzrhvfwhx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gttqkntyji.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gtyfnmrixj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtwoigvupy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtpijkdsvz.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtzvupovof.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtpogwcrzo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtuhsteaku.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtfaluxkwh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtrotjdxbr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtapyqmkbk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtzqzpnumq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtxvtlahak.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gttpszcvuc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gtfnncqqrq.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtclglavhb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtqmtrtqwk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtjeohiomp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxfbcsdt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtnpcqqkvk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtptbcnoni.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtvaaxxgau.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtqwybxnso.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttelxkwbw.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtqnvjjtck.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtdebsntki.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtrrfqjnys.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtdqrzidiy.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtshtrlgpz.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtzeujwfxq.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwopbuuyx.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtzcamjvja.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtsyebgcvt.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtebregqmh.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtqyzretfn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtgfxoqylh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtwgukgfvn.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyoumdpr.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gteahfyvgb.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtfxrdhodk.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtwojlyuyg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtbhmxoavi.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtexxkmrbl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtneoqowqn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtiaqqxpmf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtadfntccy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtngiozvox.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtmilsqxad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtzmisrtjf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gttyyeapze.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtbloxqpic.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gttenwzotb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtrsnpydwl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gthxlkyxdo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtfystvsdv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtrlrxlitu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtwqkfvdgi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtdsviuxfj.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gttsdtsqcp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtkebevuyx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtijbjgdlu.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtzwjiuobf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtegntjaoa.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtrpbsmeyn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtxjjeofrd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtuuwaiqun.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtkoeqszyj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtzjgoycde.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtdhziygie.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtrjatyebn.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtohtaedib.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtksmbdpug.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtkvnwtrze.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtqekvwhje.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtxqsmcmcl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtwvxuknro.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtlmlbefaj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtoffhdbic.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtlvnzzyln.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gtgbjpcuoc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxomrncxw.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gtygrudlpw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtwjppbezy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtnofukknf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtvhmtdofd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtuqddfuwi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtjqmijbek.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gttzmvfdhp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtkrejivhp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtgpcugqdm.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gtlrzsidvu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtfrforqoa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtepvbxfll.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtqymnggyj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtzbadouvk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtlovgxheu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtmrjijuar.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtloyzgzpf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtogcvtbgg.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtgrybqiku.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtkqfbehyr.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtfdbpkrcg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkcbfvqrb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrmbnqxak.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gthxpseytm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gtigawkmio.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzubwcsia.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtpqxpxqpr.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtwproyuzt.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtxoymoljp.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtdivhrexm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthdqdglcq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjgvbbycb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtejdoxhxp.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtgphqqukz.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcibzgmrq.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtekqyzxxr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtnrjacqep.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtramtuund.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtojrsmqqf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtvffelxla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtguphxfvz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtyyxwteif.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtfsxyrmwh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtguhfnlav.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtekqyceza.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtxuqmhnka.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gteyonogip.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtqtjkjfnv.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtulmlwfio.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gttcahgocf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gttvgiofnk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gteqjprexa.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtuogwrdhu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtkeevvpoi.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtyipaibhh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpvbmzzeq.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtoianpguu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtxqbtyhau.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtgmpqtsyu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtelsacipd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtomseuyab.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdzpgaiti.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gthuazloso.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtvygyxjfe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsudgasuk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkxehxvtx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrrqyezik.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoajufgja.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtvarmdzhx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwpsnukaf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtltmphqjf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfpqfbloa.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtvllrndoq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtrkrygxqq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtcqcbzmoz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrcurecrl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrmscraxn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtvxanamrs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtgedgxjij.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtuxqgtqdd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtnjkymqsb.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtdtboepno.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtdwitsgsq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtljrjymlc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtttphmvho.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtvcretfzt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtltcactii.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gteakqwssl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtkicanfki.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtuskvaqao.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdkuldhbo.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtpgsfddye.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmaguvafv.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtqmpszxsi.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtzdwjsabj.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtahisxviz.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtruvgxucq.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtzdmjswxx.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtgpatwfcy.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtdhmgauaz.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtbabjokzx.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtqnxhmblt.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtjtwsyrli.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtrzcbllzb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtjeudfbdh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtugknyjdq.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtqagukpsl.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtqhegtcsg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtxdhrxbts.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbwdmhbcq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gthzccgoqq.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtdembxjii.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtueakgmnc.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtjbboiakp.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtjilyhuzq.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtststgbqg.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjwxkpva.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtqzxxicpu.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtlvzgubnp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtbhfwrlcm.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gtnpoxeppe.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtpfqsrapp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gttexfyvga.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtqticujlz.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtbtosiyzs.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtqfxwaxfq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtfxakfxsd.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtaokbfxpm.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtlhwsjnlc.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtuukkafvz.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gthdrbjyuq.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlloqnhw.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxdosyxrb.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtnpiwohkz.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtuvscmdyi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtckjtlduf.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtpbmzfhik.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtjfswzkpl.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtmzdxtnrg.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtqfriczyd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtouaqjgfs.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtpgnqiazq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtilboryll.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtomndvter.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtgqapgsyk.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gteqxfoudd.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gtdavpndea.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjzabway.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtduprcdzi.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtftmabyuq.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtwcwavrzz.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtduypcyyc.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtaxkembst.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtlbbozpqn.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtlntdkmmh.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtvurpudkb.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtpldsnfch.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtndqsusrh.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlolgmuoq.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gturflvtxv.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtkospcypo.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtwchyiubx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtbirgmmeb.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gttfmpjjjo.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtodnvctaq.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtqbndrbyc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtvupnfimx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtllkoflsm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gturgfygnk.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmndehplu.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtbvwsooif.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtibcjbzbb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhgmgzgy.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtnpjqhhda.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gthkmuoxwi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtwogdsbqm.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtxlkqrtvw.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtxdoetejv.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtccmjvagi.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtovkssmpw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuofbnyn.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gteixnzeal.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtxszokuqn.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtvuzvvunb.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtuaffvxoa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtauyvkfcc.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtayztldcf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtoqcivaya.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gthmiijyqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtiydnczfx.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtfbbmlcmz.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszusewuv.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtmeuaisjz.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtrpbfuups.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtoqnqttlx.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiwckewk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtglfeylte.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtoazvwzvu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gthohrqkmx.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtphlcpjvn.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtcoahgvfg.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtdjonacmh.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtmmdwchcf.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtbzgztdau.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtzrawejdt.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtxjyiubwp.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtmwuofoph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghbxlwsr.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtkfeiswng.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtlvmhatkq.html


<!-- 参考信息 -->