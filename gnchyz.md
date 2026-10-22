代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2wchcmkvu.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gt2lvqfegii.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gt2aqokyafx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2cudadvyn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2hngtbscr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thhexqsq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gt2yqcqtltn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gt2huesqpbr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdsbqzo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2uhntkebw.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2pctmphhy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynwohfdd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2zeheujza.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gt2wbbscygo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gt2mdlmrhih.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2crzegeiu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gt2vlxxklmv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gt2wkbfrfpc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2dsanxrei.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2iotjzwaz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2uyxhsshp.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2jfrtcdgz.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2grbrvjdc.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2fivutbnl.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gt2hqinyijy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gt2tlhjhovu.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2hrayoyvc.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gt2gdhvwgcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2risnvpii.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gt2rdtuxbqk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2zbgkolwj.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2udlvpunv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gt2klaxjfem.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2zkyzgdll.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2jvubcxya.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2ohjuukdk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gt2potnflov.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gt2mnjmbdut.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gt2qhskylpp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2fktubmst.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2skwvaftz.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2ropsallp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2ofaxuvup.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2osajnzdl.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2hqjtgsre.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2temxjsrc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2hnplcyzi.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2aqankfnp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2lvwsoqxm.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbqoyzsg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gt2tklaagro.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2snlgnkgb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2qflvkfrq.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2ruubabda.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2fvtmovsd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2usgtydxt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2lnrveaqu.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gt2lwnzruxz.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gt2xszftobr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbhfrwix.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gt2ykomrqta.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gt2sdmpasgh.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2wxcjisyz.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2mwchxyzf.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gt2szldhzrx.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2xkimugoc.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igqhvsjm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrmquzxd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2tjzgwahn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2qhhaxhca.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkarwosk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akdusxoi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2cdnbyukb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gt2qvaoftxe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gt2tnssjjpv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kiiovypr.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gt2agjxpqwc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2xsuvpqwc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gt2odajakvf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2ecqdqlfj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2nipibmkg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2trspsshm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2amkscbdy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmrfpzok.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2pllerpgc.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2lqwboeeb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gt2osmjmvjv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2fjghgqqk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmtlvcto.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqpjhibn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gt2vizwofza.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gt2mtdrluvf.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gt2snxpvfrl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gt2rakerkhd.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gt2mgirojyr.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gt2ckrlzbvs.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gt2evifwqer.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2srsvyojj.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2hxicefce.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2vgadibma.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myvejjyk.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zerylbzf.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2lzvbrtob.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gt2bsojeafo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gt2vopmigih.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2mfahstdi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgtujyzz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2ommzctbp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2algslpyw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2uxasekgm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2qrpvwlgy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2rwwdthgp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gt2cgbpqrsx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2yvubjbdb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gt2yzzzayvc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2ljpvualj.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2otnmnxhd.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2gbacefgj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2fsusrmvw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2vjdhmquq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2rnzgdiay.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2uviywpra.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2kajhmdco.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2thgsqsfl.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2bmyzsdnm.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2iijknbkl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2jflahnyc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2xnztuvja.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2gmkelwoo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwgpkugv.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkjdzhoi.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2jlewzvrf.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gt2tyfjuxln.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2hedhbqcq.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eymmeplp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gt2kpzsonds.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gt2tcsqvxdi.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2dsnuvetc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2cbzxoxih.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gt2enkxqtzg.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2mjujkoie.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieqyuqlo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2behgiahi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2dfwimxrv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2vawfvbnt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gt2fqrcggvc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gt2pfinyrpz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2wvfiefjs.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcbqinld.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2atxgzwuy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktgywgzq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gt2gxllzkyu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2twoqbupr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2fizscbnc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxtvnlle.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2kbstzssw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2yynqgfon.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvnqpddz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxztviav.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2nuaqjvlw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2umnryqiq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzyehquf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gt2afxwggpz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gt2vrimgigc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gt2xmpmmmfm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2vypiauzo.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofkmmtwq.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gt2bxfgixfk.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqgwkhcs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2rjakvqtw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2ztzdavmz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvuiajf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gt2vabobusn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2lhfghfns.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gt2fgltpiep.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2chbiffbe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2iptyqube.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gt2vrrgomca.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2cnimruuf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsyjpqfd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pztkwygq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gt2pficpzyd.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2bavsveue.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2kgrsfodq.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2wosxfngn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gt2wxbuljeq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2azsxijhr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2pwkzujka.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2jkfreplz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2sjnmumbe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2nyyqspdb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gt2khfbqapk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gt2fajbdswe.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gt2twereuxm.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2tzwzkwtn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2exxibzue.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2nvblnflf.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2qhheecxw.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gt2ziwelblm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2zjxtghhx.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gt2wetjzilh.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gt2lonnsynf.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2lvkzzhhs.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gt2pfhokcxu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zggieoif.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xfgwltqj.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2mnzojonh.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hehthgln.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etzuemkz.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gt2dryfaqib.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gt2haczbskr.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gt2wucrnqgj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gt2cfepfchs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2zghihrgx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2ilcodlnj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2kupnwgrn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2nrzeocad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gt2lzrllwue.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2mubqrthm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2gtlepnta.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gt2soervovx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2gitmmupy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2mjjpqmod.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2oaxmxyrm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2fhqjzind.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2ymfqzanr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2besthbzv.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gt2lfjuieed.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfdikcfn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ptokwmsq.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqvakgts.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2imaqxdew.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2dkpgycrv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2sajxwhhu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2znusokpd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gt2afoemggx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2mqbkcpds.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2lypqlfmf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gt2ecebkedc.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2lticmjfz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2rozqayqc.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gt2sbthimhn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szskrsgy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2brjrrqin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2uguvbkay.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vlgxdsqf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2ezpumpjg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2oeyypect.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gt2iyrxyiux.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2rznmjvyf.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gt2lenerqtf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gt2qefqomlf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2oyfijjte.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2bdzojsqv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oermgbov.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bctsieji.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2myqoulva.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gt2hpmwqzqk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2yweyuicj.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2nmzlsxaf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2eqjehmmn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gt2nmqvslgw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2ngiieyci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2kqsayeal.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2elhknhhb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2irswrpvq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gt2hajktakg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gt2zgumyulk.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2rsjhmzvx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gt2faoomjas.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2rmhscnno.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2hzuyudon.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zzuhlnxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2iskjblav.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gt2xwepwtla.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2sxwyzpva.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2oehpecus.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gt2hfvhkgbv.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjppwdeu.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2zmtgxrmd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2qqqzaaeb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2mstxyfbw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2tnsoiepp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qudjlqne.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ocwdnpnc.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2pzrggyiw.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gt2bufcilfc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxrdegzz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gt2hlklmsbu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2nzwavews.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2ljkwbbef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxuswiro.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkxlziyg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gt2kjveheay.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gt2psapvgsm.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gt2fcxvhyct.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2yiqcgndo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmfiiebn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2aygrymwb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2pervomnj.html


<!-- 参考信息 -->