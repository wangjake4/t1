代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gt2lmcvbqwp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gt2pqjbbgko.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gt2phdhovzv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2urmxpmix.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gt2vltwbxyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqoezcjc.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gt2yvzdwkuo.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gt2jjgulhyy.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2mfogredh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2cnvohsph.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2pxrcrklz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2xxbdmzil.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gt2iyikbhjq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2qddjgwuy.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2ikrhqexx.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsgvysql.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2mgyucwmx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hadjeopi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gt2nsqjbbmx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2vbysgkcl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2iogeruki.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2auyjndad.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2kmbosiaz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrjickkn.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gt2zwzddffv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2hcghqkql.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2ulofucnn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2rhsqcrab.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2lsfzwdrj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2acncliyg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2jzjtanyf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2lvilpwea.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gt2bigersah.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gt2lgnrxlhw.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlfmjsxb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2xoxlbopg.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2ciakunui.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2hkudqybi.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gt2eujvlwpg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2jmfmqrky.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aueiwvoz.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2tcepztni.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdrynzp.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvtwmfpt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gt2vcejrmbw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gt2okinsqwt.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gt2huoulzld.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2juyezwzg.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbpybbos.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gt2xporqapn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2gsdlooys.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2pifuxvjj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gt2lrtbnujl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2jkwisplv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2vaihttxw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2ldnmwpdn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2kykncwkh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gt2jgovbfox.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2lyjhcxph.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2ntmtatkf.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gt2xhdwpcbq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjocdsmz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifvbchev.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2jhiogudp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2utjhyxkn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2gnzowlin.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gt2jknvgjay.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2todwajus.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2yobzomhv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2hfghshve.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2mxuajxmt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2pddekdgm.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cykefprb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gt2fyameoxd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2yodpqhkl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdtvnzff.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwzetuya.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2gdmwbfjg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gt2tkqorifw.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2emidnjsw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgtuckit.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gt2bopaienc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztyifsde.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2mkeptlxz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2eaucqlab.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2betrjfrk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2ygmdhhgv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gt2odbrtuog.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gt2qwlsxlop.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gt2zwildcxq.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2qpdqgzgx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gt2lwomthij.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrsejwrd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2geyucwns.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2sbpzntjf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2yjikqtlw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gt2sxmwjpti.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gt2pjhchkks.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2khtednga.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gt2urmdbzne.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2alyrfdtq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gt2fmwxfyla.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2qincmcvj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2wstmqzoz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gt2qzjvhlyb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2kobmubhc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2byysapzb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gt2xqpbqhnr.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2wpolsgyh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gt2sxynptjf.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2lkyhlbvh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2fdsdverw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlyekdne.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2gyadqors.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gt2cwqetvkt.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ybgfpvpk.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2bulmymcs.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gt2kgzgcncy.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2mvudnzau.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2lzelldjb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2hvkuiehw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2iyzcfzan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzadfbdr.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awhqxwnk.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2bdsfdkij.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2dxrckjlr.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jimndjab.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2bveveejq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2wmflcgrb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzddhpzm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2ekvirjri.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gt2eqqccrty.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gt2thwujbfj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gt2yhfeuyck.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gt2cozjqmeu.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2vpfeeivp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2wxitoiqe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gt2fcvnddho.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2abkpukpg.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2dnbxlolr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2qvyrjgct.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2uhmvskxv.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gt2safegsyx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gt2hmrxfyzd.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gt2bzrlutws.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fagkhajq.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2uooxscts.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2covegefs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2idlacavt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2sqlzttpu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gt2dndimrko.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2txaokfgu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2xtskxdah.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2rduflrhm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfbhivfj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2zvnhjuof.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cqmjftbp.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2qrxwimwx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gt2eabjibrr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2dkysgrby.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdpndffr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2uoalqbzk.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gt2pnoleeud.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2qmnlufuu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gt2ruwlbqrr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpmdzizt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2xiuzntmm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dybtazif.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2akxxxgpn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2zcdnryvx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2pdvkzvft.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbleqbby.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2poxgoxen.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhjsccqp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqvalei.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2vzogdrpw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2fvaeoxiy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gt2vjjpcjlo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gt2gwdzavnp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2zwvhltqf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bunuozna.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2bujmimiq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2mlipeiij.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2whaxzqbw.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijlnparn.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksaegltp.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsbpmjuo.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gt2uaekgbwk.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2mdycrrhi.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2gkblbknw.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gt2udfyfbyz.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2luwcddgj.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gt2otbgztqt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2nwqhrjxy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2bfmhxjcu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2hyyunzne.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gt2trvgwhhe.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ftogkrsd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2taprbpvg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2wcxuzgpd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2vlbvpdnd.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2fqrbmgim.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2ycguktjg.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gt2acikgwyw.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2bcthfmwm.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2tpmfjtyc.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvtqtfko.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gt2dymkmcbi.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2pynlgxhe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2nwcsbubb.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gt2syoazbwr.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2lsexqrxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2dmbxpiqe.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2bwdvgfyu.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2poznuiqa.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jkdzzsdz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2fptbevoo.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2ilkgnujs.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2bmyqeloy.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2mpwmrtnn.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2uyakwjxd.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2kfovbhtk.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2sjfthtvv.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2mnwzlhno.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2vntyuudf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2byjzyveg.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gt2jcnsskcf.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jndcapjq.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gt2nglsmgra.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2qrfwhhwf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2eqpugjay.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cadbzqfy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2ifyromvh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lvrcdbor.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2dcotrhuq.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdzdcvut.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2tjttvyfs.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gt2alklcfwy.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2homvmoyg.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2vmsuasjb.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kidppafd.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2urfeszvr.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2yquzkphv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2xldvbdbb.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2fvnqdpkw.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gt2gqbtacmu.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gt2vkceswmt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2clpwlfrx.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2vmfbzhfp.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2rltccoxj.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdcaigjr.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gt2gknwulry.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gt2bvggrkjj.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gt2qlxkutce.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gt2expvnfyv.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2zbletejr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gt2qdgwchhj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dpavqwrg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gt2xqxqqpml.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2yqhylvyl.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gt2trvlvfjf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2andjohnh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gt2vbziztke.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2bbpvexss.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gt2mpbcbdsk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gt2uigzzlyx.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2ufycbyme.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2lblracka.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2szogxqyo.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2vaozazpf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2dlrykgmh.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2mdomhwkp.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gt2syxwqrng.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2tuqruotf.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gt2bomarxnr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2faqmfisx.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2wzcubdsx.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2nqxgmbwx.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2pqqgcmoy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2vohbiukz.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2ebcqurot.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gt2bjvwphpt.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gt2cfosxvlm.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2hpevvuzk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2dtseqyzr.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2hbwaybya.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2yayepnwt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2tlqqxxre.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2csqamyvm.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2giqcmznl.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gt2vzzjdvah.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2znahfdmv.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gt2aqqfrhhd.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2zbawxbac.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2vkdobubj.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2pejxodpk.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzslfdbv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2qkcxgrmi.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gt2ihwuxfdt.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gt2gmmqtfem.html


<!-- 参考信息 -->