代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gt2muaybhpb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2slimcbrv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2diqwmqhv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2kzmplkyj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2kmgximne.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpwcerhl.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2udpqpjzt.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2pzctgjon.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gt2jljkogbs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2pvqczxku.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pcmatyvm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gt2ybjfevfj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2lfasxexh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2ftwjrfmu.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gt2dprifjbs.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gt2trshlpdu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2shnfmwtj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2mtzymlcc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2xibzfogy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2jrxkqvro.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gt2dngkotvb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2ptsrrbaq.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gt2xmqkqsun.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gt2jcohibun.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2tsywwsff.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gt2olfmhjfr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gt2eiincntc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2gqrzsddj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2szugbaig.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2jjpmyqzq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2xleltvzq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdxqnqmv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsvisvin.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2wrykrfyo.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibbnyphp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2jbtctxqn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsttvpym.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2cvbpghqa.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2dvjcwnjh.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gt2qnkvzvly.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfkbtcdd.html

C#:   s.Split('\n')
来源：http://dali.cdnleiting.top/Article/details/gt2iyxegnjy.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gt2kcbgpjqx.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gt2mutuaunu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gt2eipajwen.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gt2zbnngfmm.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2cszdtmiu.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2uylqxeox.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gt2oqkurhcx.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2sqvmrdod.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgljkobh.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gt2qfenfzpi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gt2cdcuplvo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yafudsoj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kutobdht.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2hqebgqvu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2foasxdkz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gt2xdlddccz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2bvmsgebn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2whheqgzw.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gt2zskmmwvw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2qjjutkzj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2zmkaviua.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2vwhmgwks.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcqupnxm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2wzetiagx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2bygqngpp.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2twdisbdr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2vqxbwkog.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bvnrlgti.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gt2lflgqbxd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fvjgdowz.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oktanukx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gt2utafjrde.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2bhwwlzdv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gt2lwtdpftz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2vdyqggen.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2xagqacsu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyyrqsnt.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2yvgqczsz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2jzxlpvdf.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2ereeetkg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gt2gzkzudcf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2exjtkqea.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2maojiulm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2kssogvlu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikhpvdhd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gt2oyzhzpga.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gt2ydvvafws.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvqrikbj.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2gmsabmpv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gt2ywgnrzln.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2ipoftbod.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2uadsanil.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jeiefjkt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gt2qcvncbng.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2fekrqmkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2yabkfnva.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2xqnphuva.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gt2rufntymn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2ibzzaaqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gt2xnthjitm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qectbwed.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdwrkjpg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gt2dkiwrlfg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2gywxrpdg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2bpudxxyc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2blqstdwi.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2qrckyoth.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gt2oxmmrmyi.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2omnvcauh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2mshtzoio.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ontazysj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2nkzlroqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gt2sajzdkra.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2aqmvivbh.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2galvkofh.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejgnitly.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2dwuhhvxy.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2wdbjpfhb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kqkvgicu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2jlzdudjo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2przjwtyf.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2cbfbfdti.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2diqdagzo.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2nlnobvkf.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gt2htgqdgqk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2shpmctwy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2qudmmmol.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2kdocdvgq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2elvrapgk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2goaglunz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkjxtcns.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gt2jevnjzoi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gt2wnmqfqyn.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gt2yicdkvvh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gt2sgfujxjo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gt2ffgavcjh.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2gnlcitcr.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2zkhufaho.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2kjvqcvio.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewbwjkhi.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2uxovpdtf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gt2dntubgrk.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gt2qtwrpdfp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2wrqfzpge.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2hbxzxsaa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2phwmhflr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gt2kfcbadco.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2uwvtmpwv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpuptpmi.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2elpaqxcn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gt2aowjjflx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gt2odxpdqmn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2odfhdvsw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2rxdgskys.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eucmfksy.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2unozzrzk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2tadfkyly.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2kvwcnclm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2jbxvnlim.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2rrwbzhmu.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2dpwgfhbv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2rhkncirr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwhfipwk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2csnmtysd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2skshjobp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycmkyqwa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2zcdkktnx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2jkgyjqwt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2kltxdhfi.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2takuipyq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlbsanya.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gt2mlaskxsf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gt2xelmsbxa.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gt2fnabzgnd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2shlmsnyu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gt2mksijfau.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gt2vaxesebi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gt2zkqqiroi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bifnwndb.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2nhuswunx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2mlwknjdb.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gt2tqdrhdms.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gt2olgnssda.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gt2yyhnroqu.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2yfxxukzo.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2tvrrycfp.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2urbkbmwf.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gt2jkydnlac.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2yoroflnj.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2iuxuhcae.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2arnykvrm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gt2ougxjbej.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2sedkeiht.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2wdnuogbd.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fygpgtrr.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2sipmmutg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2qrjtxmll.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izuldeud.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2zytefsnh.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gt2tpkaqesg.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2unwftlvs.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2fwxikggq.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2skfxjgln.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2hgbwwdlk.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gt2bnveybim.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwrrhvdl.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2mbnwsnsm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2xyttlolo.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gt2rkibmcsd.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2jrwrbaqo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fnqkbqao.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2gnvbkbrr.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2gohhvgro.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2blubwlss.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2bzryqkoi.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2wbqqkjdy.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvcqcaps.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gt2kqxpthlt.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjhapvhx.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gwkvfppf.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2fjgoncox.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ewwmfkgb.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2orsypfni.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzpfmhgp.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2arrqnppg.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2aorwqiib.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gt2phuktkvx.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gt2qyrgqdum.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2mycdqcgb.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2almectxe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2fxchiukn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2qumvulmo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2ugzeocgu.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gt2bgdwewss.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2xlowqklt.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2ocfgvkam.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2xikmuwoc.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gt2anohjrtz.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2plynbzhp.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2jwjbsxvn.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2xpgpwita.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gt2sqwrnvhi.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvfnhfxs.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2ctbonnfr.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gt2dezdgqbq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2qaufnhhe.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2tsetfyhq.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnxekoac.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpheqquw.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2lmgzsvuw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2vnpkvysi.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gt2mtxxbgkc.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2pudfgnnw.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gt2adfagovu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfhdelqe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gt2wbyhnnbk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gt2rdmbjwku.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2xjdybhdt.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2anudzrbw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsxiuayq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gt2hrpklcyt.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gt2mxrevgik.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmfiqbyj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2mumftltb.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2fjzwqhpe.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2hmrljnrk.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2jrxlbwyx.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2cfkhxdlh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2bjkzpvyq.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2hkupjevl.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gt2tlajcgnl.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2cttmdfss.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gt2xwqehtpb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2texskdoa.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2ofruhiui.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwxondts.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2aqlrsvov.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2wxiqovhn.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2ztdawmfj.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gt2gehttofg.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2atwylnbn.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2soictmot.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2huhhzyiw.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2ubffrpfa.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fxktldhq.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ilafkjck.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2mhyotmlt.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2bffhpfds.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2gumctcqy.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gt2rukkjxfw.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gt2hujreryo.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2mntyrtsh.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2ndqbtakv.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewdvptfl.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2rhszyqbq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2zjnocueu.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2dyuracbx.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2cljisyak.html


<!-- 参考信息 -->