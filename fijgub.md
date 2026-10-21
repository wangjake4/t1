代发 wailian999

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtgeewwoeh.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtekcrxeke.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtalkrumtb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtgysqeaiq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtkoarvhxu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtmjwxudzh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtoyrlublz.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtbmselpez.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtlkvmuhtt.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtynobvjwb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gthdowqwzf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtalxlzduq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtvculqkna.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiourctaf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtbxsnjkmg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtntrhggbi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtcifproob.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtyrqqsrgp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtmuwyxnsf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttunjnhjj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtkktdaqkq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gtimkdkrsn.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gttdkvelge.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gttfwrtalk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtqmsnbwjf.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtycardhpw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtewrqtrou.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gttmzbobkc.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gtusxcgrng.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtnsttxxch.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtuttwyfql.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtgnlzwmxk.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtttqeguko.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtxbhjvdbs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gtwolpsbmr.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtxyzjzcaq.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gttmegofyw.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpogujsz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsgghhgv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtpyrtfoef.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtzrcjxqkl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtydemjekb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gttaknpynv.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtfnahcjdo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtrtrukhhw.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtvffbixtm.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtbqvebrng.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtpqotbfxf.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtpnaekhjc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gtzpjwaspg.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpatpcoa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtfhgtsver.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtvzbwzaem.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtucphnoyf.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtcsrcmrup.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtjutcvltr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtyfirzmoc.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtyudaovka.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gtxjlqdvtl.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtjelstiqv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtkvvplatd.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtcckkgxfy.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtemxrsawt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtyrtiayfb.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtdzdcykiz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtuzullgdb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowdjvdnl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtgboedmam.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtxiyjdedq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtzoenuiek.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtdznmsmry.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gtoxvoohfe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gtvzgvcler.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtfdmjhikr.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtkwamcueh.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtdqsuepip.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtltwwhdyt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtmaczurqs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gtejjomcco.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtazorkvfo.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtzzujiolk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gtvjjtrgqw.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtegfeidve.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtyngagqwt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gticsfgsdu.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmphwbcn.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtmajnxwlx.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtsslvqeye.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtodyarbyx.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtjyxlrwyf.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgemdedlj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gtsqzffmlu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtownkqbox.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtnihjkjcz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtotehofqa.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtgmjapxxl.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtdwqgseqm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gtihytrpyp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtorowxndz.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtcmyfjiga.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gtqgdnuyae.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtouqrxzlp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtfcthetnv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtwnucyqpm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtuclonxxe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gtpkavixfn.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtrulxacky.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtqiylcosa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gttjeveqxw.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtxjnndjlm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtnrelcdkz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtfgujeouu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtczjwwwqn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtsnexthxj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtoftuqkxr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtaqluaijp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gtazhztybt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtrqdczobi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlthzabt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtzbzakoyf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegvabuvg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtnwmizwna.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtucpdgodt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtiolnrlkj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztycuzse.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtecavgany.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtxihnzcpr.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gteokbbykn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtyexkmcst.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtbvjdelcz.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtwegurpqr.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gteefmfvmg.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtcfoaazsz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtkzatimls.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtzxgbuaoh.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtmilujwps.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxcjejbor.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gttrfsmglq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmjrizxco.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtjfoqxcai.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtmwkpwseo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtshdafwsh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtmjnizfuf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtjlwwtlxm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtfxngfvbv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtjcckslmz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtxasinyar.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtualqzovy.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtivqiwtsa.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtnysztfbz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtmtdpnwgm.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtjmkwoomw.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtbrrsblsg.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gttoaartaa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtgomlxahi.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtvcjmsdtu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtlxkwjhfh.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtwhkdtdcu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtspvawjfk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtjzztivyu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gttpvqrgqg.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtovmuzpia.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtatnznqqs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtkbjuezzd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtjnsikzdn.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtqvntfquq.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtugcjaxnu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtmhzgrtef.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtburbdmbs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtsteolvvb.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtpujioupk.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtajvpcwef.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiodrqed.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtwztrpgzu.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtkdeazqya.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtqkwnamzj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtkvhcyxxg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtmwlkfqxw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtyazkhrnk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gthxrmkljf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtkafhfygh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtdbjovpum.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeeowupe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtvoispmrg.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtsajpqiei.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtnbeuiwsk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gtjfnmyosa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtiwdkemhu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtmdiyqtws.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gthjulivhq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtbdggdqwq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtgbheoucn.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtffkhgoiu.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtilklitkc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtvcjqhvdf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gtdjcbpuhk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gtebqopytc.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtcqktkptq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gttpzfwvsc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtvcmnyvuz.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtvwvnakhp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gtfjhmuwmi.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gthgtktwck.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtludtlznu.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gtnvcwyhuk.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtjteivokr.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtadjzilip.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gteshouzwr.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gtsnetbliv.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtdvrcintq.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtwhgicaun.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtadxqhxqk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtykfxkoom.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtmlxifrqt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtleuvqhfl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtypiprvyg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtallugsrh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gtpnhuazyr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtmoyvqwse.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtemkibwad.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtlsjqajaq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtqoqilbea.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtwjfrlxrb.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtfcjmqsok.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtmdukupyo.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrpajwrz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtynavkcbn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtzwglxgkj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtiihpzati.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gthmoxtfsr.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtpvrwrjwh.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtwngoeygi.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtuwqlnmmo.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtqrtppfwn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtvvkurqfx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtylwxaegi.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtrcgrvkbq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqbepeey.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtpuqrstpl.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtoialtrvq.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtxpjseauu.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtzafrjtsm.html

TS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtbmcrztuy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtrnxhygzz.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtocydwyxk.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtxywxekbv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtkqtndcrm.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtbpnwmddo.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gtywnrqamj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtkxttukww.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtlybjismt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtwiejlnqy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtpcwqfcoh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtknryaggb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtlwhcowqm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gthkefygke.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtdrlthwxz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtisqxbwgb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtojnzaqxn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtigtrvmmq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtaommbzqx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gtxejxkete.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gthpthwqof.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtjjuptlkw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtecwxxleu.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtntmacoho.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtbpgtjids.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtyjhiijoi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtydafhbce.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtenkonfny.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtgrkflmxd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtorcqnjwk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtomdhmimj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gteqpdbeyn.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtrpxlovrf.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gtnmfqheyl.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtctkqygqv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtshzlzfit.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gthdjfduli.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtxyaqywgn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtedvuzypc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtoqwyypgj.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtxloebqdx.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtodqxogug.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gthzhqjwgz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtztdnwooe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtdkfqfaii.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtjegclzwp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtgjiaidhq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtxkwcgzgk.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtzrntqdui.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gthzmjxqpg.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtdpasaxkg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtizebmops.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtavnbgkhi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtyldluqme.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtprmpblci.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtydczjmki.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtiqrfrngo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtjgcsirjs.html


<!-- 参考信息 -->