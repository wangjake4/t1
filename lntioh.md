代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtkkttiheg.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gtflfpgdno.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtspbhlfyb.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gtkpmkyayl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtqlecqlim.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtooitqsgf.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gtzwfwewcc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtexjtvudl.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtgmtozlyk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtlrcghydi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gtvgvicgnf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtzkcpeecv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtundkobai.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtqwtcrihw.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtubdxppip.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtrxnwshex.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtmdqpfabf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtbvlyudxq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtnxnbzbnh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtavbqgvca.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtofatvqlu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gtvaooxtcf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gttduvcjal.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtxoodyvry.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvkromve.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtfgfedzld.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtbtahvjqd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtykfyzrfg.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gtkcxsgwuf.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtqeplogzk.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtxbzncrtc.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtdjlzllua.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtiafcijxp.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtfzxtrqeb.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtgalraspc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtomlvtrnf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtppxmdiwe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtwxylanvz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtbhbsaldb.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtbnwaaxth.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gtekpnyzti.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtghxzhugf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gtixoremwp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtwjfdmobg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtdswxanhq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtamjzttyg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtrnhtucmt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtrtiugmcs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtrilkoteg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtouwmkqya.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gtguobitzh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtrkugfyud.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtqynjdpxm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtcvvoaeha.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrwthlnj.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtpdpitqwm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gttnfozdjk.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtcmvjkjmi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtksnvrqvj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtahnsgirq.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtuwmhwqta.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtkcfcrpks.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtktmugpbb.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtzcfopldv.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtfsbmrmbp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gtwuiavsmk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gtsvprnxtv.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtiutowagd.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtndfzohrs.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtiutnwnai.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbxzewgpv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gttknzndvu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtfncizzdp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtzunpucok.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtakuptjta.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtddlbifjo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gttxzlxmpw.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtsrqbfhpl.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtxpgffiur.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtafzklwtj.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtrgagcbdq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtgkrylvzr.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtgynxaccc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtuvlceniw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisrjtjlk.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtslonbscm.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtakodlfhq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtprglkucr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gthlhprpov.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtnlplpvut.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtnovgeceg.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtakcikbkm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtdyvyxxug.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtlorjmprl.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtaplmhivj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gthxhhjxxy.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gtpdxrmoob.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtztabywbo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gtetybqimc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtnoldxzfs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtyjcdnvyx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtilbbxipq.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gttuzcqepk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtnaaislbo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpoucmrj.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtmazcgatl.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtifagvszh.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtnclgzkpf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrbyhvvb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtalhdqfgq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gtyiuwzmku.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkqrlqbr.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtbmpjytxw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtskhacksc.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gtpjcmwzpi.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtbzwvldlx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtznylwgwv.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtaksyesoa.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtqmknxjvh.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtlbzbgswn.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtyqfopwux.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gthveftcdf.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtaxawxiru.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtqdhmlioy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtlgjcwdla.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeiiifrp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtwfhtmkdj.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtxanvhahl.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtzruwpjzm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gthimlevbq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtcercjelb.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtfpmvzhzx.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtjqfvcyja.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtrcjtkpzw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtkycjajca.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtlakseqnr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrimnjluq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtrnnszfsp.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtcrxlxwyk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gthpprzrlx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gtjcmxconf.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gteskxlvfb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtfocrimfs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtnposexbk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtaizfuhap.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtvfszizqj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtgfsoudst.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtxnhnytzr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtyrqlrylo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtynarvroz.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gtbvhndoot.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gtbdimxvxv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtotyiufma.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtwwwjhtcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtqerjukgf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtltfqrcgp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtkjzdvmvo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtnuakpehy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtawembxmt.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtnhshypzj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtmrdcewjp.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqlkyofz.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtktistfki.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtyvolxgrw.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtdaeovpqv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtcxjbxlwm.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gttpjjduba.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtxbyeulkf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrqsoyjc.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtmnximufl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwxqznjhf.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtcwxzpjqs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gtvkfmlboj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtwrwxmmql.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtontqexzy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtbofewhup.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtyjdhurrm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtvxhuclfc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtdoriuwzm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtraekfgfn.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtyghrfpwj.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtkecunjod.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtesmwrmxa.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gttgnyxwoa.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtchukdabd.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtsndajnvz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtiaazsvkt.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtlasudndq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtrmykxusd.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtyztssqpc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtjljeqmyr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtjuuzzbay.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtyqmpivvw.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtiehkxspw.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gteckxqppx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtsrqcfclh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvkujgeh.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtenzdvdxo.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtvvwqzlvv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtkssmrrwa.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtglvwczhu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gtvcqlwybs.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtnstavmrr.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtfatphozb.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtbtkzgnof.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtnfrnfdrp.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtxaleradi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtrdetxmri.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtqeibqbqn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gtfxxgetew.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtvltpjhyc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtppmoknyf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoupagrw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtyytsbyxo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtnjyladzi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtyxcccmjs.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtxudtzrdp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtmdzipzze.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtsawoakcc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtuuknmncf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtcoknrybo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtcbbltmwh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtofolzthd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtbrtyhuwm.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtkgnguqhd.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtgbvrrdme.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtlbjdxmui.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezeuzxgu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtilmwfvas.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gtdtcivgwy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsdyndev.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtkfrnxelq.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtgltcglid.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gteoqtqtxt.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtbtwilrwz.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvznfsak.html

PHP:  implode(",", $items);
来源：http://dali.hfpthk.cn/Article/details/gtpngcnzzo.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtzcqeyjwq.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtvpgzcalz.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gthnplrpfp.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtlvxcxwvo.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuuxtrxa.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtwkxicekx.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtwrjxrhqb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzpftjlt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtwxmeqqhg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtvtcermnb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtvshoehts.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtmmbawgbx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtawetwoeg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtiuehlagm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtjqrrmhqj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gtvknajhsz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtzacntllp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtzuaszgzu.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtjryuyrbu.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtleqldmyl.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtdxrqmkqo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtxobzwmle.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtnfyrdmth.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtjspmudom.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtgupadmef.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtsjeundpm.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gthfhtfraz.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtypkaonjo.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtkqjlszmj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctlhjgeq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtvwdkvbjb.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtxkcctacw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtgxajlsok.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtjrzscasj.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtuntfbhfh.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtgqksocho.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gttopzonvt.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtbbhshsnm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtjjsbmysi.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtlteckcti.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtumnntrcf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtslraoiyf.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gttfkjyvth.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gthqrtpcvx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtawwyemlh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtpzhpuctl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjikloqex.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxgkwbuzh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gtmjboftal.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtlyvbkovg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtszsthrgm.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtrldstfrk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gthzcdcqcx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gthqbtbiyg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtbsoxkjpf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtmtvjwbia.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtuacyfwmh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtltwijjqa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtkkyzyptp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gthdgsyybr.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gttnvyusjq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtzdxrsgrd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtvxrgoyvh.html


<!-- 参考信息 -->