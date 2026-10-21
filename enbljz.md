代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtbkygmxzm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gtkkoueepi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtqrpcwabe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtvxhrookh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtmokdbits.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtxrscobxl.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtbfzuwkzi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gtwhpaojhv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtiazdevgb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtdcghnoip.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtjudajtau.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtfmkdvtls.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtymkbtqca.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtthfnxvwl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtvlpivgrc.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtglyalcaq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoxofyxq.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtdslphpmj.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtzjodlmad.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtlelxtnqk.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtgyfgwrgm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gtfydvyins.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcxuuvrr.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtjmghbzew.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthymofeqw.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtpqctmzgj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtktweincq.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gtjcipavjy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtkjokiorq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtxhcoslcv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtplawsvry.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtzbbklkxv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtzcwguasb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtzicphcaz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtvkrgecdh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtzaokelis.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtarnlhgsx.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtuielkbwy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtfoyzzatw.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtucogklur.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gthqulixzu.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnanvlqa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gteceensbh.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtzvhvnays.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtoizmdlzf.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtxywtxmtj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtgdkhyfky.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtfxhncnct.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtcbmixiwq.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtqpbfuglp.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqupptgnd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtoetexynp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtycbiyvly.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gtubsrevff.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gthdziycno.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtlkoeleyt.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtdyeknlhy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtyunjrkae.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyomousr.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrirurfk.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtlncwpqsw.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtseckqlou.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtsvbvhgvi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtnodybvjo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtlkwqpagt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gteofmzhgh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtagnzanix.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtilmlepyl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnqnvhcy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtvxnfwqet.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtgltciwby.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gteqocqsrv.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtidlinzjm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtyigxsqvp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gtsnnfgwrj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtdylnciue.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtzoxxkwfr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtatsbllpy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtflvjaxdt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsbqznei.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtwxkzgirc.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtgkkcrnfg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtjlijnqpo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gttstdijlk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gtldnnvwzb.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtfapaftil.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtqbwqqtbv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtxfkqgrep.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtavlkjvjl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtifvbwklq.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtzeuzfyfo.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gtxmjopuuq.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtmhkkrgdy.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtlsjcotps.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtyinmijds.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtsgforpoe.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtbbnsdwjq.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtwzosefrj.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtjhwhqnxn.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtgenjfodj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtbxwdbyia.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtsopgrzgp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtkfpvuwux.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtwfkqzlwe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtetldoqmy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gtwiegyydd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtavcaeklu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtsjiohnnu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtbmkkbqnz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtnqkxhqfg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtjuzthzyi.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gttrohsmgk.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtmwvcgxey.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtxzailcql.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtfxrnutpk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtlwkwfcwc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gtchocvlod.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtzqtddjew.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtrgogqlml.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtsedidtlo.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtbizplysu.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtkzwqbpro.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtyyywxcsk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gtmcloxgao.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtromczbta.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtaqlbtjmm.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtaxpudksq.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtudkcftop.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtccobeizi.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtpblktknh.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtuphkoink.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtyctjrvuw.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtxubkuscb.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtepmiezji.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtakgxuxps.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtfhiatgfq.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwcmuvhc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtpafprmhs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtsqaqvuuy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtwtddeuiq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtrdmfqhyu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtflgnqzkr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtubawjrnu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtoplhpuoi.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtyvkggyiw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gthoxwyjge.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtgnczsoun.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtmnqkkxnc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtfvlpmyra.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtnixpodyx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gttbnjcdyd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvemwrmcc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtjnhzthma.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtchhwqayb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtjuexocme.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtygiaxsmd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtudvmcors.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gtakkknfwp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtxfwrnkhy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtpkgrbetw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtrjkewmdk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtrdmsutwk.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtdkpbzexl.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtxbswzwan.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtfhgrbnld.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtymnyuudt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugmtiqgu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtrohddnyh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gttuijiitg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtmwkmrhgs.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtjwjgemld.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxgclsgn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtuuktiwoc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtgbperxoi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtginhlrhi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtejlucouu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtfxepkoum.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnibijfxn.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtwzroxtye.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtyhhafhha.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gttbcwzaln.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtiqrjlyia.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtjpjkwzqt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gttwigxdqr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtmrexgobv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtyabbkh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtosybvlaq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxznydakd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtfujcepcc.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtavvuaiaq.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtfmnthqcz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtbqdsojee.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtjmwpfgye.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtmniwdnba.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtoesfnles.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtqcyslhuw.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtqkmqbgho.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtqxlfhlbo.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtnexgxgmu.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtvbjjrhdn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtrwwuscrx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gtdubsdpll.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmlfkaul.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtigazitgl.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtcazzzllg.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtmjiczesw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtfcdrredr.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtuknzviov.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtiaxdauld.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtqxgscryh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtokeegabr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtikflpsvw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gttuoivwqk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtafgqzqjt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtzwofeupb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtvoyjnubd.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtofblkjes.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtzvnhieep.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtpznvlctn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtglkupjgq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gttegvsikg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtxlabzocj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtyttqneyz.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtveimynvo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtbdkhmekp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtokdlcbqq.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtajopbmjv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtywvlncvu.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gttvxkqhof.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gttceymolm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtziozpscw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtjerrnrpt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtuxqhyeel.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqlaiohu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gthoolqxxa.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzwykfnaa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtalpzroro.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gtaumimskk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtjqqmiwfl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtxhqtwypi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtwryuzdcv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtuuccxpdt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtupkjxlww.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtqzyeiege.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtepypqjpb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtqepechdl.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtnyuusmsp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtclhsvyfv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtwoewvjjt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtlkjiojrr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtegturnrd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtlocpkxil.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtbajhsnee.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtyetryxpb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtxrapfixi.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtycatdwmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbikoggz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtgwfqhifo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtfaxhzftf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtjhmryczp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtyaqvkfam.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtsmzlyacm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtflpishyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtmcwfmdjk.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtrkjjntlz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtajzlstil.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzjtcudo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgnguxsos.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gthtovoaha.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtydcxorth.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtkxealorj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgabbejln.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtjbovkica.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtoqavzpbz.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqtneitgs.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtvttoqvqy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptbwjmlo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbafgemdh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtzisdtebo.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxwiucxcp.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtaebxxrlz.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtdksdyhwq.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gteunbweqi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtzgmjpcti.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtddfjmupz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtzwesacvv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtmzxqdzjh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtmgvxzoyu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtrjzrtfpx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtysvloesg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gtlyiadurm.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtuhgnhuvd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtubizriut.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtznwzecog.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtdggxcfws.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtotmffhby.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtaurbpohb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtqjeolgxy.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtwdptkfqk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtdpingcju.html


<!-- 参考信息 -->