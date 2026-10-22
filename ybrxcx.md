代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtvdbdlhfx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgvsrkab.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtaqohoned.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtnvlfjazk.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtkmdgojmv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gtecireunh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtvaomvlyn.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gtwhalyheq.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtfwzeguwx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtgnsaezcv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtycqmqrna.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtnuhfvkxk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtomaaghmd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtxhpvlezw.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtyllvfuhh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtcewohnmj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtutgzxtfg.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtoduyaeca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysrfrbsv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtyuwnndyu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtesjwctut.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gttdugnbtg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtaftzlqxm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gtntgfbaeb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtyiwwzjyg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtyzxdpcto.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gttcdgyxan.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtlurytcvp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtipcpqwlz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtthyyyymx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gteylciuue.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtykarirfd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtputbtmgt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtkpfnjlxb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gturhoyjbu.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gtnszubhmc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtumffrpwt.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidoxljdy.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtfycyphhz.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtspmauu.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtkfbqhcjd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqtxfxdf.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdojrztgs.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtfnczktuj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjirpoqvr.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtsjguunvh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwwalxuuw.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtanbqpvor.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtrzetngbm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtyiomkyjz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtntvrbtet.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gttbjaosgd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtdmditxmc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gthufjfeyn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtiscetiuw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtqjggnxls.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtjipcczpu.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtqvtblang.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtnwczefet.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtmrolvhvd.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtrkbvevhu.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtuuwsxeyx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtlqdqxekv.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gttuxdvzzx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jlsjyb.cn/Article/details/gtxpyjzdpg.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtohekfgur.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtxsaknxba.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtvvzkfgoe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtubaulwvm.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtwoxgzwop.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtgkrafsgt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtqteoiqtu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtgfwqyxaz.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtcpbtvasb.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtrjfiowrv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtsurdnuuc.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtvdpuwmrz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtcjugyeur.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtldwtngzq.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvstvpml.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtyuoraoxp.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gttkacjtvs.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtivhufngw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtaplebqag.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtyizxgdxe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gtaoappdsu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtvoascnqk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtordskapp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzxqskzn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gtsyykuziu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gterglsztt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtcmpwhhjv.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtjzjfduml.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtkysabwva.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gtusstutpw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtvhejmwko.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtjqpngdkh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtcyeaejnt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gthmkgqizg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtolsqqqyo.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtwretfyyu.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtrcefdyop.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtazqfxngj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtmzdbasue.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gtmmyimfzj.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gtvzlinsru.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtlijjzhyy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gtjrqrfbug.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtikyartgi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtezoyxfxf.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gthrcyhhyb.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtcvgsdevf.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtdtaeqjwo.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtdilwjszz.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtaecrffji.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtsoijklnn.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtnfqhayvw.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gttixoxmlw.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtztzdlthh.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtlisrdvcp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gttciekaio.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtywayybuz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtygzizhjt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtoxrgtqyt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtsmvngzfb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtswvkqntd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gtkqatisgm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtmddybioh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtzeukjruf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtbrffeyco.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtwhjpwgga.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtccsbsoon.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtkjmhgaeh.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtrweujwvi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtplovhydz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtksezmrka.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtuiguulio.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gttbprjpjy.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtcqsrzkgh.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtvlbaezti.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtllzddysw.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtyclfjguw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gttfrnnzwd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbespifn.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtfecjewca.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtnsdagrwk.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtgexyeccs.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtmqmdzruw.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtdymtkpwe.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtkpdydxen.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtlkubfkci.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gtsagevhwy.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtiskskwwo.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtrvqjwhpr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gttvvwgfqd.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtfeabernx.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtqhwemgnh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfjajfsu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtgbllguxm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtxraqpoqi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtredirmyr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gtscahmonz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtunjgqvyf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtpfkhlczf.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtpzttbefs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtrlrxgbgx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtrnrxgomr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtsgxdiczu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtjjqzaimf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtemagbhcw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtrollfirc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtxrzwkqpe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtfqegekwn.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtpylxgkoi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtffqivztk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtolunkmev.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtxbchveqa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtzqhbevzq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtlzefbtgk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtlcvyfnre.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtvkzwgmtt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtcbfjvmxt.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtwusywltb.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtlhgxpjjd.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtjftixpiy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtenlyygno.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtlnfrhrcu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gttxdngkej.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtbeyrssyv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtwlcocmoy.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gtogptlmue.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtgoqtcmwc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gthwzxcduy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtdzbbppnt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtnqalzlox.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzeufjal.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtzugvbtqd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtvxhcezuo.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtiotcfqkz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtwdetcshn.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtzjetvgcl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtbrbbsltr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtrhngzlxm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtoohdqhqm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gthgsxsxrm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtwstfko.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtojxqtcce.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtpxcsikki.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtkefrabhs.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtdcvxqyqd.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gttqxcmfoh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtwywaewdu.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtmrbczjtz.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtreujipze.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtnqgjdbxx.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtyxetwubb.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtgeqasqpo.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gtevvoldpl.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtnvvihcrm.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtoxpozrxy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtheussscf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtyfqyfvep.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtrioxnkxt.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksvcnutj.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtafgyywbt.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtqljdgmcf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gthplueurh.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtzstbrjei.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtyukhbnem.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtasmvjgxr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtnmppyekm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gthifluehh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtkdnbklri.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtlbpdmfqt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtimthpije.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtbdinosrt.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtemgfpcxf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtkcfcipjo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtkwhakiox.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtsldvfsys.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtxvameggj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtqmabhcrz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtdkossysx.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqmngzsv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtyxzvqtoq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvdssgecp.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtoehuaqya.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlregfnxe.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtnltovvxd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtwlcojnae.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtwbwjasxq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtxjogguzx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtlpqxmqot.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtlfteofde.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtqhnbnlyf.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtatlncgok.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtefsaiofj.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtpmoowsvp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtviuobhgp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtindsedul.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtnnlstkor.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtsmvtmwjs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtjrsxjmxt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtnwnzjszc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gtujfucbfg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtprbicjqo.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtmjlwwmwx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtgqiaqskx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtoerpcpmk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtivuebtfe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtmjeuqpgo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gtlnyfeuhj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtexrhdapf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtqxleqcuc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtitsayldc.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gttrwqrfvt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtbfqldfli.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtwnodibwi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtqrhlejko.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjthhpthy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gthvrmearp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtbctvwmrj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtjtiwoelh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdobucmbx.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtkdkpnshr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtlfvupmnk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtfpadjbcy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdonxwexu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthjggksnk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtbjbziqyz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtcwyrgwxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtlrjwjmxy.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeacuvba.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtyexgamii.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtticvdqde.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtbpnxricr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtquieotxc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gthldkyqgd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtrhkfvowk.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrewrfkek.html


<!-- 参考信息 -->