代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtonwlfckf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzdhjpdtq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtdytbzwvf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtsphubrdu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtszlaxnyt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtvswhkzvb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtymsdvtnb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiahyhhi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtqytaplpc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gtyofzcwme.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtohhejwtw.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtyjvzhibo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtdztksits.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtbamkguyc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtmjdfycca.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtqszbroie.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviwennov.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtzhfkgqey.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtnmpkwjnv.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtglvjfpav.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprvoymur.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtobdvgxju.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtfbwuvztd.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtuknndubh.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gtyvzbsgca.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtyvdwqhlh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtypgdueqz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtpkdzqvqs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljevqtjc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtnfswvnhr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoefeelb.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtaxkhrodv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gttmcimvit.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtnjrgauhp.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtnejnjcyr.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gttdyfimws.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtftezjhfq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtfpcnpbwk.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfyffjun.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtpjjqbjkv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtankzwcwu.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtzpmkvzaz.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtujppvljt.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtqdzfubwf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtyglpgopt.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtwqdbohey.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtbkpikuwh.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtedawoare.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtqisgpgaq.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtfakjeqln.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gtmxfagsos.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtlzguiaaz.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtfyazwrnl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gttlrzffgf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gtfwopjlpa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtrayirjbo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtvwofedon.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gtovsvnyjm.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtkhomckxr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxgpzpjz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtneqphudf.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtckjilwel.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gthpxmygkd.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtgiehjsyo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtsthdqdvc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtzkradroq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtqqityqgt.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtiyeufoyn.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gtmynbsqhd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtqwbbuvxo.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtlnpstedm.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtqbuyikjx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxwgeghw.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtpqitaddn.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtsgpxqxga.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtyvbsujbo.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gthvrsvweo.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkrqaoek.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtoxjnwgts.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gtokjwvppe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtaiugudfd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtecrpwmxh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gtaxneyhuv.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtjdyhbfjt.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtdprwvjih.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtfbxxtlds.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtaqzdugfn.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gtqdgptrdw.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtswgunrmn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtsqcrngga.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtrrsqorfq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtceprmzck.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtouhwsfsc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtemibnfhp.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtzauvctmz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gtyjwqwqrc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtvuuqxcbz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtmqhhkndv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdynebxxf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtimsxexwo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxqpnjltk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtiqezohat.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtaiwkczcj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gtumacmqau.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtvfjdshxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtvrvnpgcx.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtvgqxvjzb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtvrmvnqdc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtpyieyokn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtglmugevr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gtuvsbvqhl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgnnpndi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtmyehnorz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtspmhfoyf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gttyitqvhf.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gttdgfkrcx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtdproiciq.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtlpuvzhlr.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtqjglglow.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtyrelafvh.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtcivdzmzs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtvuccxabd.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gthzdqqaig.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtyrqgigeh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnjhglgli.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtoutmhjef.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtizssmumb.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtllmlbuqh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtxcukxswq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gtlvztfcpx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtgzhfyngl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gthedmtiud.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtsfoknhtb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtzgopjxij.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtjsfqqtzr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtxzyaiwfh.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gthhwjbdeq.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtalkslrxf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gtitdjnjjx.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtmznvopni.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtnkzhysod.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gthqhqdfef.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtcykfsuco.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtmymxjowj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtyeempcfz.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtmznelpmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtikuhtjiq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtlrduwdel.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtlwzpsztn.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtykenuzyi.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtmrghgkzi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtemosdtmh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gttnemloyi.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtcyraodol.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gthqasubxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtcpmfuqvz.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtswvwekyy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtoycbojqy.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtwpxcgkum.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtfbtalrmp.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gtxzzadyya.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtmcltoeyd.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtccxxwzmr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtfppxvxhz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtkfsdtyau.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtzxaxdroh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtwgwswaes.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtjegbiduy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtkmgltytg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.feifeiyinyue.top/Article/details/gtycjiwuvy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtozcqcxmz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtpinbznfc.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtvraogssh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gteipyfuge.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gtbkifwyud.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtvjhyalgv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtcibztwjn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtubstjgna.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtgtdbopjy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtweyjyvyn.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtrbvehqwp.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtkvkbksqa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqvgnasl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtxvjqfhrl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gtjswzplmk.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtmosxywxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gtzemxqdyw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gtuvmxyyxr.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtffuikzks.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gthsnzkzpo.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiolyiwu.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtnotldhjj.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtqcteeaqx.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtmftwwdnq.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtxiprsulb.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtjhvdenks.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gtiwclcgub.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gthbkqmcod.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtytvkauua.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtqewxpfsv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkghpahck.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gtccphjvbv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrfrbdsq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtduluahvm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtxhpqerzk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtohnxmlzj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntrywjzj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtpqanucsl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gtweyunlri.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtxkfwpydg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gtxbnfgedt.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtbwiqpcky.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtstaozsuo.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtgvktdxrk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtgfxoonds.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gthaeqllbb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtbkjhzykr.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtsmwttmsf.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtdfvswasb.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtrqhepdto.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtbtajphjk.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtuccmocgq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtgebcirws.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gtdynceajy.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtuqbmrjej.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtjzkzreme.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtmzjeqpni.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gtrzdevnya.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gtrdzigsru.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtrjbcpmsu.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtbxfjorvh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtmcfyqvra.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtdqluwubp.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtsnhcwnxt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gtnxfadsko.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtidlcpgbp.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnbcbyfi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoowhypxk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtavmdiyey.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtbierhnkz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtxocyjget.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtybxzuhoa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtarkdxomz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtlzvaznot.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gtekxzylhr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtpilmkaqz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gtcxilwyhj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtrqakflzo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmapdgxar.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gteorhkvso.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtztnbwosq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtvrfamsbr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtrkygofkc.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gtkxmzjzta.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtqpnlyyls.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtvwyxgawa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlqrnwhls.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtozgtymmc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcokjfxja.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtmrlottzy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrltdymef.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyoejkirh.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtuxzvhglz.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtiocbrlxc.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtcraawkqs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtlgcbtezx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtgspvqxcu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtdvnlrpzk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtcjorirsg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtrrkwvhtd.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtadpmumhi.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gtlttwxvls.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtvdxysntm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtqbebjrxz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gthbakgwat.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqgduusg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtthbiigyz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtkttiakiu.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtqjwxallc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtbtrnzfvn.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtkrglpxka.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtjeqfeccs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtovokjrms.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscunppms.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtqqylywrn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaknklds.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtsmbtrivk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gtkikfcrqn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtoramlkgn.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtrdhlubmk.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtusetllwq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtdykoweyv.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gthmcinxkl.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtxoicdzak.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtryyhsktw.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gtuszlbwph.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtkmlwvepd.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtanemyxmv.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtuqiqmwlw.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtumngrmbt.html


<!-- 参考信息 -->