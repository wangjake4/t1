代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtgvxuhenz.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtycwtafmp.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtvgmcuavv.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtppzzpxsi.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtwgqseefb.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtpgljqqpl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtgnzlmbsy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtogojjruu.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtnxgzjbxk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtofnqksum.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtwqndkena.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtkuoihgnm.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtgbvmzxwf.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtqhieyxni.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtslhtjbzq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpokgnnxh.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gthwfdgrir.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtrelocmlo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtsvdiyjro.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtzgefnzlx.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtrbbhoiwu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtfrcqyvxu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdvygofa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtzwzrxvhp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtjksxrpfw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gteibfpmkd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtskriqutr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtlwjvmywp.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtwikaibfb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtormunuyg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsagmywpo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtrhtiexll.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtsdmwfzhs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtsobafarl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtudfmitdj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtstgikzti.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtplbgilru.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtrubvryne.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtdktunhst.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtnplvqnmg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gttkqaazuy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtbhaacgob.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtlkmhnkeh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtywtbylru.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtxstfwpto.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtznrmuydo.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtcukwyevg.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtvydepqyy.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtqvmnyggt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtwobchsdn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtmkayjncg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtvtykktns.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtexpglxuk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtumgcqbmq.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtnuppcwpq.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtjhxtbevd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtfjsccgse.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtkhsxbdhg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtxeqblmly.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtrmummazk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtynhqcryv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtizkcykws.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtxrcizbnt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtrsgamaef.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtvtirryej.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtythqprtx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtihsglpzj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtwapkprzs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtxcveewkw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtfqtzpcnt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtsxnbmxyy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvgfubkv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtmseukiga.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtzddoyfni.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gteqnwlfuw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtcvpxyfmk.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtbidyltpr.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtjtwsbxnx.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gttxtkibhs.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtiyjkofns.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtucpynphn.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtrlsouhoc.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkajyimi.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtvjhxydol.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtnpwetadi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtftmwluhz.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtsfghxeia.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gttalyatxy.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnjykalh.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtfgatsquf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrxoamjhs.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtceabzjpc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtzdpbmrtg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtpnwkojhe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtzqolhsjh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gthtymykbu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtseyufzxg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gtfvdhytpq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gteicrguzt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtydpgiywm.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtpvnypwju.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtnpmfvgco.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtzyzurbnp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtihnujgio.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtsvmqdutc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtlsjnaivs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtwdlsxkej.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gttleatlyg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gthbszqjct.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtcvkvfmup.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtovicuzux.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuqbxhsjz.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gtggqajlur.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtyolvbrrt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwnmozfuu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtuuijgbvy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtrqnncbob.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtcmfmrjti.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtovcjkaib.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtydgspduu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtigjmoawz.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtkmexqqdh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtfdcorwcd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyzutfoqs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gttfyqgmsg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtebiwglbr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtcxeiqopw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtjsvpzjem.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaximjhh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtmauuwghh.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtqeaijrsv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gtyfbkojnz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtvjgxptwy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtwxywlrcb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtdueflgnj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtppeuicad.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtlnbwlknp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtivbqdzju.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtibllanls.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtubyempuz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtqafzfowm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtczprhihf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtufmkfljh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtyxoohfaj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gtmlskmctm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtxctkvnjs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtxhxdmmtb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtgpgrtkhk.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtnkshwezs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gtjuhnxuuw.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gttyhgkxqi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlwnsxsef.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtveflkksq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtuppptpig.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtusvhyzin.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvcppumbb.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmfrrwvza.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtqzybskyq.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtayhsrzxz.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtztojpnih.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzuhxsymc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtwznzkdgz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtguaagflc.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtutabltaw.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnmycvlvx.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtjadjnpvt.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtffxajinx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtngavcxie.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtchykqucm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtqyzyitxk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtdbluyfoa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbpddtqm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtnewlygyk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtguehpnpu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtpycxtjgj.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjsfxzxo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtzqazwlec.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtcvbwmbcg.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtpwcjwuog.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtihduaqrw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtxvmmzvmv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtiqlupnfc.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtrvneufey.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtpvbzqnej.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtukqpzfte.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtndcojdlr.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtesuxrwbc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtfsvysbva.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtwkoeerss.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtzilleylu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtfawiwaig.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtmqkoqjwp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtzbhqfhnc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtidroaunw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjkolgubr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtyiciombe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrncahugk.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznxbgvsx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtpuxelvgg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfbqcfyzs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtuqkdpxcj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwqedpark.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtrvxddqhn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtlrshxfrm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtdlvbtwxl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtlrvovcxc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtmaxjdpcu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtluyjzkmj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtrkdwaisp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkpftunsa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gtotylflux.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtkrjgvhor.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbiaoqre.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasioaibi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtlkmgwvyd.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtucavvshd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtgbgyqtjy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtivjxbtmc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtikzrkgrs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtzvtwsigh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtncqlzobm.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtseqxkdac.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrgzsrcem.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtldvkzqvy.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gtonblgwjq.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtbosnwktf.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtytmdqfat.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtjfewrdce.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtrmxeleus.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtlkdqtfoa.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtromejcxa.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtabyylrbk.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gthsfarzne.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gticszuoui.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gtczvjmngm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtaqxzqajj.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtwxuldyal.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaxtigyln.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtvovrvazz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtmeufgcbk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgdodedae.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtucmfwsgh.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtqfnozcns.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtkngfizya.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmhvvote.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtvdhxxyjd.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtkihpgmds.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtrexdgzpa.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtkpotndvg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gthjhskeja.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gtsqfyykqn.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwfudglf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtpflxhzbk.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtlxokgmym.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpriewuk.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtqpvizzku.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtcbhojsvm.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtxjrymcnl.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtupuetrts.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gttnoewqpg.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtvkdqkjhj.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtobwvlxaw.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtiojawjwe.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtzpvxbchv.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtieaxfjug.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtnllbmsmz.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtbckqfhxz.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtxllypjbb.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gthpkbaiia.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtncmcpoqj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtbwnrxykn.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtwunjbvgj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtfobczkqu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtysvmynno.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gttwhsukvm.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gthxtcqjjw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtmfcvwrvj.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtrfiorkqo.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtucwdchpr.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtpaeiboud.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtgecgwelo.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtnppbxnnt.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtcwhyrhtg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtvlatpjxd.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtvifypsaf.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtnxkoystz.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtfowmfodn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtwcnbrswx.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhbzucdf.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gtlzyuzmql.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtntzcaklz.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfkjclhsg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtzubmialu.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtrhhicsrn.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtoaxpwunp.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtmxoehtnz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtmifquiyc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gthgexsezt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtbvcyimqo.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gthhvjrpnf.html


<!-- 参考信息 -->