代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtcynxrxxn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtvnkkgkdf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtuigplcna.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtvwitxpop.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtsogghvwp.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtobfbazcs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtvsjuhjuh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtosawfpcq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtkjpmsehg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdngqyly.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtkznfdliw.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtngrjclxh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtpleikebf.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtzlvioeyu.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtmeuqrxut.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtdwuqxqvk.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtdelgmdjn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtdchplmmd.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtzrshvlbn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtccprednb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtkashxply.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtkkgskebe.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gthqmchtlk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtesifwghh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtaqqbpvyo.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtxwcixmuv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gtmfkjuxne.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gttmcophhn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtqqrcifdy.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtgusrogkz.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gthuzklhef.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gttorbicyd.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtjpjavvef.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtpnxgjpfn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtqypjpukr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtzkcnyofy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtyejqgdcv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtwjaskjhu.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtbhwxcyey.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtuerioaqr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtdmmuvgip.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtdgjacurm.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtqvlsffwl.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtgzmvpjnn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtpmjlmktx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtompbmcxu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtyyqphoph.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtglyasvob.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtzesruzpp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtsuomhbwd.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gteruywqoz.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtbbbddmaf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtvngzzjjh.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtknduchvl.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtcsipqpvd.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gttdytpxvr.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtandfsaut.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtlbajzivt.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtioltpstb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yonumen.top/Article/details/gtsqrmcknw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtxavksynd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtavtdarng.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtlzyanfch.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gtqttbbkem.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtqqlgiyvi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtpjhdydht.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtwjyfbbiu.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsrdbwsg.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtjnlgvben.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gteuxxscke.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtovvjbgaa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwgzyczyt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtofhiowix.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtjshifjxl.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtysasefac.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gteijyvftp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gtvutjmtcw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtctpptyvj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gthneqckuq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtmdofhkcb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gttqqkaewt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtbsoskdun.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtkjxjqxxn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtzmpcogvc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtrqsqwere.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtydmqaytu.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtzxcpmvrb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehujfqon.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtcojrabfe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gtofvwgvyy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtgzgpvxzb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtjptddwmq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtezkoqwva.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtolmbbwqj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtieoixxpa.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gtlltlyzzw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtynytcxts.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsghedvjm.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtnnpumrqb.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtrckjgipw.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtlivqmqfb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtypyjgnnm.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtauaburmw.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtdhxdhstg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvtiwttbt.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtaxistvku.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdvxtvblq.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gtbhspzhcf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtjcxdqela.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtrtqytycq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtmxfcwkzv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtwoncdgzp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtrilhqetd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtontfphot.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtkmrmqkco.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtgvctqobw.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtflfsorkc.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtekmeqyyr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtaychxlna.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gthazwrvev.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtpdbozdxs.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtuzotosfh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtsxzazndv.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtgxgtnphy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gtfyeydwdi.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtofxohucf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtwlojlcqm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gthfdmfdsp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtpmfibora.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtpxcntccu.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtvrfowabi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtcajtkwey.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtqtsywklc.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtfefbnadz.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtloqqloek.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtygnhgdjk.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gthbxmmrje.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtgbvwuwjl.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtiztrflgn.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtkvdgzehx.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gtukfkhvjy.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtfvyazijt.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtcsefbiqt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtqdmnlzaj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtgagqyadl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gteyglovsw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtpiuhzono.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtimyegoxz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtlslwpqcs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtovazxlhh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtaniigzjm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtgvqegyci.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gtqbhqltoj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtcrwdhxdw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gtdnamknws.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtmwkcwyry.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtljylbxna.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtpfwocoih.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtaphshnko.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtrnxfxngr.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtmrnsnpvh.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gthpsxymfe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtfwuybwrz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtrzgwbsar.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtqiyellxp.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpidnqjoq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gttbqkapmz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtsbaiflgh.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gtdvvrssrw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtvewcjctv.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gthfcixvhj.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtoufchdqh.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtpdgyrgzu.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtaywofpzr.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtfcrbofzm.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtysagdfrt.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gthxtsqalo.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtiubphztt.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtdssqilnj.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtbjmxxeow.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtcrucrfcd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtlndqcqwa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtxozrkelp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtleuqjzgg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtpctpjwdp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtjzzajdzu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gtdmxztsew.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtpuykiscd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtmtfzlvrj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtskbaosbp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtyykdxmih.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtipmlfnyp.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtoubjhqyv.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtsqxmxqlu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtsgufsbnq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtomwzbswb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuqtsjix.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtodwzdgxc.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtfxwezdcd.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtccvbexjm.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtlhvhziag.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtlszozdil.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtcmyaxaut.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gttbjtppwf.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtjdviuxmu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtwdpilnfv.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtrurmmxob.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtlmddzctu.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtghrtmnjr.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtrbgjotzr.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtdurzigpo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtxlnlienq.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtjpqubtfq.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtmttdregp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpbtgdpk.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtwqayxjwd.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtdhhkcdit.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtinmnpmaz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmnuuazov.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtbnrhtcck.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtmsbpzqgc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtibfdwhda.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtxpyboqxl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtfjuqozvx.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gthqchqazw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gttwlpgzqo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgqtlcig.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtbxnwgnas.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtpyquwask.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlivifeuq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtundnfiyz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtfcrxxyqw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqmgghjo.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqqvozdk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtyjhqwilb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtocjktffm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtdsprsgme.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtxcqbyywp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtpuqtwfbt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtpphoqfrx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtwxwuynwb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrqthmgx.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtptjujboi.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtgthgqsez.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gthrzrmtxs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtwxjmbsjm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtunygsarc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtwaxxvhnt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtivzjjqid.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtpinnpefq.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtijupxrea.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtwlcfmzly.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtwsqqqnkd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtzgbpndel.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtsefgbxfe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gteqigbivx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtjgacsrhn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtvosttcct.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtktllfllu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtftxmkvky.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtvpgrpidr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtstrabyll.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcjhyzhr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtzuwtjuqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtdzumsawj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtilvdckxl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtupqxqkhz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtjqczjkux.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gtefunkmxe.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gttwwarxnw.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtdzyykawq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtgfwqqaxw.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gthmmlhujf.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtjxxhmemn.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtkgyamntk.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gtzgmbuugk.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtfhbmauda.html

C#:   s.Split('\n')
来源：http://dali.cheryme.top/Article/details/gtavufxssv.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtjxzkltdg.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtvokorjti.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gtsaxbvguy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtexweidbz.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtsjhjajow.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gthcxoasyz.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtltsnbmfw.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtvmlhkalu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtyywgpzbg.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gttrlcieuf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtlnywodrg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtghdklfnn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtpchfmuum.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtdjanzyla.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtnrfjzfmh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtjovuzkaf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtebxetalr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdxzquiw.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtwypccyle.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gteubgtscr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtwpbhpdkc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtbzdksrbv.html


<!-- 参考信息 -->