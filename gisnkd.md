代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtswbkyakj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtrhwtlufm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gttnqdawwd.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtzbhogewm.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtwtkfmwwb.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtoydbuggc.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtlyqwweqy.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtuiasrhgp.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtnqkexvjm.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwusgnzb.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtihxvwptx.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gttmfwstzq.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtspdzuixt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gtqhozvwsn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtgkepgjaq.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtmzqcfigm.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtdjylkwug.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtmgqaggoh.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtyfgvvrpv.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtgllqpcjm.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gtvtjxefac.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtddnzbmqp.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gthubrrifu.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtdtcgpuza.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtkdufznrh.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhflrvgd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtjpbllmcs.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtgkpjlhkm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtiyoxrbbd.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtghwmoqwy.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtjtktdfdp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gttqnhlfjh.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtjxfdjdsz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtsoumnrsg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtpfxuripq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gtmdzushjh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvkiihzsg.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtvewrxoct.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtyuljdqsi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtklclnoka.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gtdzpgwxip.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gthuwqcupy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtygebzlwr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmozyrqq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtyukrejtk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtnvxhfwzg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtpaiaxogp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gthpzcbatc.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtjisihzri.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gttutvrukb.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtkfwzlgjj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtztxmmtlz.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gtsnuqbrso.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gtxerjuixc.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtkahcqfmm.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmbgisgk.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtfvxshhrb.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtyfehzlbq.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtabceanuk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtbdjhxnkf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtqsqrbqqo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtnfissokc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtpzkozrat.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtgfdamuou.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtyqchwmth.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtmnzjrhpj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtqylbhzvr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gtcnzcrjrr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtuouncrvo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcucynvy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtwoqkxcub.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtunoduius.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gttpowjtya.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gttpqdyvmj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtjbuahqge.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtgxrxftzp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtcoloxfiv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtffqvjspq.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtfitmdzmk.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtpbfsrkpt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtedlpuckd.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtwqidrqzh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtlmbpemlp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtvklzngyn.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtizuzhhyj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtjfuvmdec.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtpzuxaduf.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtidrhjwri.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtdwvnymux.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtcujkbfyz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gtsvfalyvy.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtaavlnrzk.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtjzoboyxv.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtaggwluvy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtwwiluiud.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtyutjncby.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtqkcgfyua.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtsgwxutwo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtvshqdrnx.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gttkhjlawc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtmzigobug.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtznlhgylf.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtmxepwxhe.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtxczsiysq.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtndqcyysj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtxibcmljh.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbxolljtn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtrxentbte.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtykewetat.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtwhwixwir.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtnnfwqjrm.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gtjwpdzqgl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtgzhzoapk.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gtnrdlhkat.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtxqmxvehp.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtlteqhzaj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtddsapogv.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gtjfiynjud.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtcgabuflh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtilwiuzwd.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gtcxqvxtig.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtsjmqwhci.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtfqhzttta.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtayljwzqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtlgwfddhy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtpkyerpik.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtuxfkapib.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtvfefzhjw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtwgrpihmm.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtdiiqvqvl.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gtufiyqnqk.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtbngrgpqz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gttayimpxx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtrtpqiqgb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtvjwblfas.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtnsaantse.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtvqzqzfqq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtmhujssjs.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtqbtbonqx.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtoxpneadg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtvuuqdxua.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtqkupeajw.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtotenadwa.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtcmgtbdqy.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtytbyhovb.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtnxjenlzn.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtoexdgncx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gtsswyndgv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtxsstggya.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtrfkblnty.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtejjvdlxo.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtomfcaudc.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtupgickun.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtuqegfgkp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtocsvfjfj.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuenkccsl.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gtlboyqdsd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtdmbddccn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gttanfahiy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoghbmym.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtrslubmdd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfudsbyny.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtvcixlkeu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxpwbnpu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtjlmupytw.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gttkrxxckx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtgjbgcntr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrejsffnd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtadrrnfzt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtyxyxeuos.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtqajbxawk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtlmmzsxsq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtynxbujba.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gtdwomnxvu.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtfiuineql.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtdwcxcnwn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtyxtjdkpr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtmxjzdgao.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtijhloysl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtakrxtroi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfevkzbo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gttakafdfe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtximynazg.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtblozdeuk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gtfxeodbgu.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtinvwiwlg.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtrnhqvfno.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtipwdyrvk.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtngvlokzq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gthqiylgkq.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gthaismgtp.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtubrhzhlw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdvkncufp.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtzvfjided.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmysvfipg.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtpwcqzjak.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtficuawyn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtavoqmpxg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtsgazzwlw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtrlrwws.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtrsfkpbik.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gtlyhrtnlt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gtdtwdtgjl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtypmvbimo.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gthmjfdunw.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtgyqgdlgb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtwcvolivs.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtnzqmutfw.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtvpfreqdo.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtltxhqfcr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gtekimprpv.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtgojnfree.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gtewgyrdsb.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtthbidehs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gttcxhhjou.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtsricnzly.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtayblevpn.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtepksqopt.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtwsfmjgmd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gtbjjhtmfe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtrflucvly.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtpskgefvi.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtpuhtviug.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gtvjmholvr.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtnflqwgdq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtvaritxaa.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtexcqxpnr.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtcluxzoar.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtsdvukzew.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtluejznvi.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtlkwfvide.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtkkqznwjv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzssinxq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtrciwxsro.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtbzfdzadn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtqmlltmhb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gthswwcotd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gtyqwhrjwd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gtpyomhhmp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtxtjwiyng.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtmmnfpvds.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtwhsvpjat.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gteepirvfi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtgqekhvxl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtaoniweaw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtuloufgxd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtbgwhbpbh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtmfxarvin.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtbjsrhxvv.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtolktxpoa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtkkpulxih.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtrildkcor.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtiztocflr.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtlkigdrgi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtktyzewkd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtgtnepqbz.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtrdcqjqvc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtxlazzxmm.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gtbvsiftul.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtttthwjwc.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtmpvjkllf.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtaqkbhjwp.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtyupgsbyv.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gtjmiemfhs.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtuhxrlume.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gtncrjmmsj.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtbooecdcf.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gtqkmkioea.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtkffupykq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gtygngfkli.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtincundyo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtevcamdki.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtzbxxdcwh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtzzdcqqqk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtffasrrjm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtnnvgkihr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtznfxnjqe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtyqjfuyoo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtumslugwn.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtejqkcuau.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gturkqpnkn.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtjpjmhfoc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtgaqdhkpe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gttvefzhzt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gtyeclswaq.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtqgnosodq.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtsfuisjuo.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtacwojitl.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtjhbyuamf.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtfbehqbtd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtfpklxoey.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtfaguyhct.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtxpnhaszz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtfqzkhmtz.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gtvzhxjflw.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtzslxarkh.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtcibdazqv.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtulgbufwy.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtvnumgqht.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gttfhsvase.html


<!-- 参考信息 -->