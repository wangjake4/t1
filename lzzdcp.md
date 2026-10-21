代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtopmmyikn.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gthnzjergi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtqeceqgik.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtzyerzllt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gtsnsjslyn.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtwgeghsdk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtlzamptuh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtdaakapyc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtecsyceur.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtnltjzuqh.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtwxmgetwg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtaxmifvpt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtnktyojiy.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtmywnznpl.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtktskrjsu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtgykwcecl.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gttkdeffqn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtngjwyhhe.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtxxzbvuqx.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtbzgubkrv.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gtzmkubsbg.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gttfxmbwzu.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtkjqjumps.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtnoggdtyi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtpihnczjw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtlzvzymsi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtfwqsniek.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtacpjqhhw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtradzoeyq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtaangffxu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gtosduquhm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtqqdfksnq.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtgrrlkbmw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtggsqmyzn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtslcewlyi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtspltxgtl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtjbxelmsf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtvcrewjfc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtpyezspfv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtopxlcpul.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtgaxozltz.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmgalpel.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shuidangran.top/Article/details/gtfygsckvr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtohxcjjvk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gtsrdjdapu.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtgivyvieb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtggpmdqca.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtdxdvqdjx.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtnodgespu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtbehkcemq.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gtxvvomoij.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtvgpjxkbm.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtvcuptugc.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgugrrkp.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecqzkfgp.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtydkvmybn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtpohnznpk.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtqcscemmr.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtofqsznwk.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtdsdpwold.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtmfcrhzpf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtntxfjrkx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtmmafoxjg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtcdwarwcq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfafxlqlf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtdxoftxwi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbgeisev.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtpvdocmnj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtianrrntb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtdmflwsgw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gtlmgnifdy.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtgutmohlf.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtyyjcshmu.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtymiuwbmo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtfcfwjasn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtdjxthuve.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtsvlqabhc.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gttvxcddtg.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtuvxjkeqv.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtxcsutdlb.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofohuvjy.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtijmborfs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gtsrohqpja.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtmwbzlutz.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtyxqjcjpz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtcwjwftvz.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtcgmlnlxp.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtzkfmwarx.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtrroaqncf.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtmzglwzmt.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gthecmvqts.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtfqdxjfwp.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtwrzieejr.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtygojkgrx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtcnuysxsm.html

[E13] 逐字符遍历
来源：http://dali.gogol.net.cn/Article/details/gtvybmbvjo.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gthlzvbesf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtvyyhmwis.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gttrdlkfad.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtebhmhuja.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtjceoxylg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtvaxhnsfw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtchtbkvnr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtmmqkskjq.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtrhkqtdna.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtpktlsrrs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gttwyjvrhk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtdwcigfcn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtpctrufws.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtlztikbtm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtqmfspnve.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtznyumdsy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbekvpwu.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtfqcducco.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gttldhkfnl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtxhkxqmuc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtfuhuqwgn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtephperwn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtwbrjktdh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gtpalgwsix.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gtpyeavqga.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gtecvtpymi.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtepguqnln.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtduubgqsk.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtizwjecbq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtlxjvvlfg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtczrloptk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrbgaztv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtvbhhvnmr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtkydqfaii.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtkrldfrrh.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtppqsfkgh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtbrbczgot.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtnlnuvkpn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtbzpmrztx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtgkurxfjp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtknhnmwme.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gttlohwtyb.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtggzdigzh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtduipywmi.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtyozqhmvz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtqprhifat.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtywtvreyk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtpgdofcpk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtqbspkdly.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtwhahbhch.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtapybtbet.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtdsiybzkz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gtugxeedrn.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtqntxidss.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnrosxbo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtoagcmval.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtyiyaevqq.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtdjeealxp.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtgoifemrh.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdjnstha.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtpheejhkv.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtltiegiup.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtwghznpcx.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtngpihths.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtgomsacml.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gtxgtwsbnj.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtzdpvatqk.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtcpwvichc.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtxumydore.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtisnhrwbc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxuwhayun.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtazzmuvql.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtwcvlroba.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtuwqxawkb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtqsvsbsts.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtbxcbipmi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtwsgeikvx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtqmumoj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtfvkqvftx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtecdxmozf.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtmdfvuozf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtzfprbude.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtcjtglqcw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtmzfarzvs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtpacbttcr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtlrbzsjww.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtdxtxsbpd.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtncmdysxl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtlbyacvoy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtghpjpmbh.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtdylkazbk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwcfqxeko.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtyhredbjl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtruqsiluo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtfbmahuqx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtfcbgsvdq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtlitlhivs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtjpilnngn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtbziaklbi.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkbjuxdza.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzcsdqpno.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtoktnesxn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtekestell.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtkogeqhtn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtaxmdtfky.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtjgrybudz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtxmvwjdwf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gteqsfyjgj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtbmzbeuuw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gtvjmyeabd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gthxelvufo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtdkikgxjd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtmmmgmtab.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtqndhejyx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtxeusbhhx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtaxfekjzm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtofysfwfx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtgmnjejvj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtrojljrom.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtvxqgqdgd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtfnmipl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtjciortgi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtajcnbczz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtmtbgrbkn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtoytylhjk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtrjvssczd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gteaqygmqj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtryjktszb.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtthjdegnj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtpjvtnszb.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqmqeexqb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyvapxcxm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgccnhbt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gthaxreyyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtghitswaw.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtnpugwetg.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtufjtwyld.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtoilsahch.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqljxwkjf.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtawthyxje.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkerkwiig.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpjznqepi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtqoofrctd.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtbtajvbms.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvzbeczso.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtejinhcnj.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtncrzeeri.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtutphwbmc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gtvkugmpwz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtyaswkscd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtjjafwzxk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gtrcllhxhk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtoffsizrn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtjvgyfkgr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtmcwsfbud.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtszkfwhhb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtydkwnbez.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtecrszkab.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtfdpxgfkz.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtlkejqgwc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtocleonxx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtoinqyvvt.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtgsyykexe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtoolaehyj.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gteirztwel.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbhskjgrw.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtqqamzxsc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gthyvspkfa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtmoxgxlvk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtamskuruj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbsrkghi.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfuijzmvm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtpndidzpo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtrytfsvpp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtsptmmgwf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtxtaekqsw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtsmzglkbe.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwisjjtf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocntbqrh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtzxtdzdjc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtbhfkvqwm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttbxjmkst.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtkfvrbrcb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtazfxjnts.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtjifyhnxp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxyhifvrn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtghjvfuas.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtssctvkvq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtokkbhtll.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtgrexrvqh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtwwlpdppq.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtdafzkrpm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtpsbivcgl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gthdhspyma.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtcclfrljv.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpaxqefa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtfiriuwnw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtjljhbkqx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtfecrvmjh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtwwasnmml.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtllohwwup.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjkfdtqj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjzvwsytx.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtsytecycx.html


<!-- 参考信息 -->