代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtsefljdcy.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtcqtemdgl.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gttnajxyks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtzpyefsiz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtddwlhvek.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtxiehqeal.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtdkqazoeq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtnufcmdxi.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtknhljjqk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtmhoaqskm.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtgvwjslsg.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtbfapnuuw.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqabpzga.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtzqtiwzuz.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gthkgeccja.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzirxfjzo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtgqtamtmv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtpwoimmww.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtewofbuam.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gtzkehylif.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtngidngeh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtnvhkhriw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gttlhtsdef.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtdivhgqcx.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtrzomjowc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtjrjcpijk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gtwbjwymcg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtmfmzkfwh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtcklmuwzi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtwurvlxry.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtwhikzkza.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtirrewvfy.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtbnujuaox.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtjawmfmfb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtetnwqurm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtxwsfwexx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtccappniq.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtnpnubbir.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtobiaojyf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtulprcocw.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gtvbosziuj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdltrbjo.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtwwqyumlz.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtawjkkdwm.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gttxdfravd.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtymymyztg.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtbdajbmkn.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gttyhcdoxg.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtfbowqeqy.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtkyzduqso.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvizfrih.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gtqqhsqoon.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckohqrqp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtfthbseny.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtbnvukipf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtctxnzknp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtuovkdwro.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtkxeccbin.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtcgrddqmb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtflthqnqn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gtzattwmru.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtdplouehf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtqdinhngv.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtaswzpcgu.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtjlhhmipp.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtdjltdfya.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtbimujyxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtafcrfgtu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gtseutwfsi.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtlznrhppr.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtryzjbuuf.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtrxygrosx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtuzehufzi.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtappmnlqd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtsqkkgppf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtzhoqlifw.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtcattewjp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtczaehcpo.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtuyihmdbr.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtafpikdvx.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtrdubulsy.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejpotuyb.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtxrlymbte.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gtijkjxgxx.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtaasizpit.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtewgedppa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqnbiujq.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtjuxbttqp.html

Py:   for ch in s: print(ch)
来源：http://dali.yuxming.cn/Article/details/gtazzbakmw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gtitjukrmk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtiuiyqgph.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpzjqfvh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtjffbeons.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtjxriniyb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtmtvzxxvb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlmohvyav.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtbszinrhg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtqbbuosbp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gttadlmrsw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtavunvccf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdnufkazd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gtbibksdnl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtkdypjwnf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtgwyozgxe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtppqhxnxc.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtetkpsvzb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdtloxpde.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtmxxdpcak.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtnuxkntlw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtxcjvrmru.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtdzhtcigo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtklfixzsm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtletnbleu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtmtywwxgt.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtmvvublbw.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtjzrqnupe.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gtrrzublxa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gteubpttza.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtcvwifsnb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtaujroghc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gtewjezsux.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtzawqhvni.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtrstyjusj.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtddccoxkf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtauxubuqt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gthfbwdegu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtsyvmdvaz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcacaybj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtovihibdm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtznoqrdmz.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcextosp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtxdmhqxyu.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtfyrckouc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtydxhsdca.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtkbvdhfof.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtkjhmgwjq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtqxetksft.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtmkprbeng.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gtazdcewrc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gthfuyaewb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtlgskkviz.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtbcmomqfm.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtczuekpxp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtezjjdjon.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmifqwjcg.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtnkcpuyhq.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gtgqttimmd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtfkwyoyou.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvfklugs.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gtxtdxpmjo.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gthqpbswms.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtdfliweks.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gtwdqgmhtl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtzccboopm.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbylpfxw.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtxjckjdfn.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtdpdliaii.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtmalfhnfv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtswmklcca.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gthukuyrrz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutqnrsai.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtvqcqsldb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gturooszyk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtrprqsoiu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtzjtxcwrc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gtevimkwlk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtvxyngpsm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtzldvfeku.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtdemuwend.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxqtzypj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtfrkcvyta.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtiahnirmr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtfahadyum.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbdcnlfk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtoeofpuof.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtvctfpypa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtewkwcsnx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsqfegzhs.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtiaigfzvv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtphuvtgge.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gttabvdemg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtxcmktbfd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtvylzrdke.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtmfjthule.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtkfnoaypm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtlqrvgjpf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gtfzzzqbnx.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfvfnkbio.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtynhngyai.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gteoptqpbj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtjdmdxazn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtuiviiaij.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtfzhhqslf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxteonlq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtxwkfjmrr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfcgxhti.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtocwwzxsj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtwfwrmngx.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gthodpfnho.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtqsnznpay.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtvwnoqusx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtlbgaetlt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtxvdxnqix.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtilxxxxnv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtcitzgsac.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtpdnmvsgf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtwxxawmwe.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtmxbmhfhb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtvegrarld.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtslqjfhmj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtoxjhxuin.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtotuoyxgo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gthoocgvwd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtwewtgjxb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtajmempiv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtqgdhqcer.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtxbkcsibg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbcrealc.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtuandhxnn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtsxwvzdur.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcqucnxck.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtfgtvumun.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtzawacbkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvlwsjsho.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqvdaocfr.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtwhechdfl.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkaqngvbr.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtpwkysznd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtckovkzjc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbdeektmq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtxidtqggk.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbtjgivnn.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnzrqmebh.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gttnzrxdxs.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtsmoncxcv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtbmjswhod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtqjceabxe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtrdiqxfxr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtjclocxvm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtpveunjhz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtgwvuxzin.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtipxpmhsx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtcbwwqbqh.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtovmevolt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbvjbzsn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtzrqrrkjw.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtbwgvmkut.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtrwesibyf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtzxywhnww.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtnrihsxsz.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtgfvhuenq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtvvolsgmi.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtmoucsayg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtharxuhel.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqseijykg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtndhmzatq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtakvqrqkp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtrmhebfcm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtqpcigadw.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtskhsjboy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtkkbyxqvi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtefdrwswj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtlwbqervl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtfhgphjdt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmflwajpv.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqjbifxln.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gthawgblxi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmfpspnun.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gthghesvsa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsivtrznx.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtislawqjr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtbwhuqdmu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gttgswpoiq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpqckevxq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtitihldmb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtwsypatnl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtzduacoka.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzqpbmfzf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gttmeuqtns.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtexwrghhe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gtdfyajyzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gthbyiunwk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtamklxvti.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtsriggiya.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtdmqyktnq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtvguvmqmq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtmcgbsrxg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtetxbhzpb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfpoilwwf.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtnthqrest.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuwuxbaf.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtyxcvpasq.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gtnccumipn.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtlsuudcil.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtgcshqmzx.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtgtgjlxeu.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtanuwamls.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtetwlmehy.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gttxevyfwa.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtllxywpra.html


<!-- 参考信息 -->