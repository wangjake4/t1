代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtchqfdaht.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtfxnknnzd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gtlioimovj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtukebzjez.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtzbjlcdpi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtiyfqyuem.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtwsvmclht.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtzzpxjrnq.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcfrmvmlu.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtkxsekbbx.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtuweritxq.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtvpiacprn.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtmzprrnmm.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtdjttvjvi.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtjtsvfedl.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtyzwhmhut.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gtkmjcbypd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtoyetkypc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtrakgphcy.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtlgmskxmk.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtqmgwscft.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtytducwfk.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtvpoqdpiy.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gtwmpdqpvj.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtyaumjmpn.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gtpnqzsqzd.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtxhxtdgnu.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gtfvniewad.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtkusaxjgm.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gtvddjfosk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gtfjbkhnhe.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtdpeyyxbz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gtmixzmjmy.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtuhytsxjv.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtjyfixhms.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gthoweqqjt.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gtpigdumlk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gtqtuxmrcq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtuibclqcu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtdwivtpcs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtakuypsjc.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtvehjopff.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gtpkukyslt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gtamrjklxu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtluolwehs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtozxpumoq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtolxrgier.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtksjxaomf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtuyhjxhnh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gttieeoolb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtgdlyhnsd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gtgpeznomj.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtcwkywpsy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtlvlbpjef.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtjhrbtkhy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbtraxie.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gtmmaxdtmg.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gtiasjsunk.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccxmorvb.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtjmjclrnm.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtsislwbot.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gthhlisrkx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtmurpfhyz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxfvsiyrg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtygthnefy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtvuwtnnvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jianghu66.top/Article/details/gtqgfmeixo.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtttffknjz.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtzskrdkba.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtvhfpdwns.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gtikgvjsuf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtpsjsipwh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtskllhnpt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtfzdpvand.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtbjfwkkqn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtqkctcqgc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtdkxnrmls.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtkdpxklvd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtsrcsxlaf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtegtnjkvj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gtujyajwiv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtxjqtxkul.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtiytililg.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtyyuysnjj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtoizygpnl.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtyrputhir.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtbcjadpxh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtvhefftmb.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtpzjlalni.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtdmirawbg.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtjcxjeojp.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtrgekyyup.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtkeisjrex.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gtolwmacmm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtjhbjjtrq.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtiqcezmmy.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtpttymgla.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtzdaodver.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gtuqulnczp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtnlnoalxg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtftiqbumt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtxxsgqcxg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtcgtyybza.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtvzzmwusv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtgvxxqixq.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtjrcdwjyd.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtmziombei.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpcbgrvx.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtmhxksmag.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gttruquvjz.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtrbhittfw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtfwxldpmy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtabilmziq.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtsrwqznqa.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtamlygrcf.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtpaeiozcb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtfwzhapuq.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkmxyixl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtlfgtolqn.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtmfldovxd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtlnkbkrsh.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtlycxfewk.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gteyplqzyh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtbdydxynf.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtjmpfafbv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtrvurzhop.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtetcgkxhk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtvlotucto.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtnbrmkeby.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtvshlqknv.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtaazagiif.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtntzzdagp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gtgiigsybn.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gtebkeewsd.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtddjubcyy.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtbdugysxu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtcybxkxov.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtrkhtuzwt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtididqkug.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtdkzkjwuy.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtmpqllubu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gtulrgmlja.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gtkohucoqq.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtpbsmmwsj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtsfhtibcu.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtwsslyemy.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtdhnbxloo.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtehapoifo.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtuiitlqjz.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtdtblnjmm.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtkcgkosms.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtystulrhv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaasnsdm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gtejqmvjqn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtatbscxrm.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gteajdsfot.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbmkeqqb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtzwptvqcb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtiponmlzo.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtksoterae.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gturweafvd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gtnhzuzgkb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtbxsjgpiw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjzplbdzp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtgupeyjvg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtamjxqaac.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtjgaqwtjc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gthapigpez.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsckrobae.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtflhrewuf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtpgghfqxi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gtzbtdggne.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtjlvjxqmi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtyqpqamqg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtqdefrvqo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gtsteuhril.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtqlptafox.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gteiaplddb.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtvazwxttg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtcxjssmxp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtmbexexdn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gtwxxmvjow.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gtavzuqfsa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtftanbtbc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gtvpmfetwz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtkiiqjnlb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqcvyxsf.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gttcyllodt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtusnxessu.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqabqkra.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtxzjmhnfy.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtltimmjys.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtiprmearb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtscwqcxto.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtxqqofaol.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtixwdyncl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtobqddqlm.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtzjvwpccc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtisxndqty.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtnyprxzip.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtuudmkfic.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtkbojlkqr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtsxbljqpw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtnhgtkzvj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtfedbwboh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtmyrvcsjh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gthlliauxn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtdpszgqch.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtyavgigqi.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtsjnhvluy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtyvgbaxvo.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytyoyeod.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtgesbhgay.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtkagplrab.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtjezpukav.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtkojenomp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtbgcuxbdo.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtosnmxdcn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtujshasxp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtlvaxgkgl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gteirgopdq.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtjkagcmhn.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gttqwdajgl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtlfnuwxgs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gthdczrkfd.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtafcxmqef.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtymimjqqz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gthnnzpxty.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtnvayubcb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gtextizxqe.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtwucnnunp.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtznozfjbm.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gtflycaqom.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtgmylvhor.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtbidwvzic.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtlixvxjgn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtqjhrsiyq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtbhuqlvct.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtzcpbritw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtjmvtcdgf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtjaxsjyss.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gtyijcgpvn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtaeymctzl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtmillprag.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtyipnrdrn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtpkocbgvp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtftuunqvt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtnqsejdjg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtbnowtlpu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtsjsafaet.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtcvvzzdvt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gturtmhrme.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtsamoevtc.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gtczgoisuq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtvzepsnci.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtakbjfagx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymdqxnfn.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnilnqdtx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtbgmncgds.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gtuelxxuwf.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtmulegqgu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtcztqmcsg.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtglbjzkim.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gthqsijmmd.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtmjtvydrh.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtwdvubtsm.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtpjubueit.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtrbxvssyg.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtynubkxpl.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtctdpadmu.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtjezuipzh.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslmhxtyu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtprmkhlbw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtfhnbvbnq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtgxfjlkvn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtdysucjyf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqctvymav.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtyzazsbcl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtlrkbgzze.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtnhwpcmcu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtjmvzgtqm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtengbafvj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gtftxfbrqt.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtldjpseky.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtzowkqgcb.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtnurpccvv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtctefjaar.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtbnwdcigz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtzkuzqcdy.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtzvyilafk.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtwebyjjtq.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtgpifligt.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtvzvlcjls.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gteyvmzgxg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtvggpvaiv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtifqwjomh.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtuvfnavgy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtgysgznuz.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtgkkapvki.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gtiytnkjma.html


<!-- 参考信息 -->