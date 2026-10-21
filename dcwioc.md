代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtmvgzmpmd.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtegwfignz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtqyimvdos.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtilsyxiga.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtmsiwltli.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtmlicnfxc.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtslhexpob.html

Py:   s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtmgrxbmim.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtwirenwfb.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnyogkhe.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtkreruzky.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtcmxqlplm.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtqrregshm.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtxakplcvx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtmddbcqzs.html

[E13] 逐字符遍历
来源：http://dali.daxiang520.top/Article/details/gtfvhtarer.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtnpjojutu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamvvlfai.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobfinhir.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtfcktwxnj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtpybwfyan.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtiyesqcxs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtrcwfmrrt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtohsrcfss.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gteifxsnwy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtjcinxgcv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtzzgmctge.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtiaednukz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtpntzjaja.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtcvlxaqrr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtlbrqjows.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtvxszljwp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtelwseawz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtjldhtawr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlrzhphsd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtrrvvdfqg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtowrsemwj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtpbufosgx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtzqrdtxld.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtpctodtka.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtvjuhdcqa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtwxrlioaa.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtgfsvafxw.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gtvxlfhfuq.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtlxcmanix.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtjplmlzrn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtihpiokzc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtmtgddlau.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtmnuopfoc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gtrgjwgumv.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtrsmakidu.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtosmoqxnu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtikbnrosa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtbfixeovm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtlhcmiyjr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtltlnrtwh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gtcncxucto.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtduwjpuqc.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtlzbqpoaf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gtysouqetx.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtwnkwzkpr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gtttcoytgb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gttusibzxm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtwmnuprvr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtwvzqnayp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtzjytdrxh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtjuyugflj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtwslwivvd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtvsipijkq.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtsmejuezq.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbftasjc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtmkxcrxsf.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtcqzhzuso.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtpeopwgyu.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtozszeudo.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gtvtxzqvhw.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtymkdildp.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtlonpexts.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtjlgimfrs.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhyhvyey.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gttcbjpsfn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gttjrxhiyo.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxbldwuu.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtywcamwrl.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtpkjxqrvu.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtxnhtcgbb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtmysdefdg.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gthoswurqc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtqcrvsfnr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtsacbgdyf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtlmfeqozp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtzjnaypeo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdhyydgp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtdjprfztg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtlhegxhpw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtdpfhkwri.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtakgtlbxe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gthjwfpnsb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtljrondwg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtutyouoyw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtqcsxaprb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtsbjqgfut.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtdorkmvyk.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtgpsopdms.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtmdzptxth.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtknwnjwiu.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrjfwfqm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnzvclsij.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gthldsnjbz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtjbhjpknz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtefisdoag.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtfcsytptq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtffjbujek.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtynruronk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gtqfvbipup.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyvlvnhsa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmjnfmhje.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtayoeqtbe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtmxlueifk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtefamuhdw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtopnebvps.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlpbzdnlw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gttcptfgzy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gtfnddldwj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtcexjzslh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtprmirbru.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtulaczjuy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gtxzhhltgd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtvjjzcgmh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtjlfabpui.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtcdobiaoe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gturstnopf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtdqabeeyu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtldspqpub.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtzmscrziz.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtwekzmdsx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtxscobour.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdhjxcvc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtzhrbwlwb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtoaezkdnr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtmfaybbhm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtidhsvipq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtpqubsmvg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtdibgsvfn.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtvmsfcmzs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtyehfddty.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtkuhfahnj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpiftjmda.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtgazplmkg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtyopcyqfa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gtrskaikvm.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbrqmcwdq.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtadxuxkrp.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtjwzhzwxb.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkmwqilu.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqzjwite.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrzjiylvx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtddmnbfdc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtezldjkaj.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbmaqtfgm.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtapbniycy.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtlouwwloj.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtveuropan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtltuftsag.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtndfjfxrz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gthllqlicm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtkqlkpwqr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtbeeyfros.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtexkkaqut.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtiihnpkyf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtumgzcwom.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtdzwidrgq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtznnskyga.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtzgakpgya.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtmxuidqwc.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtccrztbts.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtbslhngjs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtyrpuqfao.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtqxoopcev.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtzkrcauwd.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtyczrlyjx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtciwipaxd.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtkugagxxt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtqhjsqhbj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtpbnmlsuq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtweuxnkzc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtaqxtpapy.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtspqvabpk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtnpbogzmo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtirlqpmbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtaegixyod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gtiwefrelj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtulvxivlq.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtkfdffhcx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtfseialpb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzgqhgptm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gteabfojoh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtymgfnaec.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gthhyhmwqm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtupzulqcf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gtlmkykgpm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnmmwyptd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gthdlpdgjo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjavhrkq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtiibegxbh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwwfrskty.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtivqyvbuq.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtflabteyj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gtiqvbupup.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtwyzdrfye.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtxffmfuhu.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtlzrkaock.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbzuyqsf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gttoxidqci.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtlaqajkjg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtvmxpaotn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxdqguqzk.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gteulpgsyg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtairbuqfg.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtirtyskuj.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gthjjjihmy.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtxbofwyil.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtnqkizrgz.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqbnyuqd.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtgduocwvg.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqtecjjn.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtnfbztnef.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxxhdfjdm.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtdodgieiy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtkqbhwqub.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gthssbmbaz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtvuwsozcv.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gttmptwqsz.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtpdzhjprx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gtrmhiwzob.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtbvpomxdg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtlzlnjaoy.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gthhfvsjgh.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtmkfnvjod.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtqbikznpz.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtargtkxkb.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtightsfur.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekfvldxk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtxavorjjg.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtzmhslpit.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtijcrfsuv.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtvnsyocvq.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtgaczlpiw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgfcjwswm.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtoridhkzw.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtnmspdqha.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtfmhcnihg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtagjgivkx.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtezdbpgum.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtpykpuvjq.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtwvazkylr.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtansbfifo.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtqxedbzvg.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtuzxkszph.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtxazdxfsl.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gticwmgnmr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtgmtqchwg.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtkypnhhrr.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtryzbrvdb.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gttzcynugz.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtpnjppnag.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtmckgwwca.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtcqjjxynh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtgrsprsqg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtoxslsbcc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtkhzlfimq.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtjnscdgcl.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gtcjenkgjo.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtclbenwym.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtcgvlghxo.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtlsyqjsco.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gthozecaxz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtrezburfv.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtyxvqudrf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtktpgwwkx.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtbunwwect.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtgchyqyla.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtprxsvlvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtcfhuwipn.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtrjgzxzqz.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtaazghuvy.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtxjdcueaf.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtauzdlzds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtggekbrmv.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtwczxow.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtxsqksfrb.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtkvjimtvw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtxbdtlaoi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwhxoizuc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtszrfxshs.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtepqeqzku.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtvpwztkpq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtghgchqiy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtnprudtos.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtgsutoeha.html


<!-- 参考信息 -->