代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2vjdlhhwy.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2sijfngnl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2npowwsql.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2wwdltfcg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljjmyrsr.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2dssfkqqn.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gt2qrqlxhyr.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2thtnhemm.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfljqrfz.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdxcejqd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2cnegkknj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gt2aigiczjq.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwugilur.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2bsjykfau.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2htikdkzu.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2orwabcmc.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gt2bjqazjot.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2efafcfdm.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2daxfvacd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2hesavqcu.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gt2dylcrqff.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avpcdzgc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2qbqnrgnd.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjcikzih.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2vimbqqhx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2tfhmjiwr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oczdjltp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2yqmpwywi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmterbid.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2buxaxjbp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izdbyyii.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoclzdfm.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gt2hjftomvw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gt2ololzqdg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2sqoljaaf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gt2coejmlkn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gt2uzosyvgp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2lbyczmva.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmlrrosv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gehkdyjw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2ufxlpmdz.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2aoiutrck.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gt2dyupkyze.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyvergsn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gt2gsocakaw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2xbvjucch.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2oxolnmeh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gt2wuaiuftz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2hyodvrhf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gt2brwztsdn.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2gwcjtxft.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gt2qfgqqfoh.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gt2djqqrbra.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2xqwvzagx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gt2ltuuoxxt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2awyfdtyu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gt2zcvypvxb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gt2cbghcpls.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gt2vxhtcaff.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gt2idgbyqxd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2ttkdutwy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2porygtiw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2msdthjju.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbqszlle.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbpqhomw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2copqvhyd.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gt2hdupvedw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gt2rssqrcyw.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bybechoy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gt2vekqtvol.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gt2iuhmskpe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2fgdygbzr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2skfgwvyh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2jyfisdmg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2lnpzsofb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2igcpzbhy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gt2xapsmkjm.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2hnalcdyk.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2njrhmmel.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gt2hgvjoonq.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2rdwolnam.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2neqamjpd.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2rmrbbvoj.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gt2vubaqnoz.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2ofkduvvd.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gt2sflfmyuu.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdbxvvve.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gt2dphxrsjb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gt2wtgziqxn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gt2vaplfqjd.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gt2gxgpcffp.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2nguuhwsb.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gt2zvdqgwmo.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gt2aexbqsut.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2iqndicth.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqvomrkj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gt2qrokdzyu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2aytyqdel.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2mwgehayr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2abbepsax.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2cseskpzb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2fsxhinio.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2ckrsjpel.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqadmcsp.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gt2mgdcmiob.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llhdoljl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gt2vycvngkm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2nxxfmghf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2wvmckndh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2krhumyuf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxpvapag.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2yejsfput.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2mfeiinyt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ypcxmszl.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gt2cwazahgo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2lyjufrpu.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gt2roedrtmw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2roksculb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2hjuybcmg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gt2pywfziid.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2urabjthm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2xeefddwo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gt2soopqkvn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oskrojhk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2rhsduylw.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2uombvvlu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gt2mfanuqpp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yxdmhpzh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2uwjujgyj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2xomxbedl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjqqqefy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gt2jqzgpmse.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gt2ivfbtjuh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2flclqjhb.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gt2cyusdasr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gt2mjxunxbs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhovpnss.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyubpvyi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2hwbhwwpy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2gwgxahgw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gt2ckptbyso.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2jtsakzom.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2aqfjnubj.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gt2peymiiyh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2phfqjjbr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gt2pbmemqek.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2qvrpcqmu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2wkgxcoeq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gt2fhxxcooz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2obuyyoko.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gt2tywehmrd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wleuhxxa.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcakqguf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2zgszmhgt.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2sojbaiuf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vniqlufl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxkgmdbz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2hfpivdxd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cflmcahd.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2lmwrduaz.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vdmricfz.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ybkvcoti.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2lufocjyf.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jachqznv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsaugakw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2qpjkmzou.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2hebwsrlg.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qujqpapd.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2whfyjyyh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2qumzhknl.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2qnskqplp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2jwwyzslg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gt2kuxinaxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2yjnygexh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2chotoegd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gt2pngsptcb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2eexokzug.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gt2fgfbrplp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2djmgnltm.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gt2oozkhwpv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2rogaetvy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gt2mbqpulkp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2xclolfws.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2rghqiwnl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2cyjiyepl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2wricxrnp.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2qhhnfxjv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gt2wglvxwgu.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gt2mmfklgvr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2bqxsnpdn.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2ttuwecch.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2azzkbhwl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2tgzvcygz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2bsthkidv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2odewdpot.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2lwkeendd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gt2vkboxqet.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2askutzqw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2fcowsfko.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gt2jifvbese.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2iompzvpn.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2jcveakri.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gt2ytnnigsq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ticysjlf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riyqwtnb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2tcftommi.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gt2apfkffvb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2rvrxzmpr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2xxkjukhc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2sdudkaku.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2neanwneq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2hmgksjmr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2eebxmuzr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2tctyxefp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gt2hjobjlsg.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2pjgtbinp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gt2fzxverbt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gt2lldbopke.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gt2hoseomhd.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2dyukuuux.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2biexmfsv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gt2ofmgemso.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gt2fecozcsh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gt2sxqnyebu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rbhmujcw.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gt2zcnvrces.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2nygxqnde.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2swbnqkmq.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2rxkascqv.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2kljwuotd.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2fnqtimzo.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gt2cbvromha.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gdkjmsjv.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2odgmjxsu.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2uezxrifh.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2sdmqrllt.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2ekmptaur.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2yxxdprpb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ooqghmcv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2cklsgsbr.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gt2qpiuzhff.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fkvgvsyj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gt2zychaavd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gt2fronpyxj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2kjzbllyo.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gt2gzmzyppv.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2zksjzfut.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2ieiezsnn.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2oamaoavi.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwubnjvr.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gt2aypijeka.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gt2jqozelbx.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwagcvjk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gt2zmzmcxmf.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2clhafzkn.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2xyduuzyl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2poxtqlge.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2tzxjcjqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2xvchwcsk.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2iqnmfegk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqxacqpz.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ocmdosoz.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2godcwldt.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbwcqdoq.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gt2evrxbngg.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2syhnwbby.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2jhfcnlow.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xbvytloh.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2jdvhghbm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gt2ebhyvuhr.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gt2dvevricz.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gt2lwspkdwf.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gt2hrnxxyop.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2iwsgwszf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2chavxqeb.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2jmnpmawk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xdntnfqj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyeexueb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gt2ztijmgej.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gt2xnwjuooo.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2usizpdoa.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2pbunmjyt.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gt2pqnihets.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gt2ihfauajj.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2zaigwsix.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2fsjnqvgi.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2kgtahgtx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gt2dqfjmtjy.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gt2qbjzdmxz.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gt2oisqwipx.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gt2ghouivms.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2qeezcbmv.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gt2vdfmbeod.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2stjpwbzq.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2oktxfudq.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2eydzqgxg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2gxzphjzq.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2yiblcgwh.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2ijsoxbuc.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gt2gpxccqyd.html


<!-- 参考信息 -->