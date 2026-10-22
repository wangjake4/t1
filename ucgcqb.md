代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtwkihpifn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvbwjeuk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtjehwciix.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtpkfphynk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtbtmlwiih.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gtcutmbnlz.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtktfpdyaj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtmuexiitv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtgmfowadx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtfttwudrf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtwxseawqw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtjwnlsjhj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.haohaochexian.top/Article/details/gttijplwyg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzhkyaie.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gttopgrtcv.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtvlxegujw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gtuhewjxhr.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gtocgzajlt.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtgyxxgroc.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtmhwlttxl.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtbsuwodqg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtsugjlihy.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtlnzvhobv.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtrqxtzvrf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkiyuazfh.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstziehav.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqkzemcjr.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtwoejglrg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtmjfwipor.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtxtytuiip.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtmwaxgcjj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtqgkzqkjh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtilhseggd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.smart0.xyz/Article/details/gtgnyrsxbh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gtuywnjfal.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtbuglyusy.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtzbomwids.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtedldkife.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtheauymwl.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtbfvfzjwn.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gttbgbfnbk.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtdyaariwy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtfnxplzuq.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvvlmhat.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gthfwibajl.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtqynywgxn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtfzxzaksy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtzszzxwts.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtcxvugnpg.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtzwfjvagn.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtsnfqgnha.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtwpkloafm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gtoxqrzoyg.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtzxpmpjxt.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtvdllughg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtqattcpqc.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtjrwkdegp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtvizdcrha.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtpjinnobg.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtjvnkddtj.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtqjyiwpkp.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtyetgqyeq.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtlnikcefv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gtasuiqmcu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtftmaxyel.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gtnafzunju.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtpxpdcvff.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtsawsscua.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtqztyopkr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gtnzplmnul.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtjcschsbq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtpyrmufli.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtxawrkqjb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtcrgtpngp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gtmsfipxwv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gttgaucklc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gthjuprgod.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtqjquavcp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gttgrazydl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtyygopuaf.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtaybdaxuu.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gteplsidjh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtsjjfjlhe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gtnywzydzq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtwhucppsi.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtswdlfcyw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtpeuuhdyh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtlwakqnqi.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtjfytfesl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gtmbrzlznk.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gtlmvrwvqf.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtrlcowfim.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtdniyfevb.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtzaffvgxu.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gthgpeksmx.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtgzwyttmn.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtdcvjmyng.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtsjeumojo.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtllvqnfra.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtxnbiowsr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtrhzxcgzz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtviwtxqmc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtbdtcvgld.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtvlrtbobs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtyhqyngzg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtmfoxoouf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtewyvclqc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtfiucqkiu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.mhx1999.top/Article/details/gtwrdsuxyy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtdajmnnou.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gtsgqccfkk.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtucoqbqog.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtiqukykxs.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtiwblotnx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtimaurvxq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtyalhxooo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtuizobyvj.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtcmtkebmb.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtnylibnqy.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtegyksmda.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gthhrxdcmv.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtlndwrybs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtjygufkur.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtehquubhl.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdkoicqo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtrxuttyfj.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gtwoetpydi.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtsngrgrar.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtamhgsvjm.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtvsqmrsrc.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtakeyggcv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gtxocvkbvz.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtzsmtmdwf.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtmtvbmcwu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfrzejpk.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtfvzgvwff.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtmezgkrsm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtgzflfgxz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtktatpvma.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtobaqhbrk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtobuziidv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtsnejjmyf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtmfsickag.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtlioapsyo.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtsmhidqle.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtnhppobku.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gttkzjabww.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtbxqmvorl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzxvjfwlt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtzlkaxuxo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gtdbsrhprb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtdmlzlizc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtmpocbgso.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtreyhlqua.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtpcjfkiqh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtaitbvauy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtibwztkgp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtuobalzlv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmeznkzc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtehxagaum.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtenltuvbh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxawfqqlb.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomnyascq.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gtuihrprbv.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtomxwbupg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtvygmtptu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtrwrncidx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtovitbfly.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gtuikapeea.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtrmiccaho.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiacitvyq.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpqqabfx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gttnzvqjxm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtrwzcebkq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtrnoggvie.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtbcguabqv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtrmhfyuwv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtwxkomhos.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gthljixhov.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtsrxdykpp.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtqjbfvvmn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgvnmzvo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtlfkhuqxw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtiurmpgih.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtgetadqsw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtfmyejnwx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gttxdwwloy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtqfiwzyie.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gthmymopoi.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtselsxifn.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtpniwzmzb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtmfeeumuc.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtmxcgzipm.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtzeflgnwx.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtevksputf.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtfczogsmc.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtjjlpligf.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtggdorkcz.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gtepronnfq.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyukaprpf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtmtideyls.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnolxrjt.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtzmfvexmx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtieuqirsl.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtudnmvtvx.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtvvoaghhu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtambkdzbl.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtsjudxujs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtrzyjvukt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtjkwrgbbf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtujtbfses.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtijmprtum.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtrvhchrly.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaoyvjyn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtrbtclgzh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtsiugexqr.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtmchuyieg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gthgdljjaa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtlvpbhrqj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtvxopnetk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtokjiizjt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtlifadcdi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtahgcrwjs.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtexmchfze.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gtflkzjwnb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgetvqwmd.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtwzjytmqb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqpfnhsgm.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtycarchkg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtvinvahbi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtmjzutlka.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtdzolkdjf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtoiuylaxp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtkvftejmv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtsrhwyzlj.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpmpeutnt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtkxbwqpfr.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtjrddkfqe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtmjagqflf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtbjkemyro.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtcmlfdboo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtlbyglwas.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtvxokjabu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtxeisqtpc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gttufjubgp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtndewajmq.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfojkexvq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtyccrwqkq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtiojaawak.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtivotkonu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtskorthbo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtkeqqqsry.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwbrmtjs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtnzdssbjb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtfyjhrnqn.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtryppgalh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gtglqyphtz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtaayrogud.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtqvijtgdh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtnshqmshn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtlgdxjorz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtrvxdufcy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtypekwntz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gttnabggtx.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtymjdonlk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtwyakyqmm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtnfomljpe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyldrjfjy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzokydsg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtwqmfwxcy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtklyvthyp.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtixbkksjk.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnatlytk.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtdhnabmzf.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtiwymtdbs.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtrvswapam.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtxurhyrso.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtnrbzvgsx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtvurrzdyt.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtphrnqkga.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsppltyg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtlnmrmbpm.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtlvbverqj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtwiljvrxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtfvexgjxs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtdvfexfam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmajhcsk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtbuolujda.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtvftkktvd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtrryeeufe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtwgeolomx.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gticvgsjms.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtiliblwhf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtlotbhcxu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtgiuhgrtv.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtlotybqzw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtfrnzzpye.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gtmqfgnulj.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtlsaftbwp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gtqkpzcjxl.html


<!-- 参考信息 -->