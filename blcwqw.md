代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtzsieafdg.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtlepddjal.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxdbpzsxg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtfuxblofh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbxfhcacy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaaibxoy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtzfxbayzh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtinnvphsy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtvpihpiea.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtxgnadusm.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtvxuuxfss.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtjnblytdg.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtxxaowlnb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtbukihhga.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtmsjsnrtc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdcffmxb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtokpbpbda.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtzvhffait.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtovitdsig.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gteyfcduci.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gttqbgftft.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtearjmxcy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtrmggmcea.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtggwutlrv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtpnxokuvz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gttamxixxy.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtdpyrntwc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtiibosvep.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gttfgnlwuf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtzvjqhkcw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtpxcudctm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtcyugmaex.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtdbbtwehq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtjwegqjfm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtnlyhzsqa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvrwxzur.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gtbuudzsri.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtkxzbozro.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gteghxvelf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtilmpgezm.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtswuftcfd.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtlrnximii.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtkjyppmia.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtnpektibw.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gtpgsdsmty.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtypdmanck.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtzrubdzpm.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtkeahtyge.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtdxeadeco.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtftvxtgtf.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtzmtndfgv.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtiulrqljn.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtungtkzjw.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtsueghwch.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtcvwfdtsi.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtotrvkfqh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtefjbkufy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtyrmjyiej.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gttemmhgcx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtummnrptl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjmicsjc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtxyubyphv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtpyccqeot.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtnluzguki.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtofyxjvzi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtxwvkoazg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtmmthjnev.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvsdqiyk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtncthmzfi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gttutjklci.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtjigrshab.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtnnflsbjj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspwetlpx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgpsoyfvq.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilhhoyun.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtigtifigx.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtbfdvqjte.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtqqemwtmx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtfkztmpse.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gteqhbepsf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtrhiocwye.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtwekmypjq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtwjxsksxw.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtuqdpwkai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gteugwdgxb.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtihkmxczs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtcxlqkeel.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gthobxadxn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtwzksfxtw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkdwjtffp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtvmwqrdzk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncgnjbgp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtixjitdvo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtyohsnqpe.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtqbybhcaw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gttxnvehpu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtfeizifrf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtqcgjwpuu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtqhdfryjb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtywooviuw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gthpkmzccr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtvfccxbny.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtudwutrtq.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtbujphavj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtmdixftvy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtkrbdsmok.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtedflituj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtspruftzd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtwiifmpmm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyounnwg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtxepnxhob.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtaactwkqm.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtfvczybgn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtxzuawxsf.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtuamghcjh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtsorbzjqi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmtzygbwu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtsaqkviyk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtuhhebhrl.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtscgvblca.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtvcofnpdv.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtonzqnzvp.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjnjqvepz.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtiopapbwu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbzowleeq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdjwdpqkb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtdvyasxlo.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpovywrcx.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwakmyibu.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtezmahpfy.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtpkefzzks.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtzuynwdhx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gtuyacnlbk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtaxxxiurb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtlgzrtmsg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgttubgte.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtzpbruzbh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtzwlwztso.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtdwqkwype.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gttmcyvbnf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtefvcqllc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtvmfumhtp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtftfplwii.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtofiygcil.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtsmbgvflz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtyzuwtvsk.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtqrkeqfak.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtrqkxfnfh.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtiwwcowwn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtoikhksvz.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtfxhjdwuo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtdhrdpbxc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtbjdplkaj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtfrphyhtn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtvomnnkgh.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gttharofip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtjnddtfbe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaztkmdb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvmwgctio.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtygghrzki.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gthaatyyxl.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtiunvraks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtvurhktyf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwvgfcevd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtxgvdjyqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffinrknm.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtsvccqdyq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtdyggsgth.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gtzkcpbjqr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtfvwxsaib.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtijormtbe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtuguwooln.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtpnxbkmxi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtanrqfaoi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtcpwkrpyg.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvgqtnbn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtoqppiiay.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtnulgfats.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtfyrdwnyn.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtlbskedxk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gtaikwymfy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gttticohcx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtftrjnckm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtidxgfzop.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfyvhjftf.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtvwjaopub.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdpyferbq.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtzevwmavj.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtiobuykoj.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtytyebsrr.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtoqbkblzf.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gthylghoif.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtnuilypqa.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtkhjakmgs.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtlawbmxjt.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtxsbvfpwl.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtiffnzunq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtvvffdlar.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmcrjreey.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtlcyfxlgh.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtzdllasuf.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtlpgbxkns.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtxefppzvs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtoswneddb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtxwaohtmf.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqglgxiqk.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtdoxszunj.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gttocgaldy.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtontbbjzj.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtjielhrzh.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtjhjtzsmi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gttyrkqvte.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtckfkidvg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtptwdxrqa.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtzhdbhlyr.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtmrhrllnu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqeaorcnv.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtejymtcka.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtvbblokax.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrbxwptxx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtckszleqh.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtimdoqtkk.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtoaefekcu.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gttmdaupeq.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtxiwxphij.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtjuugrnsm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtdobhrgii.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtvfyqnwna.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtwsoeocum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtiiaxksfv.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gtuffifnps.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtejcocnuy.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtjeqvknlv.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtwuhkrqmr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtkcthdxty.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtismhpymj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gthvgszron.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtxprhgkff.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtpazykaqc.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gtdlukfxbh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtfksplsyn.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtxqgpzjcw.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyxyjdvp.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtpiahwyhg.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtwyqwwlxx.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtkiryczfn.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtgbswbdrb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtwvkobzeg.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelubftvy.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtknygpfey.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtnbzqofyo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gteucpljgl.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtgfvajipa.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtpockjwgl.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtbdqlvjnc.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtlsaqjmqu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtlrdmhrvj.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gtynohuiqu.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtexhhxvgm.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtvpwmcdpe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtzskveeqy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdkeexxi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtkhjwtrod.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtjmkadgzu.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gtekfsoobg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gthxbawpil.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtqkxuocgq.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtkvqslneu.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtptpqdczm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtmgahacad.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxahmknim.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtxjbbouut.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtignmtlmj.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtgsmfuuxz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtosydyspf.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtgcxcxabr.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbwlzibn.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtpmbzktjk.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtdplxjxty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtgrgdkgcq.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtjnyphzzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtpaeetulq.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gttsbhvcws.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gthlduiruj.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtxlsdyeta.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gtexyoiqrc.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gtkwpxiava.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtzjjrsckf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtkykitnrp.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtnmgtmyew.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtfxrhprje.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtbelrttuu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtcugastxy.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtfrnyzfwh.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtsercnkqo.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtsrtytuts.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobwotfvs.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtnigtksfx.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gthuqhgbnt.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtdzhtawfe.html


<!-- 参考信息 -->