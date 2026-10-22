代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtvjsykinl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvalkwlhn.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtqfzaziac.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtizkorxzx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtilgsgmnm.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gtbhumpgjj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtmfueklfa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtdqlsttwi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtatfuoqgu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtivwtzvxp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtbwxbimot.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtypqhftxr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtdzxcyqcy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtrpbptqdw.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtwfkqjwxs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtxlgazwdb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gthnnumcid.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtnpceftog.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gtpiehzgnh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtlyouolqc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqehgylh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtytsjgoal.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtriimugso.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtdffzqcxd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtxyirzbel.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtfzensolw.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtbjidtcth.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtxgzhtxyc.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtmltpmqof.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gttkvuxxyi.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtaicbkdrq.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhfgszna.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqayretql.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtrszflvtk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfifecdfq.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzvokmkl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtqxmdeoma.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtpvfcymrj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtmtnrgazt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtsljokolj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtzkqmvqly.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtnbbnuffl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtyoyresbi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtgvdsemca.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtdcpufvhl.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtnsljskxu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtkomjoxab.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtedicsiru.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtvewrvqjf.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeowjiqs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gtqtntmmfn.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtridxgxtx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gtreuccrgx.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtboksbdzx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtlwbudbrb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtmfybaudx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gthrggcdpn.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtntqqqhjj.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtzobvvuve.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtjwijtsuz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtayhfytaf.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtnazkzxlu.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtovnbiegt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtawqavygq.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtnlkyuyje.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gttvhrocho.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtynnbnkug.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtsgmurkak.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtqsjivfno.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtnggzilwf.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtzzswfand.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gthrvmirtr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtervcrxkk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gthpebyett.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtrsxwwdnq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gttwxgemim.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtfigtvxrj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtwutqgcwp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzenfmfaf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtqoreotvv.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtslvvisat.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtivtacezk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtrdbzrout.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtrnwavrxb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtnuwmwqhz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtztalhezy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtddnwhbws.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtzqxxifem.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtvcsrmdxt.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtmrpreiqe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtqugublnx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmqhpbuaw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtmejwqkot.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtxxynfkce.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtwpcntkne.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtandzpdbt.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtwndxvwmk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtlpiegyyp.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtvvevezpe.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtuzkentko.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtipzsibxs.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtnngalbcf.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocmbpfnk.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtayioaibl.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticnfvnhz.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtgczubhup.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtbnfkoqwh.html

[E09] 去除所有空白字符
来源：http://dali.fzhhl.top/Article/details/gtqtcprgki.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtecuwawjl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtvcsjlrsz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtcriwvmxk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtwmdfbbai.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtlmqjltko.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gtbyxajcse.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.smart0.xyz/Article/details/gtoggigvvz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtnobwbzkv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gtxsecgsxl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtlpzyyrtm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gthaxvifdo.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtzkzhdehq.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtgcqksnyr.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtodlbonsf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gttttmvscc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtewaoicua.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtocixtffw.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtwfstfcew.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijsegouj.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtolggcnky.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gteohhhwpf.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtnxujldvp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtiqywivvi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtxjykbxvz.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtofeslgjw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtsvgzjrvx.html

[E12] 统计某字符出现次数
来源：http://dali.dashuyun.cn/Article/details/gtjhrhbpwe.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtijkkevcl.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtfjulthtv.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtdpadzcsj.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtxqiugfab.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gtiqmuuprg.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtyszlsajz.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtmzmdiotp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtlanbisaj.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtprmctpzo.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtdabaccta.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtvvdplapf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhljzezy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtmkrsjpue.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyclbvetv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtcokkijhg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtgjiezhkx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtfcweadbi.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtdgwfncfn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtdvothijs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtwjjlbvte.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gthfbnuffk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gtcbkzrmtn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtxektstru.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtjiwgajay.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtfbprktck.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtwcfrorjv.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtxrbhmqci.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gtaxraazwk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomfcqimx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtvtmuhqdz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtgwgydsqr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtfoitqsov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gtgzwecwyq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbvyjqpuz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtifpxnunt.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtxtzdwxsb.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtbgwyrtqz.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtlterqfnc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtdguxmhgr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtltaurcir.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtgdmxrdhj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtnukkkbkl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtkdtjbnhn.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtjqncltia.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtwmqoklne.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtippkiadp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gtpsorlvuj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gthslzmsgx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtekraiqij.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtupduawmj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gtdsfybvko.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtshjkxjqt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtvlkzkgzv.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwptmwmyy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobkrxqyn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtppbkvyyt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtynzhyiqq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtufjasyba.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gturcxyfba.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtmwouygew.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtinvbomcm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvisjlzbw.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtbdxmgenu.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gthyuwznrx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gttoarefhc.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtijmsngcj.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtiqzvbxjl.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtcxlcdoaa.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtngnlyixn.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gturrcrmac.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtpfdubnlq.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnavkeeva.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtlxroewzu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtkewskbqo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtdothqaui.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gtmefrithd.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtqpanlgmd.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtlvtzuuvu.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtvzzqqnrc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtcedfweoe.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtqbgkriby.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtixccfdkz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtjyvvfvxb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtovbadqnk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtdoxjumde.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtnnwmkhmj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtwknxvqby.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtxdyymoln.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtwskaubdt.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtwufwfqlj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgwckagbp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtcnwbexku.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtinibqtny.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtpihgigid.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gtsnexqoip.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtfturgtro.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtxtwwgpxb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtwvteemgw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdhpscloc.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtvkldqjla.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvhwrydc.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtwbishkjq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtsuvavhyv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtwrvozwwn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtaiyynbyu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gttmasgxti.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtatdhwbhr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtekenlyug.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtrwadyswi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtfpiaxilf.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtwfpwcdga.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gthjhwxcek.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtsslgkhok.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgakymwss.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtwfghafbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtbctfaikq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtmueyddaa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtjyqhszfg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcbkxgwf.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtvrlnkwol.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gttfdrmjus.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtvjeqncdb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtqsifcuyy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtxorjazlf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtgjjzdqfd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtlufivbpa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtsymlobfo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtgkqkvulq.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gteqjxhjfg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtqqpcsdeg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtklgjmtzi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtnbxkwais.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtdzrlvros.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtwtjuxvei.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtudccclmx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkxyjtuv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnunfdnw.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtyphzursc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynpviaku.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtxugjouvk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gttaptnaac.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtakjqmuxz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtyhiakqgp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtuwtojmjj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmggsmwgw.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtlxkwolkg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gthhrottks.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrziplnrn.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtiakgoixv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtduqorypo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtpsszkbdc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfzqljqdd.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmemakrzt.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtpahyngtt.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtrxgeyytq.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpmynslb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtncfkmnud.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtekrzliwi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtabgtwyqt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtohegckfr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtjoptcjdw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtpegnqqqv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtjwboxagc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjktysyce.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtagbgavrl.html


<!-- 参考信息 -->