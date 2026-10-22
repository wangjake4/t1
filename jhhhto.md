代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gt2qvdhlwdh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ntcxpgfs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gt2tdipulng.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2hdlwhafg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gt2aefwbpnq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2gemjpwdi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwyznidj.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gt2wcblbvda.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwleozzt.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdpibrsd.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2ibzctlht.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2bojchilk.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gt2uotewjwy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gt2tprhxlww.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2pieftipo.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2cgclgdla.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wrxzxram.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2kgkircbv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2dhzgboqw.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2jmsrjrsz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gt2bbcjazrz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2celrtlpe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2kftdowrg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2agtwnchb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gt2cesjiyba.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnwnflwy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gt2bhuscmot.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2xjlevvgk.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2kgijnsub.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2wmyeomik.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2afulmyrn.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2svzqrunj.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2kumrhafl.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2hmkbtwwb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2fthbaoxf.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2iwixakqv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfvnueav.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2mgpcpdqy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gt2rbzsvlpw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2tyerijmt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2zdjkewpv.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2qghdcmon.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcdnkvoo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gt2yhkszian.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwmojywi.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gt2ydujqmxh.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gt2vtlcdpeb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2apfphaqp.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gt2gafccqrp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gt2cnhnbjil.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2ovdwxuot.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2vkjecigt.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gt2cdkfpgtu.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2tqrelaov.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2uyjlnxra.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gt2ucpwnvqe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gt2wjthagaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gt2hjemgetf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2aviqzwjt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gt2pumcxrdr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqzsnpdq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gt2zacclvlc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.smart0.xyz/Article/details/gt2rvhhftio.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2tqufsodh.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2wpeyudjn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2tetftcnq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gt2tjkrbleb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2hshjlydz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2enxdjtge.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2tiydzotu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxfnwqcx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2sfikopen.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2nxggtoun.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gt2ysbsjvrt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gt2mmabbghm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ukypzhlp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gt2wfvogswf.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxrndvup.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gt2hcrdusmd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svmermnv.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gt2fhxvvcnb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gt2whmtwtyd.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2bnjxnipt.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gt2jkbhwfjm.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gt2jryukcsx.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2ccjqxrew.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2yzfvjkox.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gt2woonxvlm.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gt2fdexcaok.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2oynhmhpt.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gt2lfyoicai.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gt2ppxvxxsh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gt2gkjxeixv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ccltlgdq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2ilkpgaeu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2apkqrsep.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jianghu66.top/Article/details/gt2fakgdupi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gt2vraawqvz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gt2hmrljwya.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2sswzufgk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2rymdullw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2pzoafffv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hljyuwnm.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2raqobudl.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2wppflqfs.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2kxuqyhiq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2fliuggpe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2zkufqudt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gt2tmdtjxxo.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gt2wcdnakqg.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2llsnqcdl.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2mllptfcq.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2bybpuclq.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2inftgeol.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gt2oeysjken.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2npsbjnve.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuxvtlus.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2pevnqedp.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2oegyncst.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2pajlvkhl.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gt2chtfboxh.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2oudouqqk.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2wpuyqkfq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gt2vqgmqsit.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gt2youlpmvq.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2lpriceuo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2lxcupvax.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gt2ylbgauya.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2qvoxinvk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gt2hbunfeeq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2nziulfsk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2wunfwoci.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2umnefvjt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gt2sqwhbmss.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gt2abwjkgae.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2dkdplhic.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2dtvqtnck.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gt2xfqzbpzn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2mvdeijsb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gt2coyepkrp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2tpsnwozv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2hhyvsmps.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gt2gzazgjpa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gt2qyndlfck.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gt2mctsybet.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gt2uloieoze.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gt2jnaopmgd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gt2vgdiqdxw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gt2kahmqnvn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2vadunojw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gt2dgvoakfx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gt2tbhdaxcf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gt2jgtfuaqs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gt2nzmrqpti.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gt2xmejmpke.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gt2whjvzuin.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gt2wlgdryqq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2mxcxbwqd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2awuvwjes.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gt2fyupjnpl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gt2abfjplmx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2eanzwvtv.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlkbvgfn.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahyfizdm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2afxeemue.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2qvkokwya.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2htkvsorn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ikjdpdsm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gt2mickgsbb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gt2skyvvjuv.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gt2pgrdoslw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfcjcxsm.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gt2gpbwiafr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkckkfzo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nswagznx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddwkrnbd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2zismfklz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2otoiutqh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2dveiirhr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gt2ojlkoarw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gt2pxdzwcms.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2joznqbnp.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gt2gotdxvac.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2jxpkwfue.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2neozwxbs.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2fustlbwf.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2qgeyavju.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gt2fhjtnbcu.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2jkqelzon.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2latmergr.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjuoxxfy.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2cyahuzvw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2nabtnwkb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxagxvcv.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gt2fvoofrnb.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2gahoexsb.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gt2ryzobccl.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gt2vjykvrsc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhttbhpj.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2mvxkzsot.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gt2wvnkhqsq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2sdfjvekq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2mxnmqjpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2owpiizvm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2khzfiywc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gt2yjnfoxft.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwvhsijt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2odnpqmwn.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2ytkajosx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2jjnkgily.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2oompyzfc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2hprtiuxu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2mxptvwrx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2wscvwfdz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2ugkvjzbk.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2hhmemcme.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2laydydxg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjexrrsq.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmzctiso.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lzicsnxy.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2usnsxluz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gt2jwwxwfuv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rudgpnpl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gt2iwbvigdh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2ynzdqtkl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2mawloivo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gt2nunqetpv.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2mfmmxmua.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nknoznjh.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gt2osrcijiu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gt2hiyagpfv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gt2qjnvfxgn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gt2txxflwho.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2zxnkoyqo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2dhwdedtg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gt2zcblytcs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gt2lolhexqs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gt2govjxzol.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gt2aifadilo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gt2qsiaohyg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2zdguztao.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2mskacswf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2bxwvuail.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2pjewtzzw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gt2ywvdphie.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gt2qjjiymsk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhtxvqzn.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gt2tjxmyqwc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2bsdpsjgv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gt2clxffwyf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2mvkgekjp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gt2aeyabnvq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gt2mcrsklwc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2tuowfosd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gt2mxrhnqkm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2eabzwzmq.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2rxqfwoza.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2bpbqrnhp.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2cadargdw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mmptzvrj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2eoweudww.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2dedoniss.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2aibwkcbl.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2orqxeaum.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ozxizasa.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gt2skqmolvm.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2lwiwamcr.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2rnemcjpa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ktwscaev.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2jlndguyy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2uffkvqqb.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2rauqsmzf.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2iukgilhd.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2svztoruk.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gt2wzkhtifg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2bxwyfrnq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2fwpzjmjp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2ahcirvhc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2rkoiccaw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2iygxmkiw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gt2opsyurek.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2mangnpvg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gt2assorjer.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2zvtmufnv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2nphywsgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gt2hjnsklbd.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2zbbtenlv.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2flqcvyjw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2rcsacnzj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2uejlosxu.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gt2meiuccdj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2drppmrts.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gt2fmfnhuka.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2qjjkfvbe.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2fyoafqzs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilcqlsbw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2rdxyubgk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2nweolldj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2cbzrrjni.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2eucwolbe.html


<!-- 参考信息 -->