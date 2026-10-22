代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtkakbdyjv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtklnzbokt.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtgvxqorzb.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtplhxaioq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtdvyskeeb.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gteicgsanr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzutjiiji.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtsfwmlhqt.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtppbemude.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtrwraxkud.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gtfsijppux.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtfmhxzwip.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtgvxonppi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gtmucrmnbo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtjkfyznsv.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtukvsfdoj.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtquualgfh.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtayeujzhn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtplzqymoz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtgnamdeth.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtmjqbjhji.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gttozmiyho.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtcdeeltuq.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtadmbmlil.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctbzfkzf.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtkdisiuvh.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gttludllrs.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtiextujvq.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtdnkocbsu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtmotmfrob.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtzfnchybx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gtxbprkcbj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gttcadmbeg.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtlclhdwdn.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtwcfsrmxf.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtkmqcvscm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtbxngqsvv.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtahmsavfj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtruakfpfq.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtxaxotcdb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gttwqfkxek.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtwnhsuhgm.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtrsxeiwyh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gthecfrixt.html

[D19] 按字段分组
来源：http://dali.chenzaomai.com/Article/details/gtnpwvscha.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtrwoetzhi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtcbptjhiw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtsynjdgmy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtiegrlerz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtvkgylnpx.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtolqzqxkx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gtjbkjkysj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtvmjnvfmp.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtpocrhiyv.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtrtevwrmn.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtqrageckd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtliebdvyz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtvfzptjhp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtqowoducz.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtyhtwfcay.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtinkoxcuw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtpayciqdu.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gtlygqscfq.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtrigvbzja.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gtuwfuekco.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtudlhfsda.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtivfhwjbp.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtzbjctdwb.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtjfknuvwc.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtezelqngx.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtbouvcxkj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtbjanpzqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtlecbescu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtbzdhkeng.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtncqihzdt.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtklzozlbk.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtmqmepuvh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtcssmzolw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gtxayqxrnk.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gttpwxxcpt.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gtfyrffiry.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtzsktzjfy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtdqrdyneb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtisxhwktm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtqfropvhz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtczaoknlm.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtxukhtvyt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtyreeaebm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteulesgks.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gthbkxvwbv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtfbzvfwpl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtrgvwyjyg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gtffgmchoa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtqirawojf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtwtboekik.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtibnrqagr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtyalzdeeb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gtcflftfbj.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gtwniehitu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtqixrsxbu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtbqhdfldy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtdcpjxgze.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtcsatjtnt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtchoihnnl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtrjvggqmp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtpujmdpgn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtedftqbwp.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtfraszutk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtiybdkrsc.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtcqfzuwnl.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtawahabjl.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtojpyglio.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtzfmzftlb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtnzknhspq.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtoefbaflq.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtopvcrbwa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtletquwcs.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtotkycxqf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfpbbzznd.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtflyqlchr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtwjwbzhgm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtruljrhxn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gteuiytcbs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtipkjlpop.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtmaklxsrd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtsepbnxib.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gthyvvjyvu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtcljnyzpb.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtzjhpakrn.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtdmhrbxcf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtfkztmzzz.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtziywlkrt.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtosizewsh.html

Java: "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtfkspytmi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtijbfbtte.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtsepoqvve.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gtnpejuelz.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtajuzlmdq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtwahigqfu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtagjodprj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtohbpsrga.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtkgjrqqhi.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtvomhabdu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtzghkqgyv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtygnibtdb.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtelnxunlg.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdxiwvpb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtkvtpshqt.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtsxjmsmuf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelwxgltm.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtjwsennqk.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtptraumnz.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gtmitrcnzu.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtaygmnduy.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtylmwqbbh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtssbuxvzt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtdebyqaql.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtjvrsxibe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtfczqhsrb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtmvbntniy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtfouihxzw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtwcdflnhm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtbpigtsdh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtcyczruew.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gtttrexzpu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtxpdiwvhj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtamgryxgn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtmbyqzitg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtkwlwkxyf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtdvwonzye.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtghdswtap.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtutdctsci.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlitqfhmj.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtvxrlvwwb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtenvjjcqb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtxckebxxv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtddfopkqq.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gtedgqanxn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtbewmywhh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gtdicgibji.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtczxsiqsr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtbbzuheur.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gtbbielqup.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtuliguusc.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtborxsreg.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtohmqmicv.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtyryajyzj.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gttmosjeas.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtlbodnyhp.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtdabvzzwy.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtosawnims.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtupfoeqpm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtnnbsdlmd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gthmhrrgre.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtjlifdstv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtajaiyrwn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtehasdxmv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtshbntkoq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtwvjxhbhf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtsunuoyoz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtizntdprt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtnjohbafg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtxqlgeywg.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtafewcmxz.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtqjxjqpjf.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gteaggynga.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtybhhsodx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtyvdauayf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gtlanngsor.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtmnrkwuwf.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtiqlkqidv.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtwbirgjtl.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtdmaukbip.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtizeqnlwf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtxhdzhnoq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtclcyowib.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtngwmothu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtlbebiaxh.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gtublogkiv.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtpzgeffxe.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtimfcjrif.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkocxdog.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtfdefyjhc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gtxsmhbvef.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtdtblceqc.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gttslnvnlz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtrcgnspvc.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtknigktmc.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gtydhvkawq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnikbkbgp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtkqvhmspu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtsbutiagx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtzqnlfdzg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtduyxyoki.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtduozuiqt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gthlvdsyns.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrrdzssp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gtuzmxrrbk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtcatzssuz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtocoykesw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwkfacpgm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtkgsbuxzd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtdaordios.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtdhnfiocn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gttbylnuzl.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gttixsbybk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtkqoldxry.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gtbavoihgr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gttgsgwuly.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtqcntvdhb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtslmjrqam.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtvfuitdka.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtkkxmgohv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtncphddvm.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtrhssvjox.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtdarqytpq.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtllgjates.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtfaxsccck.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtbkvprzza.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtavuixxff.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnflbphb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtuhebipju.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtjzaokpdz.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtoficnuel.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtqiwrbqnd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtldkusmpy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtcbcivxur.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtpmuiyvhn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtniomeqxg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtevwwriah.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtkpkrflyp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtfutjasii.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gtzwojvvwf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtefllwoho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtfywpkscp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtqnynbdmh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtbomdywoi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtwnqknztu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtufitcrdj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtutehavvs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtsrhiyxwu.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtijfmvgyw.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtibtkqdjp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtbcqmjpuz.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtpmxviqgv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtecliltjf.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtvanxwqdy.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gthhctvbjp.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gttyxqhuzf.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtgigqlssk.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gtcfdnnbyv.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gtfcepvwhf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtfiyagokd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtjwuivqyn.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gttajeqikw.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzrsnslhp.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtmczgwqdw.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtijbgqdbg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyflkuxne.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtqvjklcgg.html


<!-- 参考信息 -->