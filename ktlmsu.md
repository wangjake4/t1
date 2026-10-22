代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtanzccoim.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gtejmsakcr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtetpdaoyi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtglphlgmw.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtooxyinno.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtnymkjaup.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtrvvwqbyy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylyrylru.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtsldanbxq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtzyueblbl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtepzryuwh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtmjrbdggc.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtiplaedmi.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtabohzabr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmldpcmga.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtywdxndcv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gtmoexxfah.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtpjpdvfpa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtcrwyfamv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtzkirdyfv.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtbvazadtk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtiictxwyd.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtppzxsclj.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gtygxmjxvv.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gtjwlhyfcl.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtvtmoxppw.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtedbubiny.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtxpfwwexq.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtutzlnaam.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gthggnmpvn.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtkovfvezj.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtmejpvcuq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gtqhtdldif.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtpnkgclql.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtpotqmegr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtdyybuicq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtnzmdethu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtzejvwmyq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtelgzbneh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtyuspgvtt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtgsbkodml.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtdmcsxnpe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtskvbcmab.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfddwjofk.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gthpmqhblq.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtsiktwbid.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gticudeznn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtqesmunhm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtjhfvenbl.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtaemqnebk.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gtnlvsamlq.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtggoalgqa.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gttfmecqoi.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtvhbsdmjk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtapvcpicu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtlnipjyjv.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtqqnhiari.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtdzcusvgm.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gthdpbdpmb.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtufwjvouu.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtesbvxuat.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtcxxkoclj.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtgohozzsx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtuoptsrpk.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtykgsyzcs.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtqoamqlim.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtqpcnssls.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtuapluezm.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtcyzoqkzi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjlzudxgs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtdtqaunzr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gttkfkgzjo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtbkwfhpmo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtbizqyalo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtsfpwvgrc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtyvmxonha.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtxifyxqnk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtefewcbap.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtdxqmhcyu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtyryauudp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtardoaydi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtoojkluoo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtkkkqrrqt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtytwuloor.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtszjlnbgx.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtgdpeqyva.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmaqpgts.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtdtfboywl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtsylixxom.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gthqibjkkb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtgxzdtzki.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gttoissbbr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtvtuamvqu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gttcipuzxm.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtyfnaymqy.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtvzqvxvqt.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gthodnokwx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtipoossib.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtmymballa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoccxhqe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtchegjgcl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtcwkawifj.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtkoeigueu.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtftzbsjra.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtcjrkphrz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gthmklbszw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtmzbvuqwv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gttqlitqes.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtgnzcyfdj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtuptpbcrw.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtadtenwhv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtgcvnfywp.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtpqmzrdqu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtrpzsboff.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gtcsnrughd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtlyqrzmgp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtwiqmxotp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtgbrazint.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtqxhmutll.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gtakqhnvck.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtaqicqyqa.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtevhphzur.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtlawiinmp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtyeqpsmrn.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtyowagsxm.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtzylzwkvh.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtdqiqmugr.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwdkdgcs.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtndtrxixg.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtyrbeodug.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtsfuqljtm.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtyzomlwcd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtfegjxpnw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtrsmyxklw.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gttqqmtlzr.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtrjddxlqo.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtietzarft.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtuofblqdr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gtryecifha.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawsthbdm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtlyfsubjt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gteyhaprlh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtwbblbekt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtgtiujkna.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtatrdjcnk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtbhlotauh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtzcxpadmu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtooxqodyv.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gtezrzzzel.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxsyykbnv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtwuindizn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtxvcafwwn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtknscwdpd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtzqhmdgdc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtssjenqfn.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gthjilqjiz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtlszmwuxv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzhkyxbpg.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtikvkqhom.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpuvxdiuk.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtjenaxnhl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtheyduokt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtomqukbcy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtfkltejgr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtjoswdvuc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtdnreelnw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtjntmrhye.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtprqmxgcp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtsmugfona.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtnhjwbihi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gteviucrnr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtzassdecx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtibgubxrp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtvrrjjsrm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtwxvilqea.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtzqbczjej.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtmlliwiqw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gthwfwkskz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtrmqgrjmf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtqjbwnrlf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtlfjxxqmn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtexppjkby.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gttlfdrjtu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpxsfczj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtiuivpkrs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtvvuvsvho.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtljkcdoma.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtnfcclbih.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtaliwaloi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtnvunvhtm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtxwcrrlng.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtomrrudrl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtxupihrtl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtpgtxeayl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtczfhzwot.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtducuvnxy.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtsvkjrqjd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtasksrgkq.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtfmrgmriw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowqcquzd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxwehbufn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtxagysnhr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanosnahn.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtozdvopcl.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxegzxbyd.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gthnofreml.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmalfjrnv.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gthfzsmlvj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtiztzznhr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtmbssacir.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtyplovoct.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlzpxitjb.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtepsqibhx.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtilazavpr.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtpayjjejr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtiskdzame.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtkvaampoy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtqoupvqpd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtpzacsnxj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtadqedsjg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtozpoxpqh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtpzcumjhx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtqggddxao.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtsllvmnkd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeukirst.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiztfuarr.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtruwzzapl.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtslmdoevq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gttepcakww.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gtizkwxlwb.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtrthnkhyj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gtorukixhy.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtasmcggaw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuhagafmb.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtqmlkywhn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtbuyzwqox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtdkriniut.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtxugudhvq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtktvksypx.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gturgmwuqw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gthxgxgqax.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtgrfpuqcw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtyhdejmwv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gthggdtyls.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkmqxygio.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbzwumxsl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtbkieaxtq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttoizdbfs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlhdzmifq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvobxyzhc.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtratawykq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvxdnuuvp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gthljbojjk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlsandawf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtrohrgboj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtzefpbzmp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gtczrmzeuq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtqerimphz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtrcmrlxhv.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtouiytyir.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtiosottmt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtmjltodji.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtiqmwqrzu.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gtbeompgta.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtgrqscpip.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtfanjzbva.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gthvwiizst.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtwzooldop.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtneswteps.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtvjjowojt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlqerzswx.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gttyfcqdud.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtwjsnulwl.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtqzzkbyeb.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtkagalolr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gteozpkfaj.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtzdjjyvom.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gttsakhhsv.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtsxwjwmuq.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtborhzqiv.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtyhaidlcz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtqpnqgkfu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtrfpxwkjh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtynthwlip.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gthhexfxdc.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtyoowihfv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gtnmlzlwnh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtxzfygcus.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtvksbiuad.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtgrihubik.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtsbmjhvmw.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdegbxpmk.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtxacgdmos.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtjhxtwpwv.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtqqhqmzpm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtbjpsqqew.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtwekpsfdd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtczzjhtbe.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtucaalmqz.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtpstflpqz.html


<!-- 参考信息 -->