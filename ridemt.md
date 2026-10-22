代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gtorjafmed.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gtirndrkmb.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtbtejdfcl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gthtyqdbwc.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtxxhqlpbx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjodolsqo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtlbgbrkoy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gtcljmpnje.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtjdykvzpv.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtappkallp.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtibzeexcx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtnvhbgopf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtdvnfmsxm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtapxhgszg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtdvvhojmj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzlrrdpk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtjuewhpfp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtxuulvznc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtytefmxvz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtrdxcopnl.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtaswpdodz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gtdqngipzi.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtqytelcdo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gtznxbpojb.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gtaulaqlmr.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtsdxceybx.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtpmrzocif.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtmdcgntol.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtntbwginq.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gtiritaajr.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtjshormrt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtqusteoid.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtdwdkrlck.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtjgcbhvzn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtkncaskkj.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtovbifina.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtfdhsnwtr.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gtvodkfzup.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtrxrvgdjm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtdolaxaip.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtztttwveb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtrpssepbm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gttqscreom.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gthjsxfhsz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtxkwthgsx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtvuccnyog.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtlqvvrqmp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gtlyeizuny.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtzncmrgwn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtgbiqegli.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtoyssiuoi.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtzfjklhex.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtbbjpctov.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtqnwpsxto.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtzaayngpf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtjlwxccwi.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtffvvdvod.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtaayszuqv.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtzjucnjcj.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtjhmfivfv.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtihzinene.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gtnkqxokxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gtfwplidcq.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtuyqobvcy.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtkcnrnekl.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtgnukidqk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtxyubtrcn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtxhgtioed.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtskqtlkoz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtgwdgwtrt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtnsfdhndb.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtoxhioyax.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtqyiruleq.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtlsgxnnom.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtqjxexwhy.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtarvjblqm.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gtfdbnvemk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtknqxlvqm.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtxvbbejgs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gteuecfmgm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gtsrthusjh.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtxzwznusb.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gtmpdhydlv.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtovlgbmia.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gtmkocvpgj.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnzktmwn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtnsbphovo.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtftmpigzh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtbcalmdgk.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtoybdmnax.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtacnoxtbw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gtgienrsng.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtifedeqif.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtjyrzyluj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gttedonsqg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtylugbpsd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtestrojwv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gtrbnrnggl.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtpmreieqh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gttypvcvge.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdbsbcwc.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtwljffufh.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtkszyftxi.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtdisujkir.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtnflvpdqa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtvqzqakcf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtzdwzmmme.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtnqwcombi.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtuythprmn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gthapfknus.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtqilccrkg.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtguvhbper.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gtkemdhqps.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtrnbqmnhs.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtpblnemrw.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtwoetqeoy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdiyiqzk.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtpgkxckji.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtyelkamgp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gtrvvswfdk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtpqiwgrch.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gtjvqtfihs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gtgzayghmg.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtxulzwjwg.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtphdvijmd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtplzjhcdv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gttfldplkm.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtfduzaqkw.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtqcvxeair.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtzwnzxcgi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtxzrwvydc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtslfmerdi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtwaxoxkcl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtiymydmvr.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtmxhudszf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtqqnhdvmo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtryinfkoc.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtvzofhlzl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtrwuvoxlb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtxjeuptoj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtbzmtncdp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtlngmfqyv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtzdcosxgf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtfqdnwwhv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtrqywftpx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtqeyykvar.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtvievqgvr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtwmxzncvy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtryezajug.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtaqihnxjy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gtyzeetgew.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtuisldkhv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtjzlodbdg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtfborkfyi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtlftjqbmn.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtekiftiby.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtpjwxljpk.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtritzuglx.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtolynkvpp.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtvwyshaqm.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfrsblal.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gttbcqdapf.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtyetvzhba.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtrnygtdcf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsxgnlatj.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtqhkeqxvq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsuajocsr.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtwpbvdait.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gthrjbaqja.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtayfpsjaf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltdummbv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtalkomebk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtwuucpnwu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtxleuijvu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttxyiatc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtswpgttft.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvycpyyxp.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtzlqsfetb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtbbzfbifh.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtmqzhkzrt.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtevsoyrdp.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtjoymtmza.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtzkanoxoa.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtuegigkhk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtnwyjvjrr.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gttxwiqzco.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtvzrhdofz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gthhmgdavi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtkirpurns.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtdzomnhqi.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtkwhdsrbp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtpfkxtpet.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gtxsfcmodl.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtehfysxef.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtlrzsygfg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtgneuescn.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtqthjduhu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtadgqhzga.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtefbofcbq.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtnnubpzut.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gtjluwnucw.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtaauodned.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtkwwfwzmt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtyxanfhlt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtjbrpmwzy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtbeixkdxe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtcdlslhbk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gtcqkzswhd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtpqkdoons.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gtkgrhbfks.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtvvoeasug.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gtixketvuq.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gthrbiwzww.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtzwjbuxuc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtfmfodkin.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtagcqalxi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtepytbowf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gthfflthuv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtqvzpmwbs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtfqyvkvnp.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtbpbcxrly.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtlelprsvx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gtgoappfcy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxenuqszz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtefcepuzj.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtmfikueqj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtcsjkxqzl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtvbfineju.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtprouvlsk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtzoksvhaw.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtlopmgqgb.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtditspsrp.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gtyfpmijpt.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtlwdyndrf.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtevieqppc.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtszjyoopz.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtxpvrccnc.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtxgrvftgd.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtillodqla.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtdiztjduq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtqkqvyapi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtuzshjcjb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtxgwfhztd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gttrunhpii.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfokqimq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtbjhbrmjm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtbswtjqgk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtrvwevnnc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtnlarxaax.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gthyflfytf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gtxgbzweln.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtvezpjqfd.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtkzxrzqnw.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtsxsbqhny.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtmbmixtrd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtedetfzbn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gtciffxizf.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gtwvnueirj.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtrimrbsvl.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtgjzprozp.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpwgmltq.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtkzqezglb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gthbgqpqnv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtaqoblaut.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtkzywuxko.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtqradxmje.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gteflvezom.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtkedsdhnu.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtpvhwkkne.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtbnkuyzby.html

TS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtrevsuarn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjxqomhd.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtmuokuldf.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtldzackmj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtsqbikjgn.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtqyjabjtr.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtyqtpnzqd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtdfeaijge.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjntnvgw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtbeszcjhk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtsczblsue.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtpauxfwbx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gtqxdnggko.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtlunxsyem.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoflecjs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtsxvfwkpt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtjqcjniyq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtdfxnziti.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtttyiiisw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtjsrlmviq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtgdewqvbl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtnevypcih.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtpedimklk.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtfyfxyjna.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gthjbrgkhi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtjylxxlou.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gthsmlpjqd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtzbqqpukm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtlfrtmmrr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtpmamtwkz.html


<!-- 参考信息 -->