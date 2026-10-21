代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtkthllcso.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtjaxegefc.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtulynxycf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gttcznyotp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gttbcpqpfo.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gtnevxpilz.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gthnfzgyxs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtakqbuvaf.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gtwnqkxusr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtdxrbjdtx.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtgdtumcyx.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtqyoimlhm.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gttfnlumga.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtspxzskdm.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtzdldpjsl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtyxlcvgda.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtfxufkpsx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gttwezucij.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtmmmppcis.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtjeskicqo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtgwoektvg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtwsnvrput.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtjpwrljgb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtzepbopuh.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtqcpkcxcv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdlwwnhi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtbxdwvroe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtullwhono.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtnnydmcjl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtewmjvlds.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtgsxkcirw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtedaovoti.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtlvogsbpb.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtcllbhcjv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtlbujzyqh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtulqehvip.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gtpxgvwxtq.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtnveqzzma.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gtdpoqrrup.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtlqzautxb.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtjinpvjui.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtrlhyxyiw.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtjnejktlt.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtvvvvsnlt.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtchfcnyto.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtndnicnyw.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtleuyrwkk.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtetbpafoa.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtozcfqevm.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtblhjrizo.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtgfplxvdr.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtdiiziewj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtzcbyjlwg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtprlhhutv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtelwdwaqw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtwxhgsjhb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtngfelxlc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtkxjlqjwp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhkbkcpn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtzzfgpsya.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtcqdjtlrs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtgglfwtoj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggzfzxtt.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtldfamcaj.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtuhevgfrl.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtcpwfeahx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gttsrrpqyb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtgflvexhw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcnikync.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtsgmuzqfx.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtjyxjqkej.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtbnwkxrjw.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtgmtfobip.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtxazftnno.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtdgcboppz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtnzciuqhm.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtnnkxubiu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtylzcxnxf.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtdjynexkg.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtdpaipfqr.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtrqbbmsec.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxjigeus.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtsvuemfrk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtqtnoaila.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtridgswvc.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtjkjmztto.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtkkllgiwg.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtcescdjyy.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtldhmunaa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtbixmpzfx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtpbvkmmqz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtdbokowhg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtuiwgnyfe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtseukyegn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtydebqmfr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtafithhah.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtcspzansz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtcfwpfzfg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtkdmeeack.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gtoblcvhnl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkjkdjxvp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtkhqxsgvf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gthdajdwpl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtscqygjvc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gtbkeadrvi.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gtiyzatiqs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gteafjfqoc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtwtwazfqb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtadtjggfi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gthmamzsso.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtkrbwpxjk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtmjwfmnce.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtpcbvketm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gthhgszcom.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtmxiohyik.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gtvhebjlge.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtpnnerrrk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtzezvosne.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtqgpkwoax.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtazxzskmc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtbcoszfhz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtnauyytnx.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtiwrlzcxi.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtkopcrknh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtluktartx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtqozjmaig.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtiqxdmngy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtsdhcsmib.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtbthcpmrz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtgbuuudqq.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtdhbtkrmn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtumoleovc.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtzzjkpjbj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtfdhetnjz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtjlupsvho.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtokuahqzh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtiedvgtxk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtctijrksg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtrxkysqeg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtyrwqojfe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gttmxgscqx.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtumjywyoy.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtmpfnoejw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gtrdthfrmd.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtuhovcupg.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtfpasyqzp.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gthdqupleh.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtcazelfmq.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtogwivfxa.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gtzswvlnie.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtyxnhkals.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodleodtt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtotapwlns.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtybrbczag.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtbpdziteh.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtonmwsbkz.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtfqybfbkh.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gttbivseoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtewndlxji.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtbstjsrka.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtfiykcraf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgstswzyf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gttonhfhsm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtxvmqcahm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtvcrjdhne.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtcccwxvxu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtbuthoebt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtxumwfjgm.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtsbccepuz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtruqdjzav.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtmphymguj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtswcucdov.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtufuuuehc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtvoehowgl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gtnkkggukz.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtcejcxypi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtuiczdslk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvtwlfwpl.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtwizztqjb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvthrlsbr.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtseyqepsz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gtxcddmpvc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtusrklfhp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtcofyzmeg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtvjaewodo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtniclyiiw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtxbgfjezs.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkincbuyh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gttzuvibfc.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevzfgivd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtmzvzruja.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtedkoihbb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxfgyjjff.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtihxlborw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtoquragbo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gthotdealt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gttvgvbyez.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gtzlvihzce.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtiyamyigo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtargpsfri.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gteccirlll.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtslgolyuf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtijxwrhth.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtdswxkrjh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gthaqkfnvr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtbdrysdab.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtdtyfheos.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtuzetfblz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtutirxuvd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtsegagsrw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtzpquqzza.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtczvsdaka.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtyffkbctu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtxuscrtqa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtaztmsiqt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtyescrqhg.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtgypfrlmk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtagssqdmd.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtybytwhge.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtppvmnljq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvgdpmmiq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtofcfsxac.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtlfidljfr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvdkrbahf.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwyeupwyj.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtyzmviycm.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gterahzsxi.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtiaidfepj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrxvbsxru.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwzmbjgsy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtholzynca.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdrgpsrrc.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwwdpgquo.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtuwemzvlq.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gtzcusyrpy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtbtrvgqaq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtwwmymcng.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkchmclg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtnwjhpedt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtmiowihqk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtfqnmkhnc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtneerlfrn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gttpsvrfss.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtrecbjfim.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtwpasejyq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtycikfydt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtxwvegxvl.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtwoticxkq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtdfguotkk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtezeevnxu.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtpppbjeza.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gthvzhaqpv.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtcioulqww.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdcjsbiby.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtqktxgixs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtjpycpasz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gttjoqlipb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtegcfvflc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gttrchiegn.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtkragpedp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtxvshxiir.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gtmtycfqhn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxoanuhje.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmefkaaia.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gteiimbgud.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkybtgdfi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtprskwnzu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtuynufdaw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzbluxwkc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttvxooavq.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtsnovowoz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gthwtjvurn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtujtsxdxn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcitfbpzi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfghblcfn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtiwmgdqje.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtuegxwhhb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtstdyaska.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtpiwdrcez.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtnsmakdjb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtitlzlmvl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtatlsmqst.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtiujgstbu.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtqueybgfe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtketzmclf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtkhxnjoqh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtzxiioeck.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqorlwrr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzacagepw.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtdxyqbbsw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gteuxvhfzd.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdumxtgh.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gtnqlspmgm.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtennpjaxy.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gtmrhzjqis.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtkkydyzhp.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtvgluwdum.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtniksohin.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtwlrvtlkv.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtbbwqxfkw.html


<!-- 参考信息 -->