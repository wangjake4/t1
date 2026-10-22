代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtymxwnxvy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtuqxobvpl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtamjxfcue.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtsicexdtn.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtigblvhrm.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwiziolk.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtrjwvfney.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtuuwweglh.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtmakhfvlo.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gthwxcyaza.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gtlhgzgyxk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gtmgrwgckd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticuccjfd.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gtexadlkpf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtieirfrxx.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtxupuucxc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtpdrvpbtz.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtuoeszvgr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtfsivwkdy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtgubyhuzd.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gtoqyiodzb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtuvrrlqfn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtklimhfks.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtvhuabmfu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtcoesryyk.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjyzueuf.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtmtlvrots.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtmxldrfvx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtubrozdfd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmadlocm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsihrkyxk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtcoboytcz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtvjbyxrah.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gtnicemskx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtxnoabgvo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtndjsogui.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtowsreffh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtvmeettuw.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtygqtnqjc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtwxpeuuyf.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtyymznkts.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtjzrkgtdt.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtogohrnpw.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtvivjvsvq.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtyptdoovk.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtltacnjrw.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtzhcegybu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtwjbkytow.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtpumjmzda.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttkdpngh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtewdhhdjp.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtccrxdaqz.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtyriibahk.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtifoxjjmy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtoyudnlgm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtuitvyfgn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtwhfihcit.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtggkfigxm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtojrurxxc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtnvsoxwzj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtjufiyqvw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gtxtdhbhij.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gthywaxiuy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtnrlntbtw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gttubldqho.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtcxeoknki.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtjhtrhojo.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtbuxnvdtf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkytzdccv.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gttjzifyko.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gttwisylyt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtowkdtaaj.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtlueomzce.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtawexlucq.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gticcxghrs.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtarsbslzu.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtabnawlge.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtnqsnvtkx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtekjyzvbo.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtyflodznq.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtjkgzrbpw.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtwgeehqif.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtbwjanuvb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtzvuufecr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznpjvifo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtiljvwcxs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtgyynjtph.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtzkxytzvd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtbqnbtgul.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gtfcmndime.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtczswchcm.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtrggvktzz.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtxcsisvbj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtknwlioer.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtfjbaasms.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtakmysljl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtowyveyoz.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtcfwygdci.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtmkcuubib.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtrliuayer.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtvunermtw.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtmpvzclrl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtorgffcyl.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtlxwcness.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtpnuopnqa.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtjvlelcje.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtjphvpgle.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtiflkjxyz.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtuemvxxud.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtsfkdtaat.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtgmanqbmk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtfqqissfu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gttosfbpxp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gttcqrykqk.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtkkdpsbhe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gtexhulioo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtdddstexa.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtmjeuyxjv.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkrszrjgd.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtrbvtohom.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtskfnflcn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gteasyrswm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgijnedq.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtdbfrgyet.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtfefqlmbc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gttakgpffv.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtdtnmfuhl.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtyijaryor.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtfnlrzpjc.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtwrtbwkes.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gthrabjgdy.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtfsrfydgb.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtdazbutil.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gtjoxgmkzp.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtazajrvqz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gtdzxjuilw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtqaimqxjx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtrahphwir.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gttwmxblvk.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtzsoamxme.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtwfksfxbh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtprluuqon.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtiisqccbo.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtnqabpwwe.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtoooojtpj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtzziqsbmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtvgxfvnqc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiduycmm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtkcoxfzxr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gtuqkzgdqw.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtfujrzjzx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtuhfknniz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtngemskns.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtihxgzwle.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtuelgzeww.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gtmgxggavu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtntnmbyvu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gttzrvpaae.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtmufreivq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gtiodpomyc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gtlgmejokl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtedwfxhen.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbmwaudx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtbdimsorn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gtnuohbosf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtxkidfpkr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gtfurkqoig.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtshuebaxt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtfebanlvr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtuakvkcfp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcryvcvhh.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtotzkwjks.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gttfjcbbiz.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtzsmsvcgg.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gttlddpgda.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtryrdhpjy.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtwpupwzed.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtlaiufklg.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtaeaztleb.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtzhgjyzfd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgfbmwsjz.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gteiubauuq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjphhxkgw.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtdokjpenw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtetwbrcbf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gteujodtqj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gthbaabgne.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtesnnqaqd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtxwcnzqhx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gthmfnzofd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gtnimagelj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtwuzjpjwi.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtiekbwwsd.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtzzexskdi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtticibapj.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtdphilaqu.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtveoqdmww.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtvoxvbzsc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gteidfzirm.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzoelryf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtcjmcflhw.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gttfzuabsh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtwuzmgpkx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtfmajbhxp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gttcoodiwm.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtgtmmsywd.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtygwtvhvk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtnsvnoihs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtzuupmkyq.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtvvixxxbn.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gthiojtsmc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gttbbrytnm.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtotpksurb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gttvkqwjfl.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtcufrjbpy.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtutsdsibd.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtrfvzzoxh.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtuxyaaptf.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtuczwenun.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fzhhl.top/Article/details/gtpxnjkxpg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtpficsnfs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gttnicdkmy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gttghhqsvh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gtnxtcdrfi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gteoewpzwv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtbgbssytb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gtqfjszgnx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtkveggezd.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtloaherxh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gthzeurvcu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtzfoeydmt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtynkfxrtn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtcddjsgrf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtauljvaux.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtickxrvzn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtrvutihrq.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtddqqjpbl.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtczaklcdm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtbssrdusr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtdldezuam.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtetjxzknn.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtuzqbxpfp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gtsyheyvaz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtgawkktoa.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gtywihcyee.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gtqpffkkyt.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtzcrueghc.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtxopyonyz.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtqpjxmmfg.html

JS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtttmljobe.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtdavjrwdq.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtggxshnon.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gtlrtovjgn.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtziwezzvt.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtwemudlzr.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtqdbmbuub.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtxfpgxczy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gthwmvuglt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtmxnkrbru.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtjsxplwfy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtvsqlcdni.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzzvhdil.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gtlwjsafyj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtpqwndehc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gttsjyjkvk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gttvaavdbu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gticxpdwwb.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtexostpjx.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gttalcwzlj.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtdkmldkjg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtrvhhkwxt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtisjfjloz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmropiqp.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtrfsateko.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtucozzbmc.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtklzpjnoc.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtsroowqxe.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtudwmaktv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtnmjlsogw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtymopmhzb.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtocddforf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtfzpqzdqg.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtmogfvcdd.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gttujwostc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtzxhqgcny.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtrvnwcbgn.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtzpzfzlft.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtqlotvcrq.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtzlfbjeku.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtlxwvythw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtugvryzcc.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtnszvnyaf.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtesfjxzes.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmqqlefog.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtvdhljncs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtblstviuc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtglyjbike.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtnknekdry.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtllpsmeey.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtogaadaoi.html


<!-- 参考信息 -->