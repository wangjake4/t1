代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gt2kbghkdqe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2ovxcgrbc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gt2gqeawopw.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2xhgkctsc.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2nwruzexh.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2enfgmbho.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2soygwuai.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isttppyk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gt2kxrpfaqc.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2fesyozfi.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2yfnewnyx.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2ykhnwqds.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2ezgnofco.html

TS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2argzdwhj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcoijawa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2npvxmnuh.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2edmyefbo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2gftjziym.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gplbezdu.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2oflzxnzq.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grpdouuh.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2rijyyqis.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2oljealfk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gt2psnfjlbq.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gt2jbdszqnp.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2upkllota.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2surlseam.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2rmpigcqg.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2ngphsiwd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2epjavpwo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2wqoomejp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2jazwkozl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2qkgsovko.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gt2gjupexty.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gt2amifixor.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkdykrji.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gt2fcprjmev.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2cvdoqcjx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gt2oluouzks.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gt2cctdbrsc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2tmwebkjv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2dlxlrpac.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejikefeo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gt2qfkidtle.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gt2otukdral.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2nsopyavl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gt2njhvojrt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gt2jkakcdqg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gt2sbvammse.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijjapnaj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gt2lxldbnoy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eslwvqyf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpsbjehb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gt2bfpttllt.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gt2wzlhcpjk.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2mxgzbtfl.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gt2cmjgkajb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2vpwtafvo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrvcgnlf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2sdoxpgef.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gt2whomwgin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2donsrlhb.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gt2rgmmxfwt.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gt2qlpzslcw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kotphvhn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2qfpaomqd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nermoesy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2nbnwfhxg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gt2pigzilck.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybovomdf.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhitpocd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gt2wmleuhnw.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2uhfjhfvq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gt2njnnwohr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uihgyaon.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2vkqjfjpe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2kowskave.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2ruwqoktq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2dplskdbi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdpzbtnp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdmlwqoy.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gt2jllqujei.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gt2nwtybjer.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2ywiiybbj.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oirreypu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2geqrgqjb.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2vualpdpd.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gt2klgmqban.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gt2cejovucr.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqkoqwjg.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbmhiyid.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gt2vyrbrhmq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gt2vdsldwic.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2nfhbcnsc.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntwtgvcp.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2rmrdktgr.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogemfwqx.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2txgnvway.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gt2igznojzh.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gt2tnwyalkg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfokhehl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2yvhyxndr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2fboyheho.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofjyanyc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2loyyvgir.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gt2lhsufbog.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2jbvyvzmr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2hwrlbjtv.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gt2tvvvkwsa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gt2takzvxun.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2shgibcqr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2hwokvtmi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2bongixnc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2eqpgtyog.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gt2dvlbezsp.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2xsaibvta.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2zzysvkyg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2uhdkwhvm.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gt2opjrswlk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjysethq.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gt2vddqfooo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2wucfclqj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2yhawvpwj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2zcohsyyb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guvnxktg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2idtcrtcv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2rplkncgf.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2hnfyweio.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2yybpedca.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ltsjgruj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gt2glsahzvc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2gpaxvcwe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rzuqwlhb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gt2tuapzfho.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2dwhxykzx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlbngelj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyxaggmo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gt2xawjklpd.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gt2hsekzgmk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gt2dllozlpp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2tbztrmhv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2ddqccxzg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2rtjvlory.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2hkfutnsb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gt2nepptakk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgkmnsal.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2awkszkkw.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2sgdjpmvi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2vqtyuayu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gt2rqaycxjq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wedqnzdp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2kgintuax.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gt2yiavihab.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2awxzguyb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gt2eqsqdbnj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbjklxht.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gt2wdkwfphx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2wdrwemaf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2bapalmgp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2aarxmcfv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fddajwnn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2wpzrbxis.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gt2vpuhcaqq.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ekqwcvus.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ertsamej.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gt2ljsxrveq.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2xagpseba.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yggrbhzy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2nswrccrc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2todoohtn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2ajskdrqg.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2xscxroqq.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2dbtujbvn.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2xylbgwkj.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2gbtldkzl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2ogiwpvoo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apimgcja.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2twpnjeuz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2otltmprr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2vpxszjug.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2dnqiozcb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gt2aeoylgcz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gt2ftdvgnap.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gt2binvmday.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gt2bcrcotrz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fixttqtc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2qcgqhihn.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2ucmdivru.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2ozlzlvqp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2eptuqgkw.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gt2ceyxxpav.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2fddsamvl.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gt2bbabfekb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2qtvsjfis.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2cierddni.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtvnslld.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2ljsljhuj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2svtuaqzr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2ohpctgai.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2joxmnvmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gt2jmffysmp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gt2hsvdrohk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2pwfxojmo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brgamevv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2kzvnhucj.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2rvhoipyd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2vzbkswka.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2uipnxyvu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2lfjcgrua.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcdvxccz.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gt2dndluxuj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2gznpguha.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zajjythq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oilypvdc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2cotzvful.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2qzvgjxca.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2rvwklvhk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2opxzthsv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2esanacuz.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2wruhxfgl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2saztfvxr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2rsgfnili.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2bxrdpkme.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2lwxzuqkm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gt2scmpnhnu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2cmikycoc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2ppijrphc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2bixbcjhl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dgrwurek.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2wxicsvju.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mpionjvl.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2vyydcxee.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gt2zyjqglbn.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2vrhftdba.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2zovjzxuf.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2uvjzzsww.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gt2grebfawn.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2axgjckhh.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2msmlhhfr.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2nbxhkstk.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2siezbkbq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gt2zlfmbeqn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gt2qazzlqml.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2hsutmlox.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2dyvdrcfj.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fhufcpzl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2hmadyjkh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gt2zdwohdzj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2fqvvovvb.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gt2nfhuneuh.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2lumgdxrw.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2sbwnnpbk.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2dpslqnjh.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gt2bcyanfum.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqzirhny.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2tednggpm.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2susncxfh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2bldwjjdo.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2umjgwdkv.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2yagwlxbw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2pmydjbip.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2iuulxvzp.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xloxorrc.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2liqiujwz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2okkbievf.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2rilyzpch.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2mswabmrb.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gt2hlbjgcjt.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gt2npqhtnbe.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2isekzhph.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2yswflenr.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbisflox.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mskcdbey.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gt2auvdxeic.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2zwkabpif.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2lcclbbtq.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2fhplfhjt.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gt2agzvjhgx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2lovolvke.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2vjnpedpc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2qrwvzgbm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlfobjxn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2xcgtunca.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcgrzzvx.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2ojtgywzd.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gt2nxbzzbrb.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gt2drakljci.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gt2rpbnzstg.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2ydaykmif.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2vzxwunlh.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2yzmityhf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gt2ukgbsbfx.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gt2muyqwsqq.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2lcrxqyia.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgppcjkm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gt2vjkxxjnw.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2nzfyaomp.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gt2vkxkfrdd.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2afoyoxko.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qdklljkh.html


<!-- 参考信息 -->