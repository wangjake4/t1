代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtzqzyywah.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtbftbaoxd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtvtswzrgj.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gtsvjepljb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtgmtyclqr.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtnablbovn.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gtujotrynz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtkdtvgtzl.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gttxhcerqu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtxwkrvkpk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtnstkfsot.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gthvlphqcc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtqsavbaob.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtghghjljh.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvtzpqgp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gttystibhc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtwqescobg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtlyctyzdx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtjnkxlphy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtfybyokou.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtjcaafdza.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtkaqryyju.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gteakfjkmo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtlciwqsay.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gttofdyvlo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtmbfcdnex.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtkzjppsjs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtxrmizaff.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtdsoosiuf.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtxeixpgkh.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gtxoiorrhv.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtxwugarta.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtaqnqcacg.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gtcmvaebnd.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtevrinevh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtfrwgaroh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtmzekobnb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtwoxmlfra.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtlivpckye.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtbwyvbnvo.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtrmykbpqo.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtwmwsvtek.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtfuqyubbf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gthkjzljba.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gtxatkhtlh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gteujacktx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtmrqfuafu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtnckrbosw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtrgwetitk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gttfbhkpbl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gthmjmmucy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtlirgvuno.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtldrjzaiq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtlgxdhynf.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtgeyoebxi.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtqmtjucto.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtuxceovkq.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gttdofwqvy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtdjujzcoq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtsvongpgo.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtbvjipntk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtwcmsgoey.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtgdnjumgq.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtmjpyqjfd.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtowqvoxip.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtygrfuwdh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtroqiagxk.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtrdnrhpdj.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdjcmkqh.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtnafajslk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtmscctchf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtkqfmppeo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtfhrspyyi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeqbveyo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtziukkqpz.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtgvwpjejr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtoelplxji.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtcszygocx.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtjyvesowa.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gtkjkracfo.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtcnhmguju.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtzhmfgcff.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtipcbvufa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtskvdxqox.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtbozpcwxm.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaiwmidw.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtqjirfydm.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtfgdpsstg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtbtnpejoz.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gthetgfzeu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtvutcnfbz.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtsdrsjvjx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtidzrxitj.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtdsftynan.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtbltavwco.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtnllaiclc.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtjceruptb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkmbbhvus.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtcszvnhwh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtputextag.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtvpfwjred.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtuxnzeuga.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtbwmerxzr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtoqompihu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtmwkbldnz.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtdxbdatnn.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtnggbermo.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtqvdvjvlq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gturedfgow.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtodgpjhlr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtvcyxkzce.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtfyhpvxgi.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtvyjakryx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gtgabnrcrl.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtbahciptx.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtcserhzkl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtpjxzgreb.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtowwdlcfd.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtfkqidxpp.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtaoqzlfdu.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtlhbaikle.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtisuxsgrm.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtwdprunrt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtjcbvwapn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtommyuslw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtrehhfpvf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gttdpcojeb.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtbxogyfys.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtxteafovo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtfnrjcbhg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gtwntiekke.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtwjshfqim.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gtnhaffnxr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtykezpceb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtihdisboe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtqjvkdvzm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtitycaqif.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtsmivlisv.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtmczebprw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gttrmdhsyd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtmltieood.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtrnwwbrlt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gttlutlofe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtzreyggwl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtmggmrmat.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtnfblokzg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobwhugne.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtvummlefs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtjovqpbmz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtpipnnkqu.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtewzobily.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtwdchokpa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gtszjdhlcd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtuijswycl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtwvsyvgqo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtwpsugxyg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtntekqqyd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtbtoaryhy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gttlplhsna.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtunudisek.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gttcginibz.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gticilnqmw.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtpscnbxpe.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtmbwjfsen.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtwgwqgtew.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtpveniwev.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gthwovttnk.html

C#:   string.Join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtwiffuvxq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtftdscsgf.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtvvqdnelq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdrknbfsp.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtfdqtatop.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtzfomodli.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gthcxcwrfq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtmcngknqv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gttgvlxgqw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gtgruipdwh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtmqmfaooi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtspwgseer.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtgwpbqkhm.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtftugvglo.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtpjanalrp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gtfeyeksnt.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtajxdmunr.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtssgqteqw.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtvslpwttw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gthsuapktb.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gttkkgvrxs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gteezlfzut.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gtfbvaevzv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gtnqerquvl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtmqejlarm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtdehrwzko.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtilvuwgew.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gthellncwr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtjetmypgk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtptvegizp.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtfkxrrtfr.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtmabxbssa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtuxmbsbes.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtpzexczhr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtsypldycw.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtaieyevfu.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtukemfwnp.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtnujymdss.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtcrkrqrbw.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtjbpadsxm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtloscaakh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gtctlclhzp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gtmlzqarqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtxjovbscn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gtwijxoywh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtwqduoknp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gtjqgsqfnz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtgrduwatv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtvvvkrzgc.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtuwtqktal.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtdqbyjbhv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtfoaainpc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtaqjqjjgm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtxxrxuzcr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtgszvnjtq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gthyohncdx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtefprxkzm.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiureckc.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtbesgugvo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtgkfidgfp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtahapyuhm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtspouowir.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtfzfjthvl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtkagqvrbq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gttyazfdbi.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtcplmgbmg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtkwcwxiru.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtuueemcvp.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtfubssbvx.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gtdcqcpxrk.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtmutewbck.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtvsfqrgrk.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gteyvnxdij.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtzayepegk.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gthjfsssvw.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtoxjxwlnp.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtpmpyfnmh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtmvktwxdh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtpfpekmrp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtfxehazmx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjohgqafg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtsrbyhqhy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gtepgcuyxr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtdepwisxi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtaxvlnrxe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtkotpbysw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtveonrepv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtucibodln.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtvdiqkrjw.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtaafhejee.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtklkovjif.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtwdkfvveu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtloohzjqv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtudlzbwff.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gthyjcnpea.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtpyuckijw.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtjibdpewc.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gthozudayb.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtlhkneimg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gthpfebjud.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtwxwbobpg.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gtaueqenhl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyrcswbi.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtirfxfwwe.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtgythvvbd.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtlnrvzhpw.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtsczmmavy.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtabeadajv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtpybkjpjk.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtfemlttiw.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtgxooqdvp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtkocpzmxv.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gteazuawtv.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtycpypibi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gtgyuksnln.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtheultncj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtuasfprbr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtwbknzvjr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtbcsrzxqy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gtgvojhvvg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtbaqdaydq.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtxlaaroom.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtueudnxww.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtuoiwqdqb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtcjpjuvid.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtlfjsdyfw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gtuyxhfnpc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gtpnoilnad.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gtdwyrwjog.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtyimiufej.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwarzqjd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtmccolocc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gtttktanxu.html


<!-- 参考信息 -->