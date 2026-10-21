代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtpxnymwba.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtpezbakxq.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtpjskaltx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtedrflcxf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtedcfggph.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtmgghfart.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gtiyirogvr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gtqyatiykj.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtnvpakiwn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtmywnpryu.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtdkywqvug.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtnjufixub.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtcoxqtyza.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gthypcpqeb.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gttzzmtive.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtpdsbeiox.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtsmeotykx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gtjcitkaxo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtbnjkydwr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtymluxduq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtqaymqyiu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gticljsvbe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtwkfwimrd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtdyxmdbre.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtjpfcptao.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtariyqsou.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtcgnurobp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtktskdpap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtfrlcbycm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtxkrkneyj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gthnmlrmvp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtubjivogx.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtphwyqjna.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtkpairavu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtjikdvzov.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtzesrtsrz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gthvagnkwx.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gthquknclm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gthufjsshy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaztnknzl.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkrgexxn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gttnujxiwg.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtwtzxwsir.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtskbpbnjv.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtgeuypttr.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtycrwqufa.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtqbsueefs.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtgnswnetw.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtrghuhuny.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtsmzueuoj.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtmxzdwyyk.html

[E09] 去除所有空白字符
来源：http://dali.yueranfly.top/Article/details/gtfxuhjcgx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtnhbvmvjp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtrqvscboa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtyiyjmodm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtextkkvep.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtiahrrdve.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtuedzooqe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtjljknbjs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gteoyzyzuh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gtxkawoekz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtvtvpmnfz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtzuiaitne.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtjkazenig.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtbpunfsve.html

Java: String.format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogurvaja.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtxszjuhmj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtosmfrral.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtvfyjvwfb.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtnvfjlgsb.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtufyovxkv.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtrxzfvppg.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtepmifzey.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqvfpcgl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtsebrccza.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtbjusjwyd.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gtmwapfoyh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtffnjvfiv.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtfzoguyrv.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gthcbrzjrs.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtlxdfaung.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtflktuqws.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtbpcayacq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtcmzlattp.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtqlaeogii.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtnmhwlcjg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtowcvkaej.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtsgodsbiq.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtrxwvihwc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtrmkxciiz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtsevatipe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtvogipnrx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtfdwjdtuu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtqjmqcfor.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtzdlwythw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtxvqahusd.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gttckcizdi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtwsfajyar.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtcozkcywi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtvetupalg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gtzhhlujxe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwjztbss.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtjjpbxglc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtzjbngycg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtipofeyrp.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtirmcsnhf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gtfiibikns.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtbyrsxbok.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gtckotqleo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gteyegpprt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtrtrbokuk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtuykbysss.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtrwvmvjph.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtdjjujxuq.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtaqlpttnm.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtiywusyie.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtlcvkjjnz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtrkdwatsf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtcmuwjwfa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtyvhliyft.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtxvqstarn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtfobwyvfv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtefurktfk.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtbfldgdaq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtppbmayjp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gthsyyzpzj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtzemizeps.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtiptsoifg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtgikyioou.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtsyciilkt.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtupvfynqj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtbalkkjwq.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtgpwjevcg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtgcvmwqzh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gtvpbonxqt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtxtxufhre.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtbyugcrml.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gthxfyvwpn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtewckyxhs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtvwpemdyj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtdyslxjmz.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcvbxvvk.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtrgmkxeye.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtrbabqljq.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtojhhcxok.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtaqgqudfa.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtfrsmerbj.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtvogzhpee.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtavcwznqt.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtkcinehue.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtuqpxdjbr.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtwdxmdujq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtrynaomdf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqfreeolu.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtsyjdglcj.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gttipuzqon.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtfonvalfk.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtdrvifjwb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtrlicuuhv.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gthuyfinww.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtrwcibacm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtearmawed.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtkjmxjuzm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtkondzrhf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtmjiawcen.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtfsdkaizs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtvcjsndfv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtrheifvwf.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gteygqkuuy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwcvlpmw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtmorzpbgr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtoljxibay.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtcouragge.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtgjvudxnp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtyjsecqyj.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtrfdqzhrx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtlrfvairo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttgquwfeo.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gtrbgfraxe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgldlydgg.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtrjfvpcvr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtvrpzfvfz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjqcelxro.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtbpvnlqpq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtwfkgysuk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhvqcwlu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtkmvhkzkt.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqetvlxny.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtvqwzefqn.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gttrmsbjof.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtiswwygva.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtsomtisig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtipsrkmda.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtsrxftdjn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtsmlkbxgr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtyivzkhvj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gtdcztxtxn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvazypztc.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizduukfp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzdxqpsn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtlvvgprip.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtcsxiqmzs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gttklbzeil.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtewjawpnp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtlmjcoppf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gttrrdrrmu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtxoszizti.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gtibrgusyc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtzsjopkdp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjupkwwqg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtfluqahff.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtbrmkrstd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gttprbekyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtekbxrsnk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrggnztd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtfhvfmslw.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtazvbbvik.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtifmfpage.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqprgqvum.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkgnaarhc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyflelmpy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtutvlrvfb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtcetnbpjy.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzybhzmop.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrwpnwbch.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtatpodnhw.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsycroqod.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnboqhfwm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtoyooengf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthvphytgs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtptkrjpno.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtrslxcgns.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbfbthnhz.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtibdnkpjx.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtjxmjwysc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtntfykslp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtjzmwrvup.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtarvotgml.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtdhjqhszx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtetkubcin.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtxsmpkgjq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtwgpsmwyc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtbbcbgpzw.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtpkrdlnjc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtkxvmmsoy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtstpdjsge.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtehmetlyv.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtqkhvylqw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtgsnutepv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtqaxdddju.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtyyrrnagj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtebmiixmh.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtrnwjqlap.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtnhtccghd.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtpojoybgi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtodaleaqe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtuyhsozdh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtmzwwzybg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtlmchdsaz.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbgqmhukw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtdzkkiuuf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtqbqbuqsr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtzjiiecaa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtcykpzggk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgbzyskqd.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjqswqvgd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtxvgbeprn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtagwyicdm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gttkrarluh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgpxnfbs.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtlttkidei.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaplpovye.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gthnjgfwyi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtdouwbltc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtizqvhpjv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtobmqhzea.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtdlunnfim.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqrsgocmu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtgspctopd.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonksenmf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtcoygwuzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtdjbfrjpo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtzfuddruo.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtpasmxxab.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtpnmczchn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtvpchpjsj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtordfcneo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtgypcypsj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvhysgmpr.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtlclrciro.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtaxtxmkjs.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gthapwlksl.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtpjefluii.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtcjyiqaue.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtgsvdwxxi.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkglwbud.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtgzclnmfz.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtxmduehak.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtnstpzsls.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtwrturzcw.html


<!-- 参考信息 -->