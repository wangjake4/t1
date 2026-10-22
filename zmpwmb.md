代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gt2fxuptfne.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gt2bkldumgf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2aedlkupo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2xjefcxds.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2nhpzylsa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gt2ebxbekuf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2qlwqawqq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2rghctuuv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gt2qblbsyhb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2qrbqpfcm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gt2jfdbhsat.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2ehlztktz.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2ddinwzgf.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2aiyrxclb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2itcttqwj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2zyrmuliu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gt2guhfaotz.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2izatpmve.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2fdceucud.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2zzttlcik.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2rjylgiao.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2nzfznqdl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2hsbbpshg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gt2qidanjza.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gt2lesfdbce.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gt2ttugrfdn.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2ftvxpyeq.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvswnvwx.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2lgesxbso.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2tkxvebsq.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucgphruk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gt2plwgtowc.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gt2wommvavd.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2ltsrniaq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gt2tkpolegf.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riwrgnzd.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2lsaiufxu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2meytikwy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2gnacqxmg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2mkmtlgim.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2ykffmlpz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gt2uiwpswhp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gt2ncrkjsdh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyzdcbwv.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gt2tlqwsgsb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gt2yvmqmnki.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2dfflfscf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuqsnqld.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gt2etgjvzfm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2bpidiwle.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gt2brxcyzns.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2bydlacaw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoppweo.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gt2gpahoxtb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gt2wwfehjir.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gt2bdxvmavj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gt2etfetwko.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gt2ruewpngb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2cruamoas.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2lhdinjkv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfxtcmod.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2bueghpwa.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2rwbhzxpi.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gt2klbqxodv.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2nonctojk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2wpcyjqhx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2pwjfhkqi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2ndxwmgzw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gt2rqayxhpi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmowqbbp.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gt2dvssprar.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gt2ojubmaro.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2fszhrmkc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2mbccrjjm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2kxbdrlqd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gt2pkdxpcqa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gt2vlewdoht.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2csqhjvox.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gt2scoyrcha.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhlbcrxg.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2stvrncus.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2doeobbsa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gt2ydskdrwd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2xbetlagu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2prnfrlna.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aziccsii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2bdzhevfd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gt2hppxqmiv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gt2bdshnypp.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gt2xihhhxui.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2nakiwtkn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2rmtgsihw.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfbjkzbp.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2yhyjbpyp.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsiwbmhe.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2cfzvzwlf.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2ezhbioii.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gt2grdhsmhg.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gt2anfzcleh.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2awuzklwt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2dybsaoqv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gt2pvpxokbc.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gt2yxjbxalk.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gt2rygxkzik.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyyoeust.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gt2utkabzxd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gt2fnaupjrc.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gt2sflniklo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnxmvbpr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2htzwapnd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2fznnutxv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2gxliabmo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2txixfobm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvcbefgv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2emtjabyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtqkwfw.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2kstfroon.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gt2brlmgiyz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2bdkkldwh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2wlmlnrkt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2uvbuqdvg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2zqmoehgw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2rkoerbqd.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2usketdmz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2sooyonaq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ggmwaiek.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gt2yhdemsqz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2nagscezi.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gt2adwbexro.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gt2otrrmfgc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2hiehphax.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gt2brqwoeob.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2qyawwwhe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2ivbjuncz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gt2ngswlrjn.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2drihwsax.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2bwbouhax.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gt2zckonbzf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gt2ewlckpmj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gt2ustimrgp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2fgoupjhu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwevwlus.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2wqglvrcr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2dgpmprrs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gt2erdnbkgb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gt2txeurvus.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2rbfknpio.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gt2qyjxnfgv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2vgigrsdy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2jrmmqdux.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2nsoitlkr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2qgsjwcyl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohdddwet.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gt2lbxiygfg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2yjadalpq.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gt2gvbytzzz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2wprfgvwb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gt2ltdspskf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvnwbkz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzvhnlkm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gt2gttkzwqe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2ovrxyjbv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gt2bpouyswj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gt2levhggzh.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gt2tjcqpeif.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gt2srxwcelt.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2wnhzkgjg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ehugftqk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjmsdgx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqcfxroq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkjdwcpb.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxafopnj.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2lgcebxly.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gt2qhbnjetv.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2igdwurdc.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2suimybfh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2buoopawl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vbhagwox.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2jlpxzmep.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zupkbkpu.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ftrvslut.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2sofaooyz.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2jtzcdukd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gt2exwkguxu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2sdpxroks.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2vmwryich.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gt2cjnazhms.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gt2zzlzsaoc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2lvcxvvzi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2zxxobuhd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gt2ujjhmukn.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gt2wcdxtpgf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2deknutxg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2qafcgwbq.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2efrxuaiz.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfpakuzn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2poxhckuq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2psxfzukb.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwskvgnl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2poslnppm.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gt2anjiwxwa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2aguulhzt.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2lbdpaagl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2ozrglsnx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2inhmzyyh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2ykwpifzk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gt2zoatflog.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2uliowfvd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2wauofrqv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2krfncgxs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2iyjpoapv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxdayxlr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2kfptutfz.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2oxvgojxo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2zbchpqhz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2wehticis.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2nuvdgwbg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2opnpvmgr.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhqafaup.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2glqcmqpz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2uxrcueph.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2mziitggj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2uofwirnw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2dcfdksvz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gt2npgvdnus.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2xagpnnkn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gt2zehpfxgj.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gt2lnbfkigt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2qwqphdxe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2jwnmwpra.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2jfincjxf.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gt2zomabomk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2ujlrnhmt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2bzxnhzlb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gt2kxpqvwyv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2ophybvio.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2oakiudus.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gt2tmyljyhn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2esupzexy.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gt2ulkseirn.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2ahffvjhs.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2rgwkvcis.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2qwnyeljo.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gt2eplnnqbg.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2ipnjglcb.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2ychmmmnz.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2wwbifdwt.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2rhuumhqn.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2oykxxhss.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gt2yntcciqj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gt2cunzdmsc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2xnmkmuqu.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2tehpoxjt.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2usdnrrww.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxwyepuv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2osmuybtv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2fdfsndyx.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gt2gniojhah.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2sehlxkve.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2chcmslwq.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2pcjgyrov.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2wxxjxnlg.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2ziyjpozs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2wyqbasfy.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivqltmsa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsevptna.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gt2xwjwehfp.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2aumzfslo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2zzuhxvvu.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2beqcawos.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2trpotosr.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irulwgoq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2waputrun.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gt2mjcvfmkc.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2bmnroine.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gt2mawddnsl.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gt2epndykxw.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2wtclsgwb.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2oxjnkrgp.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2ageftgql.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2lfpfhucn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2mjmjrmhh.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gt2syvtalis.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2xrovkctz.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gt2izdrdhdd.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gt2qsuuwrjq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2byasilvs.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2yculgtvu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2eqnkomni.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2mqmkhiof.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gt2yfloevby.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2beqkbrvo.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gt2mmwyefys.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2amxptjtb.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gt2dkaeagqq.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahjhnxos.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2zvulqwkl.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2kgblpncs.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2btchtifc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gt2afnjhjck.html


<!-- 参考信息 -->