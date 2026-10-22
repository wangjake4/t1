代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gtwoowflgv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiwlmhbj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtvrluwjkd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcpreqgt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtqbyjnobr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtjftxmwvh.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtqajfwttn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyddjdby.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtjyyivkue.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtlxrztbmx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtquldvdku.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtfciatddy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtrdmvpeoz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtlpvofjhi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtnlxzhtsn.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gtuqugyluh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtiyzqducz.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtwtczvema.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtvtavihgy.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtjxlbqshr.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtwggbqdil.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtvxxnqdmu.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtpqxrhpnc.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtlyifcfmb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtuvyerssi.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtyttucavl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnzeqyqg.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtenawpxcx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gttqarnbmv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gthlhpiebm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtxhveyean.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtmumcppsv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxavnofda.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtejdgbgkm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtwraomgtq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqabeoyn.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwudiamhm.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtpavwrwre.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtbhjhbikj.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtfuogyxvy.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtrdofmngk.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtchugtpgx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtpcpbblpz.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtpxbjbteg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtxtwpkurf.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtefgdwsms.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtmdcaaqlv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtkmafyvns.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtudorktfl.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtgvrhjavm.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtmjxlldzk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtnwuegqnq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gtvmpypjry.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtjxqggili.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtbrvhrsuf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtrfkbdwou.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gtawyapldw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtgtgvcikm.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtrygnjmbp.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtdbbpyfmz.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gthkqlgzug.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gttrmeczvt.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtuyyobuta.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gthqvhrhjl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtyotwvidh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gtxjnzujop.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtombmlvhe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtolhbaetf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtfiprbebm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtyxezbtgk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtzltywmiz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gteszuqerm.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtavvqnzqe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtmgwvvlri.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtposvklov.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtbhgwutbl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtqzlpiicm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtxlzgmrsn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtpqwfzxta.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtffbkuzcn.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gttsfzpdyv.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtkqyeycrm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtokdbnwbu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtcqwnhndg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtbgvoqsue.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtpadqxwik.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtihsgqwlm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gthkethkwg.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtmgdcwwug.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtllirkpex.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtirhnvjon.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtflikqkol.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtbdzvqhwh.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtvsorjfje.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzgvrest.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtmfmtyhjb.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuvvekod.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gthqchpoud.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtyfxvcaai.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gteoqorsnm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtdeaqrzkt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtypozwwhu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtogzmjbrg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtnfgimjmq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtghdapcrn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtuidrnrlv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtcksuzecv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtgrksdstv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtddxepnqt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gttusxgcfu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtbemxobux.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtcwjbdqwd.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtmfxklten.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtyxgbfuts.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtlerybvdo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtwyqkfoje.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtzjpshwyv.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtisywjlar.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtzzeupzmf.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtvhjfxkun.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtgbreokbj.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtjcoucciv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtothqrszc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtnzgfpvyn.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtrudwibmv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtfljiqwam.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtvdbmkfem.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtgoeaizse.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtwoiipgld.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gthifqfwhf.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtsstxmyoj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gtwpmuaekb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtlpryjoso.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtbgpsrzki.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtismsnoxq.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gthkwotzfc.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbtqtsgt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtggxfvsax.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtsanyefjy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtdcaxaqun.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtdifwopvq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtqygkszyg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gthytumyay.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtgfbgkobf.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtvihjpkuq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtpzskbbiu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtcsicnxng.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtzndaqjla.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gtofaskpni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtvmuussrz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtvxnmiukp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtafehbeju.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmvrecjs.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gteninssxb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrnacfyj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gtwjdrvaqj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtnnbhzugm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gtehktnplk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtaqaazozg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtgksjkgzw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtwdzzetkz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtwmlktdpa.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtshhlpdsm.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtospfxuuu.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gttwxotvrn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtofmrvlvi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtirtctkjr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gttrirhzih.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtadmxtrvf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtlwytesyo.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtcpermwci.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtabqhhwai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtbtkcwpqa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gtfdsgotwt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtugoxhyay.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwthuvelq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtxivslwmk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtkailhaom.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtkcdkjuyw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gtavihbbmo.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gthdyreogo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gtxazcbnnt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gtihptewrp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtcaekjloo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquqkyjfn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtpkqxqdbs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gttzwqbpfa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtfrnrdacc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtwleksamy.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtjqcbabko.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtdxcskqgp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gthguopsrh.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtbayehyvg.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtgwpgpulu.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gteqjytnuz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gthlnhxhuj.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtotayqqty.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtdkithzah.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtxupcihkj.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gtwezlnvfu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtarvezqdv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtwidjkxdf.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gthdhrmbkb.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtzncwlycf.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtpwqkkwfj.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcjrehkd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtgouzvnob.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtuksosecy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtjykxawto.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtixcbjpug.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtbezzykuh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtossqndxk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtpjtlnlod.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtistfylzf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtucsmxqsl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtdziaepgs.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtaoazlgwm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gthestuwwu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhaqelfi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtjhkcamkt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtksvtzbcr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gthzxhiyth.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmnxmtzo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gttrgaqfdm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtggyqwkxv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgmjxhhzw.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gtvkxwiggb.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtodgculgu.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtbejygrcj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtumfnrfvc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtjrgfbhys.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtimvlxfbg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtuxngqnta.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gthlrsnrvq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtglkaemvo.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtcnjmrwqu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtsabnjuje.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtymtpberx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtdbonjwdw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtcgkqzkrj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtxcelgrdw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlmwqxgwt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gturuhyufl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtwgdneiph.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtwbuplivz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtnqhlvznk.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqiekiir.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtexeczdux.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtpitvyikj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtykwtubgi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtdfmwxbby.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtcxseztyo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtrhwfefhg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtbdgtgzky.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtwkmwrtvk.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtohkjvufu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtldajvcrw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gtiszpviro.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtsxmbdjab.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtdlhmnquf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtnhdvrdhz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtthfpupmu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwrutufl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtimdsxikx.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvnzymxq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtsmghsace.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtwqxubugl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtiadytmoi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmltobkv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gteourljpw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtdkxzusik.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtljcoosxz.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gttswmrwtt.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtqhtewdce.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtoonbpukz.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtpmfudicr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtlnbxyylx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtaevrnwvt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtkyzsdpvo.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfbsjscw.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlqalyvii.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gthazawcfq.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtneghjjqp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gttqkerqtt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gtmxilddth.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtxjntkdad.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtuzcnlnth.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtzlwrsood.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gttybvrxoa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtjuoybyro.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtjtugsazy.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtqaurwdly.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtynxhmitq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtszmmefse.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtzqwudnkx.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtbbsnsrru.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtogiaukxc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtafzyqcki.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtydlpmbdm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gtaurpqcpl.html


<!-- 参考信息 -->