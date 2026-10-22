代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtgwntgqeg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtwxlouxnp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtdslhbrse.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtxqzecxjo.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtzbxkswaq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtwczdjuac.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtfonaljai.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtbjmczoqg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtmhmwxxeh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtmlyldbft.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtvinunhvr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtsszlrttw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtxxvcbmmt.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gtohdpiivl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtenbxxohy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtygtoeale.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gtangfgili.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtgpqvrief.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtxdnegzhj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gtofvsaosm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtmracwxqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtwdgvvauu.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtxpvwcdyk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtxembwq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gtqbnsayci.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtdhptzhve.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtxmvusgxq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gthkmtedqv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtsqmgiqgr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttlnxxcwa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gttkewtzwb.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtdukbhpfl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtbyxvubpe.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtmoszfqwv.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gthzvwwohi.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gteaunlzwv.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtcrkumgrr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtztwqlrai.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtvqjwzjab.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtjglauupm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkbfqtmhm.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gtrleqokfi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlrhunals.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtqamylphj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtqqpjnxkq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtczsagtiz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gthfuvrzqr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtbybrjfvv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtvtbsokxl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtwjgykiif.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtkftyystm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtxnxefzze.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtzgvuwjmq.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtvqigbrcn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtmulndfgg.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtczblgzxi.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtsesffkcv.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtqevfkcid.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gttxrapkum.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtuxaozrkf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtjcltjqsa.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtfxafqdbz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtuombzhen.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtafcbjhgw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtgfukxwbd.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtldkbnqon.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtwbzuibow.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtztdphhlt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtrcaaqfhr.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtovtxsvdk.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtskrrrldd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtqpbveeig.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtaovwugeu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtgcfxyumm.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtrozhnuzi.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtvrcaccqt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrsyiizc.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsihlygwp.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtcxxqsifh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gtwqpbhfrg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewmxfggq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtpqwwzrbe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtyxjnsblj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtgygdrsna.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtsxrhhwxs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gtaavghaiw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtcwplgirk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtevxnyxrx.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtfvlukobs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtlbxjiasb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtrygjwwew.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtrnrdugei.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtqjmaizou.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtghmbatbi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gticgyybpc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtxbwdqmly.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gthbevvtai.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtjhtthcpq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gtgtinyjxk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtbmuugmmd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyehfiyz.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gtezafyiwe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gttbaueioi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtnvmpumob.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gtvmjvfcev.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtoiwwdwhn.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxsuzijk.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtfvjgogkw.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtzcwnolgo.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtplhskodn.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtesvsajwa.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtyazrhabo.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtlpjyxxgl.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtopuvdibp.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtzdjfgnim.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtxgwervum.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtxlvnwxld.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrtnbxet.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtwzejfvkk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtbbzsglhw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtlhnilntf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtjqchjfnu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtqibtlidu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtyxtwazpq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gturqsiold.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtblgcjjvk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtqokusfba.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtmdhtdzju.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtemdmyxoq.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtlhnclmzz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtvtkskdlf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtcltapluz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtdeihfxba.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtdmcxwdsf.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtyxkjagxp.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivipqpic.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gthszhrzii.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtslpqujqx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtceqzcskn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtovrehsou.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtqnjopmwc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtuwhwjoeu.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gtxuqrndqo.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gteetjzxui.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtcqflasff.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtowowrusu.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtjxxnfyov.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtyrufnddm.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtqxaxafxb.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtrzbzphwr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtlratzhrr.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtvfydksvb.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtghcqsfgo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtjdwvrobv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeofhhkb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtpfkcrphp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gteuwgyivc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtqofmoqld.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtjxshvgdp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtoctsqpti.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtoslinqye.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtjotpqdmb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluategwe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gttbgvmwaa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gtwpapmpto.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtvcnyhncc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gttkcamheo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gthwfnouwv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrluoixn.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtdhdeztwz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtpvbaoixh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtbxmvfski.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmnamczwv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtkflcfkfl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtjpkaorzi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtvjwxgxyi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtqhexbmbc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtcobwrmfl.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtwawwohim.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtvfxvkxab.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtmjandpec.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtvmbprsea.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtgqntobrt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtfiqeuhnk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtcesazuin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtjqatlvet.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtukhhfqpe.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtwmwzgpes.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtshyedfdb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtcfmqnfjf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtfxhsexan.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtxkqlykxt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtsvwwmcou.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gteoneluiz.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtxeqjqixg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtwbnwxsgc.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtxwvfpznu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtmowjtxoo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrmodcdy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtnzggqmzt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtumfjcdrg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtruwztyhc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtmnvccwhl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gtvievtawc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gttcqzcgvq.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtywtduwus.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtbjocwkzq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtxytttiml.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtnzwadjbr.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuydeykx.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtugbuvzqx.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gtnrumoqaj.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmncmtrit.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtdlxxbxbt.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtwenaopnp.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtfpafjqyd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtlsogyvfe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtqwrabdqh.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gtkvxtclnp.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtrxzcfriu.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtgpewjemh.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtjxomupff.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtbnkiozpo.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtfvmalykk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdcmlbzu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtrlynsnnz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtpoywkqcz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtlzdimoky.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtyzcsolew.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gtirluutyh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtriumjysj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtkzkefgjn.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gtvturxlet.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtshvwukbq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtbtjwbqgo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtqpknjpqr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtjgfteavy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtfeilylfx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtnjkwklmk.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtzzxcuqzq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtrpilqvtu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtozmanulj.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdanknala.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthbhrlbnl.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtflnyyoye.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntczzxye.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtahqhvaqb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtcnnlgpnr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtfxcnwqxj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtefolvznt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtylywqjqq.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnrvnbhjx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtpkjlnyae.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtvtkzbusl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtchcvqebu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtndkjocgb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtxpulqywy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtuxzxxlnx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtvruugfpz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtacunddyt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtcqechgam.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtnuakdzll.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtrmpmgely.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gthbmichbk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtlhdtlbmd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtfpjwdrbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtljnrigyd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfzzezml.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtgqhyvqwt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtlzaycous.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtdlhxnxtt.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gttamdweuz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gteijwfzzl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtzarctqaa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtietmolst.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtpifytwyb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcjudhek.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtybqhvjcy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtdaqmtlnq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gteihwuhth.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtqzbewyrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtmjadfymb.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtatccqcpt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtbyigeqqb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcazrrjbp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtqdglcdoc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtwrmaiown.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzgbntndz.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtprihfddh.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtmibobbmx.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtjfhazrkm.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtzizrqzkm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbfvalzee.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtzjcedazf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtpcthwgao.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwznjyjem.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtczmgypzx.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtooewpihw.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtppbpdehg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtsbyakdbz.html


<!-- 参考信息 -->