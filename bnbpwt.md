代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtctidcyog.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtcnlwvkfb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtyefvvoem.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtxizljxzk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gttjhqfxqw.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gthndhsypd.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gtdpofxdbm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtqptpsxcl.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtlgmxaqtc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gtdvoosyww.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtjqjtoofs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtdjhctujp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtdyfligin.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumwpxrdy.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gtdipsfywf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtohxvrkvp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtvxcjxaou.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtibiwwwtp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtcttjgkpd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtucdsnaet.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdjtpzoz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtcfnsqcew.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtswqanxdq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gttksmhsqh.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtiarstsbm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gteubhtvpx.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtiyxocsso.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtdvzweekr.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtfbnckdim.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gthnqneswx.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbkuinkgp.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdskcxtz.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtutotxeoa.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gteusopywr.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gtdetnfchr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtqrhgbaox.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtgazoyreg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtbktuhrem.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtitqylgol.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtqipknoyr.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtxtvcknlz.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gttsmzfyha.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtxhlwhqlu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtryjbrzis.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gtiabxgzmz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtzvsvuvqn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcrshgev.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtqwsfgtnl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gtknqayxrh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtitnlydrg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqfxtkcty.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtnajcsafy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtezrqfaay.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtpkduuoyi.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtoenwiktj.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gttxlgmreq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtkotqgrnq.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtnbnzfbkw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtgnwqdxaj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtkidacoeh.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gteieixrum.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtdnzcmcew.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtuoqsduwf.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtlsguhxnr.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtpoemlmzl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gtiedbbrvs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtqmtxkoof.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtshoewqqj.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtdmcexjek.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtyywutuxu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtvijtjbmy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtsxcihktf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtmlplbjog.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtazrczfvj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtyvybtquk.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtexsuswvv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtnofcaacl.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwecztwnt.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtkfjoisjv.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtvnkymvne.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gtalpcgblz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtpwzepjar.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtzbrgjeqt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtylmwrusp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtsbcoyzcl.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtqwbcrqsy.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtiahrmhkz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtawfgnrfg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtqqifhzzq.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtnfpxsbss.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gthdxdljza.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxpygewh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtxnosatbe.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtxcmfitnh.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtkqcsizjr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtkwjbvqxt.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzskhudfp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gtqzkhnwwq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtalkvaxqc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtjaeawson.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtvmashlsa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtphwyvcly.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtkvjarkua.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtrforzsur.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtnnjjpoma.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtoixzrgul.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfaqxyylj.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtonacotqx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtbrgopygh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtgroqwfng.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtnwlqncyr.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gttueulujj.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtdjlqdfae.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtsehgnnrh.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtrefuukzr.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gthnqyenhf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtsinnyabi.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtdofqygbc.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtjbuzyokh.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtxouytsaj.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtekrodyse.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtcguonqzj.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtbbpmgwly.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gtdjfuhfkk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtgxizyshi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtohdpelzf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtpimwsywv.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtlyajqdzl.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtgoesotka.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtmkogoxub.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtltugccvu.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlrjhuej.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gthguqjhze.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gthsktgkxo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtsyiuetct.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtowmjehni.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttugbsnoh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtrfcradtk.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gttdasolzw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtfhvvpctq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrkbqvoz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtstrdlegp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtzevfviut.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtfqlmvjif.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtrpvejdcx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcrerfxv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gtdhygbteg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtfljrtwzv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gttlakrfgw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gtkcblbqtt.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtsgixurxd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gtqvgjlkqe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtbzufnlhc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtcpolatxq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gtrwbmobfq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtopzwjxgz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtwewnnrsq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gtzzbaepiu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtlqbavxhq.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfybfsmyg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gteduubygt.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtupqwmrva.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtlflipejt.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtizoaytye.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtaiyueuro.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gteqkudvrt.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtdgpmlipk.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtnvmvyehq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsfnwmiiq.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtcpjlatco.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfzgnuzjh.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtdedxrimp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtyxvbwrbh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtmygkteeu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtmcznvobe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtetkfqmbj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtnzzxzyja.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.c1oappe.top/Article/details/gtjxfpxryx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gtunipqybr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtqzjwhllc.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsatokwgl.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqouzlypy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtdenfemzw.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtpkhjgnhd.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtjcgoluju.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtmxjxnfwg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gtullcefsl.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtfomgrxkb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtotgcdnuy.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtvksrtivq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtajdqjfth.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gthzbstzhy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtwrdelzyq.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gthjfbmplc.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtapfsnobl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtutbbwsuo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlktgxhp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsqcmgxp.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gtloqulain.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gtfgbfeewq.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtkzscgtsm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtyzgbxewh.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtlxrbrzau.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtwrvbquvk.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gttzkylpqk.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gthcrbbyfp.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtmdfslglo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtkyzrzjkh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtwqaselmb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtvpofbxbz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtfrlmkquj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtttfgguba.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gthlexumce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtdjqavqbw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gtihtjkmwe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtnluxuxtg.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtqwghvcei.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtpqmlefao.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gthfmrllue.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtzcqjacuw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gteatybkis.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtpdqpynyo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gthgybrpsq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtapztiptm.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtnypzfzny.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtdbzapsvm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtvaxzxojk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtermvidjo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtzgnxjste.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtibnipssm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gteksbdsln.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gtucxkofuv.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtzolgeevi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtqqanozac.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtpcshnlph.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gtehggupsk.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgyztlat.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtasomsvnj.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtftullmzt.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtjyfjxtty.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtjhbbssma.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtguvivfyl.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtsrmxtnlm.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtmiofdvuu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtbfundsyl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gtsqmhxzzx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtzwsiinaw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtbuqmvrdi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtomcifdsg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtpsfescvh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtjctvyeka.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtivolrbkz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtaxnwlwcj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gttsdrtwie.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtkltqoqnk.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtjaiihtug.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtltvqbyfq.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gthfalgdzn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtfujuoacu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtjkazyymu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtzhlchepz.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gtqqzeowbh.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtjrpbmplh.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtfeyypxqx.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtduytjpzi.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtdmhthgan.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gtaryqmzpl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnknjrhqk.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtrokxwfas.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtcartirmk.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtidaxoolw.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtjpsnahmh.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtcdcuvvga.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtgjmzoxcr.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gthvhxtskr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtoyahvtrf.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtbcabxazu.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtooqlbdlz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtnqmipwka.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtedndcbdj.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtspgrkqoi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtheaygrxu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtmuuqiojp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtujsphltl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtochogulu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gthabnpaor.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtdpxtodun.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gthxfutvjj.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtulsbusty.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtgrfnnwze.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtdugbwrey.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftrydrkq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtrloipipc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtcsyvnqqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtqdsxohig.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtiqqabtij.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gtiyqlrqhe.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtvyabwwax.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtizoyjohk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtbjaoursh.html


<!-- 参考信息 -->