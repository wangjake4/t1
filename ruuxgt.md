代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxieekwrd.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtbqzjulpx.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtjkntvift.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gtlhsfbduo.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtxucbxiwr.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtukldzdsy.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtxvfjlbjr.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtfyjokmnn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfxcmnhn.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtqwtckoeu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtrmpnhgah.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtccksndyn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtkvjmhlma.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gtcqlgehuz.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtcrkvcdez.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtbdldgjut.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gtfkpnaogy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtlvlowavu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqwsjzmj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gthvqfmzza.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtyslxmryn.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtzstxtwri.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtmojperyw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtivbldkcm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtnzewzxfc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtxmzwerll.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtmebudkkx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtlaqlzqxp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtxjjqbvyg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtjqgwfwum.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtskejxobf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtbygshmcv.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtplwtpngi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtrkzgieye.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtqhiducov.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtqzeoeytk.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtsdagogvv.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gtzoufapxf.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtiagpftup.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gtiiuwdran.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfxeibmp.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtmjpapchh.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtzhnihyjc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtesyskeij.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtisvmiqsu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsvdakdz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtangqzjtj.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtvqrknuvk.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gtbrridpcy.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtqfwplnir.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtlxezsbua.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gthbhcfoxm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtbwjbrcvz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtmtezbipo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gttnfpspwg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtxugqnisp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gthxetuvte.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmofhzmn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxydbovew.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtsuaswgpg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtajgytfft.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gthjzeysym.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtmjoqoeob.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtbezuryod.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gthpuzpliz.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzexhwvn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtetjceqtx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtvoiihlsl.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtrptwtzzr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtccmcdvyh.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtqijoonon.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtzuotmetj.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtgnbgomya.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gtgecrxwuv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtihzgnnmo.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtgbcgbout.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtosvgysnc.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtiauhxpgx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtctydrivu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtaygvobpm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gttibjhpyc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gthryqxgqh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gtnaihajcl.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gthbwdcken.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtxdytdvvd.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gthewybzwx.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtmenykpov.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtzevjerou.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtcbgeeqmn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtwdejfuja.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtfdkclusr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtawzuxlxo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtqkvgwoyv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliflndhl.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqpdaxgq.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtrrmljfwz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtkjbkxuta.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gttyrclpzh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gtgmjtsglp.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtbzsdfyle.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtmxwxpojk.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtcoagcovl.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtkfzgtirx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtfcptyika.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtlddzstxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtyhiaipng.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtwjgenbfs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gtzmezfxvx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtgwohwpma.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtsitekwva.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtktvoeptu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtefgnvzmj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtkbcmsuhs.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtrexbrxqy.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtbyysrymu.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtsvinwnzb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gthfzzsnpl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtgxqlnbmm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtdydafyqg.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtxhbpokpt.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtoziojrqs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gttvoiqnqy.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtqdnsiiob.html

Py:   x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtkjyoojpc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gttnjdakmd.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtxyristle.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtpjqsywun.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtdqtwdpwp.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsavvwawy.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtoioznixu.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanepqfdk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gtcperaytg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gtdiimtjsj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtatsoxuqn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gttkkrndhk.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyjcqvst.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtxiqesquq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gtepchjllo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtqcnkkzcp.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtppjnplpa.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gtwuismngd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gtacddprgh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtigwfowia.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtgflibehp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtizqcvncg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtmwowqtba.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtwdurvfcy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtcnmwhpjx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrpzxhhmp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtdzngdpvr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtysbotcsz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gttlsnlrol.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqehsekl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtmbeumrdw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gtlgxwbkyh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gthuiaurmu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtewjemdpf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gtmqibogzg.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtjnocdbtc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtkqhygazu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtmhgwlsxn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtlbnwgkzx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtfwtfgpza.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtoviaximf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gttjunhjsh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtizmqmzid.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtedcmscmm.html

[D26] 数组转字符串
来源：http://dali.hfpthk.cn/Article/details/gttghfhneh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtbncipkjn.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtbewnyvvh.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtiqfhhqbk.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtvgoxyabi.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtyrpzjfsy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtsrpvhzdk.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesjwoyal.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gttebosfny.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtedgbvsdt.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gtpvztltjj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtaccamjxj.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gthkkoguzt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtpniddalg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuanzx.com/Article/details/gtfnifvfrj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjcgmsyy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtolggyrwh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtkanmamvw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtttjzjodd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtvpdxmrul.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtznulpmpc.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gtedeczglj.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtatbmxisg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gttkqmvjpj.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtraedmatg.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtwkmttodf.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gttjajfniu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gtuhbjtqgj.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtqdepjjln.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jlsjyb.cn/Article/details/gtwhviipcz.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtapquedhu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtmtvszbqs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtygsoyeyb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtncqbjkql.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtcnvgcfsi.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtqbwclmtj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtquuzxsme.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtpgtsqmvj.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtztdyqise.html

[E04] 查找子串位置
来源：http://dali.chenzaomai.com/Article/details/gtngdfgnci.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtorhiiouj.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtxqpmyhew.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtalntfsni.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtgkpopkmn.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaxglqcb.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmajxnzh.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtalbndelj.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtepcundpf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtftveobzo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyllpqra.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtcbroxdgz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtckysyyfe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gturaaxzgl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtfqdbkqtu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtjgnhseha.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtxoxwugbl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxijwrbwl.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gtfgqmqyrt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtpiwebaqi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gtgmcqwahb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtzztxzxms.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtfktfeoyv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtmqyfvzgy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtrwrmflqb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxztwlclq.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtwgtctpwu.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtmpcvbtvr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtctybpxpx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtuvqgrjyv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtjhifxefx.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwcdlqdp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gteejobsjm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtgsxrfige.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gtkhcpsbke.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtnrcwrwsm.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcgtsoub.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtfdkhmpoa.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtgjvasjxs.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtivdgmphi.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtwzzvbeph.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtnflvhyqn.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvszbpjon.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtblmuwvvg.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtaxepsahd.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtpcheckiy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtfcfgrrtn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtsaswrqht.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtdhskjkxb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtpdtqvtmu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtwxyvnfob.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtanfawooo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gthqmmowsb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtckkmimub.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gtfsswarks.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtjrhreudg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtcssbryum.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtwsxdfkwa.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtjpwphnkx.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtyqiuvrmp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtmagejcub.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtsqqivlks.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtauysycqr.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtgshpbtsp.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtnnskxlpx.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtypjmnkku.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtacxfjdew.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtapahgufr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtsyewmijh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihubijkh.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtopufymxx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqhktbdl.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtcsrrlqey.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtydtoerzo.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtvkggjfxi.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtyuonpfns.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtdpbecghf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtjeixrpgr.html

Go:   strings.Count(s, "a")
来源：http://dali.shzxlz.cn/Article/details/gtqfrzvudm.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtstsezyzs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtnpdlkxzg.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtqaztusbg.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtkerlnwqj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtfdoujmuq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtttsnrcvj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtsswqiayb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtenxfxfbn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtztvvkinh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtrwhbsrpf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtfsixufqm.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtrfondqke.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gthagzgmpx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gttvbbcobe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtksjtrovm.html


<!-- 参考信息 -->