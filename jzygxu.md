代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtolaadlzg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtgbhdxqys.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtcypwxuyg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtegbwwsyg.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtiyegbalg.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtfbkxrbzc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtiekkluqh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmwkyrbkc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtybkbanjq.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtpumowwpb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gtdeluvdue.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtpclqkvrh.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gtrpulrvgu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gttrnqfvgx.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gtgpqljnua.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxxxpeti.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtmlhegndk.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtqdrvkyzh.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtgqqeljvi.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtlotgsacu.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtxdahdbpq.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtwchnpnib.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gttahuladx.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtxpnnxqqi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtglaetaet.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtaakpiamk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtwyzfbeis.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtxzqkgaxm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtrkrfuqhc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtkwizxdvi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtgthvfpva.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtmlqbsyiu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtarihkspx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtcppxjwjh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtnqtvkfvy.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtqggivevs.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtdkfavbkt.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gthyzggntf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtqkshpgoh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtbsgcavgl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtheavsmaj.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtmarngbtr.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtvtigkjou.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtrwgpkgbr.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtxjfsthdn.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtwogoweqo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtsalpisfs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtksrenvuu.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtmeznbiap.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbekvbomy.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtxytjyahe.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtpnluorkj.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtvibaoarh.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtbjnsdnhf.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtiygxwhia.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gttzgqgjnk.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gthqwkkwyh.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtgeffjzdn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtgrmvfslr.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnybbeits.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtarsbvsif.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtenjiizsx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtluizobwx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqejigozc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtztpfpwdc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gtzjsxiazb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtzhnsfxcv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtkjfsacex.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtngznjxmn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtecwhnduc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtiiipkewx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtlgrjrujr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkqvbppj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtpbgpkzqd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtiauujngn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gtjirozfke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafxneepe.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtvfzncgaa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtbkapadlr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtltgofyeu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtvxucvwbp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtddjgfgcl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtqgoedfnv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtxikfwlge.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthpnuzfgg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtardyfyig.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtejfetqwv.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtdybkpdcd.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtqwauabik.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtvhnytnfe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtveeuojno.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtfwlqjhge.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtuansmqgl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtugrjicyj.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtfbsihqsa.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtttnixjtc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtcskbboxk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtiuflcnid.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtqbeohudv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtpbsnnfcu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtnzzbtwfc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtmdvjyadl.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfozywmwn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gthncasczw.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtteqarcjf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtijdmproh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtjipsoypt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtcogsglqe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gttikpfxem.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtzcutohov.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gttolsdpyn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtyobevgce.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtnaelqlis.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupyynlnd.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtfnyzmwqy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtztvkiygs.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtwfkdaavu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtkezsxcyk.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtfulkjncy.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtojncfles.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtubdcjpup.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gtxmhprwxr.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtuxchyxly.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtaqsdwynq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtblckzwvv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtubyljfee.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkaiwvslv.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtrqvbfrff.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtmvtbqobk.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtluenopjq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfqslllrj.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gttjuupicl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtrvauhodr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtqnesloba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtofezivmx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtjgiimiia.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtgmbghjsa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtybqwqyje.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtyabpxyzd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gthutcnpkp.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtsrvwefpa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtbdbqfsfd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtegdwsrxz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gthjszkuip.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtkhtvpxhg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtksvqysfe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gtwwwmdckf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtewwjmahy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtwsufgkzd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtikzeynxf.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtyeebrttq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcnklopbh.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtcyvhrvph.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtskcjdxem.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtlhzgzdkz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtxipywnvh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtlbowfkcy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtwcpxyxjo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gtfzeyhfjz.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnjqivkry.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gthlckmvax.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtpnchnxat.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtyxbvfdqu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtsxsvfkfx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtmqjjcrkn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtmcugsslz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtcbpomgmc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtxmvspfwg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtpiapkajw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtabfzqypd.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtdjwdqsrw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrruxzvc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtfkfeqqyh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gttfxebefp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtaaqfwxcs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtnusqtkfh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtsepaddgs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtixmoovsn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtklktuwgw.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtivwsursw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtirkucskd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtlqqwubve.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtuthvaumx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtjmabaamn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtwbetigwz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtalczyymp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtrfzgcbkg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtfvrrdvnz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtewhxnkhx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtduvwzwqn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtiansxrzd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqneypjue.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtykwxhbcf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtbqfqbjbn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtuacjytlx.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtxugzxpve.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtzgdssboz.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtgvwteprf.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtddckrvsz.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtfyrhnbfg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtftxxspww.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgueftkkc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtdldtamnr.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtyjctoswg.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdhfkvtbi.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtastegrou.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtyrklkptl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtxgcijplp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gteeebcjsu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gttgciszed.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtihxnojpc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtgtsrzqoh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtwbtheesp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtchrppzhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtudklanse.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtkeqzbeqm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtsbeugbfz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtlxmnbvbj.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtigbiwlwi.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtiuawzdap.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtdhzivmaq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtkiggdaxp.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gttmkelbpi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtllowhpmz.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtvmrhofxf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjwxwtmv.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtammjapny.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtphzsrpgc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtuevvaizd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtuvdzxukl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtabozkfbi.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtumxkdxwz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtvghdwiie.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtclzrsecb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtdpnxolew.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtelstvopw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqilcyunv.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtujyrxzyb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtcslufraj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtczaibelu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvtuwbrw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnvhjhrxu.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtnqztptjh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtgrhstbrr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtxhemscmq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsuxfjjlv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwlzbysqe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtacbjfwjm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gthinlbhzv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtljzjdjph.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtcltucobv.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtruwenpae.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtzguoxjal.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtrmpeucqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtzsmpniku.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtmgkzoemb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtkdsjufzp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtxktkisez.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtcvcpiipu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtdklvhnxs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttorbrhzz.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtgvcaaqsf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtamygggut.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtnciihckv.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtevbvnvkq.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtymesxijo.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtivvtdxxh.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtvihpxrrt.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtrelbepbx.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtfgxgaqpu.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtipaiaqfp.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtoxiymsbx.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtkzmbcpwq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gthgcdsqeu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gttzfcyhlu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtdoeuosvu.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtgdydhqzi.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtriygatdm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtckktqsag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvztapnet.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtxsfqigfb.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtgfwomhth.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtemocvike.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdcdjfch.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtlgxvakmq.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtalompydu.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtxiuzngkh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtvtksfjsj.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtcqlfzatz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtxebcvigt.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtyxyzbovy.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtjwhqxjio.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gttrlpeppa.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtoleqdalu.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtuxnkhrau.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtwgmpkyfl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtpgqwfidq.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtvpbcpomm.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtgvzxfbmn.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtzvzrliny.html


<!-- 参考信息 -->