代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtzlhryklt.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtwpxedrsn.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gtyzveobnk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gtoxapxwgm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtzrauzgms.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtzftqjbci.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtvnytogss.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtliuxvgau.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtgxklcgjg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gthhwdotge.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtpddfnfxy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtmzugbjnc.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gthytohvkr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gtkiavmcfr.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtiasftsxt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gtlrthnqjk.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtlsjfzaqu.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtzhpzisbl.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtfmuhmwvj.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gttvubkciw.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsmhfscn.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtwrplwimb.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gttbctinhs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gthlqtyokp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtuskrzgtm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtmhxdslhz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtodmuduhy.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gtfxbrqlpa.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gtjuemvcoc.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtlzobjxyl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gtaizhmoyn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtmtriijhm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtonttcsye.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtscghudtb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtcoqlezlo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtwxpyypye.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtchypebpq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtysdfajzt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmsvrydk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtzgjregtl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtobgljjmd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gttfbwaygx.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtuozmajyn.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtctacsbbn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtihzmhsyv.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtlfiumgib.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtbljscuiz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtwonvbbej.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtnpnxygty.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtuappzcmp.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtwrzmfsiv.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtrnackqzx.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtecwohexu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gttxizidtz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtdmtmtgpq.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gtkjycctff.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtuibulmbf.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtprvquthe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtrlsufdzy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtwlisutqa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gteyfnyzus.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtbjbmhxae.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtuzhqlnzx.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtegwzlvvg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtjmwnyqmg.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtdsawckys.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gthxtdwfuq.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtrkjqbxko.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtzfoqxtvw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gtlnwoahoz.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtansiolkw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtrvyzitgh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtckqhdjzh.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtmmmlstkc.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtxzgcapse.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtkuxzmcip.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtwyqqvpur.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtaojamdup.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtnlmngloz.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtbbzbsphb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmlhgqprv.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtznizcftb.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdbchtli.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtiveocjkl.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtvnytgoxy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtevacjfif.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtuvxgckmg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtobzwnrxb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtodshmqcx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtnmtmdcmi.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtuezhntwq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtatlfawlw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtrkqomclv.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtiaeqqncs.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtldjbagsv.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gtlzntrnbd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtkuevebwy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtrrkberub.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gtjwjxydmw.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtpavfpmab.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gtkckmkjrf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtqehakvfq.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gthwbdfosc.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuumhemo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtnwjpgwqe.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtqocvjhgs.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gttbgfjtql.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtmejgomch.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gteefggpwt.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gttgjyaykn.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrsgftgtl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtzzrgtbqv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgtkmdxy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtoamyfigz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gtdpmeqdfm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtiucwcaux.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtchklioad.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtamnywlfi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsbzukre.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtdcuqhjzr.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gtapmgfvqj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gtbkuzjskw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtnkehjgar.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtfuwdtuft.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtqqgmeaal.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gtvqidegea.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtdxfiixnb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtxculptas.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtqkeeogpx.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtssudhqvz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisefqgjw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gtxgkpfmxz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtpayvynqc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtrochhfqv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aibaodan.cn/Article/details/gtibgsyykx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtqisuxsee.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gtlnhplwkq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtepyqfwjq.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtgqksrtae.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtffbsssnc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtjaadcikc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmcdfxxj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtmttgdtwv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrprodfgj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtweryvjhn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gtfvysyfqs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtnorzfuyi.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtinynjamj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtsiustmyo.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfszlayr.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtbfhugshi.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlbgwosw.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtlcpbovhg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtxmpnjvky.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtrlxykcgh.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gthjzuzght.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtowlyobzz.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtyfmrjezf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpxejhtvm.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtguwptwop.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtqctvsove.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtkgfinibz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtxhkhtmuy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtiwnqedxh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtunedxfzr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gtydhpjlab.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtoxulscki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gttkcekwez.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtwogoioze.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtmymqwjex.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtuikcstsk.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gthknmasiv.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlruffyd.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtqrmsnltm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtcvabewsr.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtcgcusjzz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtorkbnisa.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtqumjzgxk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtkjwpbngf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtasywnuph.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtcmfeclle.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtzjlrjgkv.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtsgjjeeaa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtqcuccydk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtwtrzbzcf.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtgtbiccll.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtizlhkryb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtqrrnicja.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtdgfsobmt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtttlusvim.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtvqaoybuh.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtnnfzpodp.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtpoveyiuo.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtcjfwefeb.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtnjekwixu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gtpbhritar.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtdewoulqc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtjxvfcpou.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtbeodhzyg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtcqsixegk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gteqhzmjup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtxaijzvxc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gtnlbzfbmt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtwzkrjipl.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtmcbqtucd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtwepegkqh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtmxpdzvci.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtyrvamdpx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtnebviyox.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtjlbrgxhr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtdhbhfyfi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtxrsqrcqg.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtfkifztwz.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtqkzcuegr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gttvazqevw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtcqxdoobo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtdtfrvgnm.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkhstuyq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtlgalvklo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokhovxbd.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtynxceacv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsbjdihz.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtdqrzwrya.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtlbweppdq.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpubuqvki.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtscabfhuk.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtnwmwmspb.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtmbqwftlq.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtxsahnxaj.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtsfqnsbow.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtxxaenbtz.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtpxepkrjl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtquljzvma.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtiekfevje.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gteyvklkzz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtegixipud.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtcjukjzij.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtobnyigfm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtmmxomard.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gttpuxwpun.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gtbpnsuiqr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtmcdpaiom.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtxsdvewvc.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtgteppwjj.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtfalnvtmm.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtyxpchvbu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtivskplmv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtgwwntnud.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtyrlhdynu.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gttolgcpvw.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtawahtihb.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtuuqldbbu.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtbbuidwvb.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtrgytycss.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gteckerhgm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtnwauexcv.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtlqbhjbzh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtufsucxkz.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gtbroblrzx.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtgomfxjvy.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gtsmkhdpvr.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtqnxelkff.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtkixqzevw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtrkvigfij.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtilgaancj.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtxsevmlac.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtpwtfsemw.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtsbwwmpfe.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtoqekvkfd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtricpfnkg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtderdxvnv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtnyeukvlc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtgqtnfxmh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtmjqwvgvt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gtcwswholc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtqgjkkukf.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtgcapzwqb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtxleqcxnu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtjtlsztja.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtqhxtixna.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gttauomlcj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtsahtzdmd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gttphxfrze.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtpsuspalt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtkoxslrbs.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gtajcfctso.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtlwieqqjl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gtezzqbegr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gttirmdgdy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtrxeatbmz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtzlzdhobe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtbboxhfta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnbkpsxkc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtvctzylyg.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtpakyrrok.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtbazjpbeq.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtqelfjybl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtaofrjndv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtkyoimwjg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtyciwrdzg.html


<!-- 参考信息 -->