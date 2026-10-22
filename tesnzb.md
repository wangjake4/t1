代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2rjuynddh.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccdgwsix.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2psecirqb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gt2rwjillfy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmzfubyz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gt2zvhzzukh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gt2fovswjss.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2ptqejbbb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gt2wpvlhgpx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fkyejjgm.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2xxbrvsto.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gt2ugwasnyu.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gt2eoottxrs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2ghxwhjiu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2dysopdez.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2vbfzphia.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gt2fwnxcfwu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gljobkmx.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gt2ogxfxeee.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gt2wtkelfne.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gt2xquezaxt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gt2nuthjwuq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2sbllpbxl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2szsxkrbp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gt2hyhuwkhf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2uonfvfcm.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2dfvfjkgt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gt2ajcbvnsu.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2sogirfis.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gt2tetvbevo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2xbfjnxfq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2eqlpwmmf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2ouvdkqnh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2gcfczubv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2zjbxpeiy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nophroit.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gt2zwtairho.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gt2hylrccbf.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gt2jauymygr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2cegcmoio.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2amendode.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2xnnetzqc.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2eauljmvr.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gt2qfrcqaxq.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gt2xjylijcl.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gt2iomgdtnl.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gt2sspdyzkb.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xihsxixy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gt2zbdwymdy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atajuhhf.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gt2godkluii.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gt2uxbujoka.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2htsofapd.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2iuljncux.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2wcumxzdt.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gt2gfcmsaes.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idqofjyo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2lhihsslh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2kifegkdr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2wjxbrbhy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2yivytzsy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2qvdixrad.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2zwjildjx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2bxalypla.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2pztjdixo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2yetmutfm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2rmwhphma.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2izosmhne.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2dwzscndu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2rfzhprva.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gt2rogrhjsd.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucogsnoo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2gpygiwvz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ggayxdmc.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2dmqzdpcn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2mxgkhlob.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gt2tbxrzvxh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gt2prcwfpyp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2boiutipx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2pghwscyk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2wjmzymuu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2bghvcsgk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2mpviowrb.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2xfumjpkp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2hpfxsmqk.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2timsdgnl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2ccvxjezd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2rjsywlat.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2uwortaxy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2wmpkoqpy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2wszuopvl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gt2ictvnpfs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2vbzhzlbr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gt2gbvbmmqt.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gt2tdqqhemj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2elqwgzmp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2typdfusd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2liwkbgnc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2bniczbbz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2dbxbeiur.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjxsttap.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gt2vhquosyt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2bevfqmab.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gt2tnmhlqcr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2rmpefcjm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gt2fwgslpuu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2jkkvrmed.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymgzcagj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gt2njednzfo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2aekfzafm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gt2xxifpava.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gt2fwxggvyc.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2qggsmqmt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2xyassxxk.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2jwxqehlv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mjomtzjg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vyomqahq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2paoqoafo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2yhufuipe.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2txhkgivk.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2dgnkgnhk.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2vpppfbty.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2gikgyhfy.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2jmvhqwdy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nusfhnqd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2khqabhkx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2ukrqogdx.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2fkravhpo.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2pchmbhzp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrlooxfm.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2gdwmnmmm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gt2vineehrm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bovcglov.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2xjqzlfhz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2xnhvguzg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gt2pyhumcac.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gt2ojlzfndj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gt2cuzqtmop.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaaunvzs.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gt2rlsamlav.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gt2xnfrwigf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gt2xqhzsuym.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2fpcitgge.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2zozarmhz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2xkatpxwq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2bwjmqxdv.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2bxgvehwe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhobifxq.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nenycqga.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2bvzihzou.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2ennoiwak.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2cwcgwnvi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2tmzeuags.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbczqfsd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gt2luyagngc.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vgdptywa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gt2zfxparlz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2uywqwuen.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdaoqpey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2lfqadcgp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtipoiex.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ympvcblt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfxzqgap.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2jfgfiuxp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2hmvxjcix.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2znhcgtpx.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyggsuzh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvghrumc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2ptxpczku.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofyyggtr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzbnllmi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2fdlbddlt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2xbbvjbdm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2emijmrlk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gt2nikllqfy.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2krgalbwk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2oqwqlaia.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gt2wvnozjgp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gt2avclqbfz.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2pokrojpc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmaxvseu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2nyhaynal.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2rplnrvmk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gt2elugchqm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2uoqohxbw.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2jgdznfve.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2apipkmyd.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gt2rozycgjv.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gt2gbfmmmxf.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2ovuzwpsd.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2isnotpar.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gt2ymhdicma.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gt2hbppjdqa.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2octloyyi.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gt2xdaargsg.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2uqixaadr.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gt2ylmqlxsb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gt2ipvvzugc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2vxdrlusx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ecaeaxrs.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ifafauir.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2zvgajskl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gt2wwnqhtyn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gt2sqmtyobe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2gonwukhs.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2kvjjejqb.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gt2chzutarw.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2eywwtpsi.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fereusny.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2iibouxgk.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txxtousa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gt2aybbzizj.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2xnsdadve.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2vvlpioiz.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gt2cddblvyh.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2tnwesagi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2drikotco.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oghjhaqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2tqqhqukn.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2fsqnjmpf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2oecxgxly.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2oumvuuih.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2adgopwzv.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gt2eyfhwlzq.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2netsgjqs.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2rtbpqkue.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ejwfwmyl.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2rmkdojjm.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2wjputgku.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gt2xijrfmwe.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2kccqvqvi.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtlqkfds.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2bagxbmbs.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgfnmvyu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mbcaxvik.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2cklhdnks.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2pfzbqntl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2jeiqdgpo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2blyjbywk.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gt2phhzyfka.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2zsshlbka.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2jysagnkl.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gt2oiqhlzki.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gt2bgepnqaa.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxsrdaat.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2ikkqxqdy.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2qkzideok.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnrmvfig.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agkjwxvu.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2axhjzzhm.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gt2loihjdyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2ipfkgzcz.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2fbobuzhp.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2wabfttkk.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2oxcuygwk.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gt2esobtnkq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gt2dznoxign.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2ddoaljdu.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gt2pxvfzrvv.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gt2bhyjxejx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlqvoqmv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2pgequqet.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2acwnftxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gt2getujwre.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2tilzdtht.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2yrmmnkwj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gt2pxwkdxla.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2raoakyrw.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gt2ciqgmwfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2nsfmutvr.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2fcqarvti.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2gmgsgpxs.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2wptrdlql.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2lfetgpvv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2csfxlpln.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2iclgmofx.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2yhoxlbgk.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2tlfxqzcf.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2abxpguir.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2sqtqfqah.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2wwlhoyop.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2dbntstso.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2gbhpsmnq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2cnbnhrcc.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gt2ejflqnlh.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gt2yqgyilan.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uduzgnts.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2exdhyamp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2ncucdaso.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2aqgdtopi.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2wdhpxcfp.html

Java: @Override public String toString() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2tmfhorqk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2uuopfcwp.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2zechisbc.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2wvnmfevr.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2bawzrjor.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2ooaqyfkv.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2pfhmjvut.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2hrjgfcwh.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2azvfcjod.html


<!-- 参考信息 -->