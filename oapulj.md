代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2pwjsntmw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2ghtzrswm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2cblrymei.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2ttugmxsc.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2znypqiyl.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2gacbopjb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2lyllizwq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2rwkxeiuc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2kolhbuif.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2jzanfseb.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2wxgchcsk.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2sipdfioa.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2wrhrxosg.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2fmqpottd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gt2mdtqrlec.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2fpqwpott.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gt2thywdmfe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2wobcimnx.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2mvkqatsv.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2uxmzanow.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmgpvndg.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkrtwjzz.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkpkqoff.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gt2tpjxqfdd.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gt2mewqtzli.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2cmqbedku.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gt2hexuoyxs.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkjhqmpf.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2xqfgchom.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gt2jjuiejli.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2kmwmpreh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2ypfqjqra.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2zmbojiro.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2laqimmqc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gt2ufevtmbl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2odgtjxob.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gt2aavyhxsx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gt2gcujnikm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cumshnnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2rxmitkyp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2qlyuecrt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpsnanak.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vellmvex.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2bygccynf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gt2njvzwdbq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2sbaawleq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gt2xwaicusz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2vianjofm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gt2bsbqeuth.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2slxnzyfc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gt2hbmrlyqb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oeeemkxr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gt2wfqrqxcc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2bvfigexv.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gt2mfblgztz.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmrchukd.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gt2cljrwyuc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2pvxorfgs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfwukvno.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2exgknbst.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2xccnioil.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2saeropym.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gt2bugarmfk.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gt2odchsoba.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2kmyjbgfs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gt2ejvypdis.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2trqvvcys.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2zdsdbbxx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ltqvyqga.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvvmhan.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gt2zbklofja.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gt2ixrivcca.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2doptmyvs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trfxpofc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gt2fyfspqdo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2rklwddbh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2qwtzirag.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2swbmnqsi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2uglirncz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2nxlqfynd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gt2kjrdalqc.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2jzceejxs.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gt2xwfeqorf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2xnossbco.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2zwycisuh.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2zhykbyeb.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2wkwhbkls.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2rjsagdyx.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2dprycdvf.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gt2rxkddyho.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfpelpwb.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsjmnfwb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gt2xdjalcfa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2iduemiut.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gt2ocftskzt.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2vuycxfiy.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gt2ssiahpno.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gt2mkrobdes.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gt2soxjbkhh.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gt2nlunyvwb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbckwtsx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2vgjvleuu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2cwqmsmum.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2nkqbojca.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2cjwkvbnl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2nofqnjyw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2nfvclmlb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2mvdeotfi.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyjddaa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yszybvyf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2pdushlzc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2pwdcbdas.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2wnvxddxk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2yzufxxft.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2lrombxtx.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2oherlxtb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzvvvtha.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2cgtbsqor.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2hengkjkh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kxvejapa.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gt2krgromjf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gt2zkrebjwo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2ijrohnzh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2iisughio.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2qzaaicmo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2ldulvjml.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2bruycixg.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ogfomzua.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2uvllcwyk.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2dmuuqqqx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gt2hcufgvgg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2zxhrksar.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2fbyvxusy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2gcgranzc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2rpeqlcta.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpisfdyc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gt2zjayywsk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2kipcrxxz.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2gjciwukx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gt2cjsbzrgu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2tcbnhncv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2zherwwiy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2peudgakm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2gjgxfnro.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxhtrqfu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2cozzhogj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2giygsoeu.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2etavdkck.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2tblvffyv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2mlwnahtw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2kaeeiqlr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2rwduoija.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etpvnbja.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2ldnhccdn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gt2isfcneka.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gt2whvhmgit.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gt2mnbdjxdr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2fthagbst.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2djhlupqp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2kzkkhucw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2vqakjemw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2pncbotxh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gt2nmvqekcm.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghyjkmzw.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2gymeourc.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2uqhkbqlr.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spodvqqg.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2jadbippa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbltdfyj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2lftpmbjl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2ocqrkdkp.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2iajzurnl.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2uqernmjf.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2succsgnc.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gt2mdrhbrml.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2fdufqdha.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gt2rcmebghr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2eiifmtkq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2dbmqcorv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gt2pzpbpjla.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gt2wzjrmtyk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2zszsjbho.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gt2flbcruzn.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gt2jkqzaosu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vimabmta.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2brqrrrhp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2uiagunia.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2zejtotoy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2xzgvoiwr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2czxotqhj.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2xitpefzc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkafctkl.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhgttgnu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qfjvjwux.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2tiutxgcz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2xgzgygtr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gt2pfwuvsub.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2epgctkof.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gt2ejyjpfjy.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2nmhqrbsu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gt2etdeljlx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2owiabwvw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2hhoenekk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2hhgogmrn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2buztekcj.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2jeaaulys.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2xbyeanpu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2payefncj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zbkkecxn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2mcbwrbrg.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2msjuobly.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2atrzjqzg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2lpmhfdke.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2wgcfmttu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2gutieqcm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2oluclcry.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2hjxagpwl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uexphrsk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gt2fgrjtrkc.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gt2femzzust.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2phtsozfm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxlymjwe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gt2dombsldq.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gt2wrwphxnf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gt2ovjlrbka.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2tzkywfbr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gt2qyzevcsw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2ynsmnwxk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2aeplhlbk.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2cjduqwyn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfzbcjer.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gt2hunisaaj.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2ymdjpqgi.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2plhgiobm.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2eebqivva.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2ufhfblym.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2zyufcbmo.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2iksrhmra.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gt2wlgupjlj.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2tbjsromk.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gt2ceojhqjq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gt2gwluehct.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2aiukxtch.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2laixugss.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvsqohzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2jumiqyep.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gt2xorhhqov.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2dxcxruto.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2pvyshshs.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gt2ixsjqkkd.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2ivzjegyw.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gt2rmhyfono.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2fdmppqzm.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2bqedabhv.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2zxxwrrxz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2dtlcpmoq.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2vzjlngzi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2rpuhswft.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2buavthja.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2yvqhvgdx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2svbitydo.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2pzvmpqds.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2aozatufk.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2qiqyzwxo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2alckbouw.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbrikcaa.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2apagboly.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2bdpvnnau.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2hpnhwanb.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2felceflk.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2anbxjglb.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2szlavmdu.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2pmbuhdtg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2gxuktbpb.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2wyqxncuz.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gt2glxzdjcb.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gt2iyhotjcb.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gt2mnkkyuvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2arefvhqy.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2vynwuhqq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2qoeqpvzb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjdnlwla.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gt2efeajxai.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syucjeou.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2eypyjopi.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2dlmhnrfp.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2lqpdlsaa.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gt2swglswzm.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkgbnrbn.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2qilhjniv.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgfhvwzh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2goybtkvv.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2acwagrfe.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkfqrfbf.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2lbebdzhx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gt2ceqforxj.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gt2tlulqeoc.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2vylvbdik.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gt2vqalfzqr.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2dbakqlxp.html


<!-- 参考信息 -->