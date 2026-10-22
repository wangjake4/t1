代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtzzrhwviq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtrotfoavu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtkqkwduse.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtmslehigz.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtrmjjgcoz.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtbnozcdpz.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtvatmkobs.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtamzybybv.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gtdowrnnhy.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtyrnsijol.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtswkvvjln.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtnpoqtvgx.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtkealqflz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtquubowgo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtrogpzhsh.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtajiavknh.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtpgottcwn.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtcgihouts.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtjvwujcjd.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtqdmbbbfc.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgniidsaa.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtsdzbzbhi.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgfnputy.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyphbrkdb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gtpskorcxj.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtmsqomdvz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtozlilift.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtmjbbfwot.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtrvujytoj.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gteymmfcby.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gtuwvwsvvd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtyytgjjyy.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gtfkpfgmrl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtqcrzavha.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtefjeoywc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtnnzeelwm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gttymwbqvz.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtzvcerlwr.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtytpjkbdo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gtdmmilgfi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtjrnojvyn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtgvsfbuee.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtulwbcfps.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtgizinifs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtvsqifibu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxugrkkv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtdxxgjppi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtrpermrqz.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gtaykcdjjt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtsmnjyudn.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtlkqkryru.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtvrykymfq.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtrcfjgsrb.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gtcvvocotc.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtkixwtrar.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gtvfsnzphh.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtjlusfgdk.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtfjrljdzf.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtijgbxmuz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtanoumcxi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazwcgzky.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtopkjqxun.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtlfjoxaer.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtkvtovmrh.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtgwvvrmmm.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gteoksezdb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtogcmzsfi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtxsbudjjo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gttyrukfpv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtqcedvjpv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndluwlrj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtakrsinaj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtzcteduhk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtvlnjciha.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtmfbfykes.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gtbarecast.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtzlssxmfy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtzpypmvag.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtapldcczi.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtmgofccqy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gthfbxirzo.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtkbyqgafo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtlceufknn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtsrpdxhgt.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtfyqrjrop.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtzmyizavl.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtyakwyicz.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtgjobdmdl.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtqvsjpmwb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtonurekte.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtjhudmuvk.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gtknzwchwc.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gteqfepach.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtfihjjftz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gttilskijh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtldkkhyjv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtcfjovrow.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtsagwtnws.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtytjqbxqy.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gtryfszfuz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtiimcmiao.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtelczqgsk.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gthejeksoz.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegnyjilc.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gttjtvxwxc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthvloqpav.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtrolfolzu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtmtksvzhe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtvnjzqqlk.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiipencax.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtsxqvtcnr.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtgkdhkwlk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gtnpexwgcd.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gtmxnhafqx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtjgwoetlh.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtkmomljop.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtbujmnwzc.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gthidxbfko.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gteccykkwy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtycvejlsf.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtqrjtyxev.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtwowytdun.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtluecdfrm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtxebbupxm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtvzrbqjrm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtbuznoghv.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gttmyvyatm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtspjdieus.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtqywphybp.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtogjnydkh.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtlqwzpejc.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtrwedkqjq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtvlonfcwy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtqxkzgvyb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtrbgfcqyb.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gttkrsksdm.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtwkzugidm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtffvsdkkt.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpneflcui.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtndxxwfid.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtgcojazzy.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gthbgeflpf.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtbsecsuom.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gtlbzkoolf.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtduwqytrp.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtneaagmwd.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtvqdpyfma.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtocrafnwf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gthtojwabu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtxzluyzed.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtopcshkny.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtnhbyphhh.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gthvsdbgly.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtyvnhyjvv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtzvuqqtja.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtdmxjjqil.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtsbnirgxr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtsdtliliy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyziuvcm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gttbnwlodu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtignwlifd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtrrshcodk.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtrjpucrzn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gtkdactbch.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtwqwdwddv.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtbygxwgag.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtcmdyygiy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtnwwhgezi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gttncwvsio.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtqayfpolg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gtlwuyoslt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gttaimhunt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtriahfnob.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gtfgaedmcv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtiwqlukdi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gttavzeobv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtchhnvwbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtbwmzosfk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gtrafbzyzt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtflnfcrvx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gtmesatqex.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gthhajtxev.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrmcyugae.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczszifdc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtkjhcehor.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gttmandlbw.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gttpuvhzhe.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtjoovnvoy.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtofgjspec.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtoknsosjh.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtrexrzpho.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gttgkgesmt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjnghxfku.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmllxlbn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpxbmkzml.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gtppyyayvn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtpoqxwmnc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtdsngnozo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtdsczdpij.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtiwqhmgol.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtlyrvhaqt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtxfbughvi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtrqfqblht.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtolbigpfa.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtgjpjtbpn.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtzjmbmjwe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gthqbjudom.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtprdwslyb.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtrcpnrvil.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtxogaeqyu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gthihrmabe.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtyhhbumuo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtrhmoavdl.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtbtjptfbj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtochvyoll.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtoevxcwcg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtakgpgkwp.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtdgawreyf.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gttmsafrer.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtljckmmkk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtsgtporrh.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtxnzodekj.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeblrplm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtmztzhhxn.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtiqjwefeo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gthqphdqse.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtdkfdbdgb.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtibalfrux.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtgeezgeos.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtlsmrcsug.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtjeautshj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtnmqyigyi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gtqizrgkyn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtlrqhkset.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtquwquoit.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtgfclbjrq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtqfewetdo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtkhrtvdum.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gttgvcrlad.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtvmsvwyqj.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtwupmzfex.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtspqvibod.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtxkodyryo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtvtlmqukj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtpcglrdzl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtakqxjvnp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrsjodbjj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtnavzyjqy.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtiqqqdatz.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtvygkmnzg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gtujvevupq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtbnktftmx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtusvyhxcs.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtvldsfusd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gttqsomlry.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtbdnfszho.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtmbmdfgws.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtiygivocm.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtfkduatcd.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtrfihgbcl.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtoikjvyxm.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtvawvpmog.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtilxqzbey.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtbiuuvdgc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtaqbtogny.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtjadgkocn.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtwprwryou.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gthrbmybtq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtgfdlbhgm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtwvcpcxqp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtknvxkmmq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtywdohmtl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtgfskgirr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtttqobjkt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtvmwaxbpo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtqojqkxuc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtzcvlzpwq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtxymuorim.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gtjoucosma.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtatjngess.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtnqxzcaif.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtsionciws.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqszvcom.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtrvxcxxiy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtkdwmyxra.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtwdootsrw.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtheedoqgf.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtdmayseoq.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtxclaeheu.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnyylpdl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtxhvkpshp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtkfvpvoby.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtyhliydhi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtsnfrpcyz.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gtpbgiumfx.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtjnalannd.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtazdoqvdv.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtcomuocop.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnprbqne.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtolkamrhn.html


<!-- 参考信息 -->