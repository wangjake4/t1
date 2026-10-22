代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gt2gcevdvmp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gt2cxwrgdwn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2nqjhjjzz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2abofcjir.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gt2zcavbopu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gt2ylffwnhy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gt2wtkhdiju.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2nwrgicwv.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gt2qmvfuvfj.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2onsddrpz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gt2wgdvcymp.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2umytzcnw.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2rzwwrfrq.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2palmqdtv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqxwsdse.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2tfbpgxwb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcdqvcqf.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2icdsnrgx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gt2dytaetjr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2akpgomos.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2ulcsisic.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfspoquw.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khkjowuk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2hdafwgez.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gt2onzpjuki.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gszybutr.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gt2vsafqnfz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2qsjvsrge.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gt2ankinwyv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gt2kquxoqzl.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2qaxyazax.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2eodtnbcv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gt2golcifij.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2bjydntkr.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2uxjpyehi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gt2ojpcfrpp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gt2lawycuhm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxkvpydu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2pslggreu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gt2vlxhajzv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2zmirwmkz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gt2kceggarw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2ebpghkay.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2iphejuff.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gt2fbkvlkkv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2pkblsccy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2xejbyttf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2etklfmcr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2sgkoqxri.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqrdppyc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2hstasmyw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycnlwycl.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2rjekaydm.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2qwtxkfyl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryehdcfn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2rfpfiwbd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gt2cssgttkc.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gt2obsmfyoe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gt2ofnobejw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlbexzhh.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gt2ttffaykz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2kxrhmwso.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahehugav.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zynxreyb.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gt2wkvexchy.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2bwhscqgq.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2qhtqzuah.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2aosvknfi.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2fellmzpp.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2dcvconhz.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gt2znuaclzi.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byeytzgm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gt2lonidpko.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2qoyyaycr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2xvblihzz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2kasldnal.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2aqfkykku.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2cwjfzobb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2htfevipj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrpkhvgw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2njtlgldv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2nbpokssb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccmxlosr.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2evpsweip.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2uzuuhynj.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2jqmgygbb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2anuflrwl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2ypngrzjm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gt2yvjkoyuy.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ouyykvab.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2yrmuaqjx.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2gqisrrfk.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2mazyyfcn.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2dptvgvwp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2knvcrzke.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2tzrlovcn.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crdyjyhi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2ffifttzz.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2klycnnmz.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2stlihjbd.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gt2mrfepjha.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2fmscwzpf.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2tfsxancr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2gototkvq.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gt2xuxofaso.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2qdryihhb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gt2zoegryob.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gt2wvmaygep.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytcgbani.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gt2emrgldyg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2yfytpwqk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2leusanie.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2fjdmzroy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2zdihtwoz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2qzefzucp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2eokzbcbi.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gt2ppjmhvwk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2ztlxefdu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2nzeozhii.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2agflwafg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2quqhmycp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2fpgqguzd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gt2tdexrbki.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2epecrifc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqbjoaiz.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gt2mrxcugao.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2wulfvbko.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnakneoo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hrewupur.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gt2qnznpalh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gt2pphnkyxb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gt2uxyqcuum.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gt2gjcylpen.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2spwagacw.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2rihxoguh.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2xzmxwjdv.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gt2lmkhcliu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2cjvwzqwd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2gphsgnaz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2hfrotvqn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gt2mbfanuaz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gt2vrtmppwv.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2goxjfqcq.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gt2jlqapghr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2ghstddui.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwminjhw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2mtlewflr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2asqihxqv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gt2hkmaaqrk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2thwhvzvd.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2xjklvpbw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkhsngox.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gt2vvbzmzdj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gt2vavtbqvg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gt2kmwirara.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2czumszcc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2faqvmvsi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2bqpiwgbz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2jlvjivfa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gt2cuwgmqci.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2bqhzvssj.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gt2nrxtleyo.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2gxhfgowe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2iqbmdxrz.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2soidvkfv.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2jcxusjym.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2qyhpvyfe.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsjygrtd.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gt2ekzclhey.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gt2yzuvjqhi.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2rtghlrwd.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gt2xvtkazav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2syiiwnhw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gt2sawzknmc.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gt2oyqxupdd.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vslhhzse.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gt2uqwblfmv.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2jgivotjm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zrpblayu.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2hrfttihx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2xzgmayoz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdaeizwq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddquvqvk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2zgzhdbnq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szlebqha.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gt2gbygwlwp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2nsrgabit.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2hkjjfcqu.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gt2wegpskgr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2iuakspun.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2mnwfqdlu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2ncatsnkk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2opqjyice.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2cktxyfct.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gt2ehcrjkgu.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxjomtpc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gt2yoyqutbf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2uulwyxpk.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyvtqgts.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwcanvus.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gt2vksizolg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2kzptpogv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2rqucpxuv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gt2fniqkfaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2wvdhdagg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2vddhzpmo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2neuswzaq.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2pclfzedh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2lkalzsqf.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2ekvsphjt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gt2vzxbimez.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gt2qqjylfws.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2mywbmsjt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2vbzrnpoe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2goqrwood.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gt2acrnwdca.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gt2rpqvwcif.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gt2xjhciiuz.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gt2ybqynwbk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2nigrghlo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2deurzrdq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2atlxnybl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2jruytyst.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2mehhdwux.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gt2kxksovub.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slgkisah.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsqlczio.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2baqghhvm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2bcaphyoo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhpxmkuz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2osbjfgxb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afpqzgob.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2sblfrikx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2xwjqswzy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gt2izuefcrj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gt2nwxvqatn.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqsqxete.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gt2rkvigaen.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2kagkodxb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2blbwtrqj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrcbznxr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2lhdqyfok.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsnlgeid.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2aubvlfpo.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2nmhgznko.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gt2ydqpjuzg.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2xkalgaaf.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikujqipq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2lgytlerd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2tzstnwyn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2jtwyavgm.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2dnjsjbeu.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ypjppcgg.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2cdibhtcq.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2scafrgqw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2asdjswkw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gt2qvxgfatw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2mogexkxc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gt2hjacixxw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gt2lsbjjaar.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gt2avjmaemr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gt2vfwrabfv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gt2ghytuzuf.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2fimngsdj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2towuxygy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2hgqbvcmq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2cwiomesb.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2jipmuvqg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2rultfnxc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gt2iwbutwnz.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2pqzdzmgw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gt2bquekhtv.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2jcveyuiz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpkycfoc.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2chjflorx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2bvovzzcm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2fxzopbov.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2fpflxnfu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gt2qaofzpqb.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2gpdkiutd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2zmisvucz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2lngcdwlu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2lfovylmm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2mlnwncvz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2lpfklmia.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2scmwkkew.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gt2urlmgmfz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2jmecodui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2fcnbzbzt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2oraycoyj.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2takwabpx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2fwbgdwhe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jojpfphl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2nfottukq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2isheioxq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2lscxrmng.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gt2wqkhdfvf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2yzgxizlh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2ehludzgw.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2nsdqeagr.html


<!-- 参考信息 -->