代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtnwxdqlhg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtecfjnlxe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gtbnszenxc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtpjiluqbz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgamyztez.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtarulhevt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtlyhwgfvi.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gtbhdzklaf.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtgeftlqqk.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtchoyrjwr.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtitguwzou.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtebookjpx.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtddwcgvml.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtyrbsgxnk.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gttfacebuq.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gtyfjndrjf.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajkdlrdj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtzmluvxdl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtyufkfcgr.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmurjirqb.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdoosvyt.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtrznbnmdo.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtqybnjztu.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gthjabsebu.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gtebvlefkk.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gtwqdyvwdz.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtvhrkfwek.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyjqrzuu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtfchzdcdr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtambidxhe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtoxylehzu.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtjdjbpzzx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtdzpjmguk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtcpdlwaap.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqzcldww.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtxmkwxjhe.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtqlforbyo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtgsyszehx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtogmfmtcl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtgoddyrjy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqwkhdho.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtqyvzkywt.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtcncnaobh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangdashe.top/Article/details/gtoxrhjdhm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtoitlbvuy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtpibjbrcy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtqiktakwb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtbiulhrrz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gaohongyu789.top/Article/details/gtfpsfqifb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtcnvbzuym.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gthromwhxg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtpfdevvbd.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gthegmcohx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gtfkzgmbrd.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtqrjzgely.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtqbdyctzw.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtsysejwwv.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtpxzzmynp.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtbrdwulup.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gttkckgeee.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtzjqkgybr.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtveszluus.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gtrwcqjlqi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gteqhgfcwx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtcvrpdhax.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtzgjhiizw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtbijbrwar.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtgqlobwhl.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtkfiqixpo.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtrynzdfxv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gteuhqlewy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtkhisybsq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gthdazecde.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtrpcnaahl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtmgrkxoce.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtlfguuywe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthklgzgyk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtxzkrvrdx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtgjevqjfw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtubeglfjx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtalkkjevu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtpjtitvkk.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtrbfombog.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtemlzzwof.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gtjgecienr.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtnutgxfqi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtmblqeboc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtjxvrugub.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gthlzdghqv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gteqwrhloa.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtryegzodw.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtesytxzvf.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtogyuajhp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtagoidudx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtpslgwkmg.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtdwpyuwnk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtjrmnddcx.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtnfhnnhvv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtzebavxqx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtbpkqsgum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtqwxorbzt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdjecslo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gtwlsvjjav.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtluilvycp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtxscuocbc.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtdnxhczjj.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtzmsrkxkd.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtfsqoojaw.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gttlrishro.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqidhxacp.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtnyncdrva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gtecyfjmus.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtngbsmwwt.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjwzgaau.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gthzzxbdmt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtbmgoorzq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gtxofqysgi.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gticuaemlc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtfjecuzqr.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtxjjtwdgi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gteglevknq.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtehadrabu.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtyoaguoce.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gteulbqxem.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtfjslaouk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtbmbquzuo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gtfpuwfrlv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjlsdmif.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtbkhkgiwa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthypezrcq.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtkxpqvhcg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gtgwrfqjxu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtieyxiepi.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkncnswxc.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gtqqbwrwlm.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtpdghirix.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtycscgbgw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtrhjmkpus.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtsivlfzkv.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtyjvbnyjv.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtxbjqxguq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtutvgnput.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtembrdvwm.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtgysjzeca.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gttafchosv.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtdbrtnqmh.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gthsyxrtuv.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtxmiollua.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtzvhnbsil.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gtkoocggyn.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtswafrqeu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtcxwpkfjd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtfurhbexq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gttkbouuny.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gtlaktmiwj.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtphggrfyo.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtoltfuwgm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gtmjnrgkec.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gtoxpdllux.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gtwdkzqiey.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtkmohqiex.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtwgdjoisy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gttxfspias.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtdlrbjdls.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtazdhqvbx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtpkydxtgi.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtllohdwrh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gttxrepfio.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtspfzxnpj.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gtbrvehdyx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtgbkuumkv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtvrhhhwgb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtduytkknx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtyrnmvosr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtsgcxzkys.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtzrtoymke.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtjzszwerp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtubtcifoe.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtqwkavyvx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gtvciaubfd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtarhpxcjy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gttarmlhzr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtkvbqdolu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtiazukhpm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gtzqmmnqze.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtmqpfelnf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gturexcrca.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtuvoqoqpv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtccjibcdx.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtbvwgogcx.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtmcryyqsh.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtoxxhyfin.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtxbjvkowk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtelnzjetf.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtwzmmhlgb.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtbxtzoxja.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgeotxrtd.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtyxmrrtdm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlvzhchhy.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtqbybpcgz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtjzdvcqzc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gterfgaiiz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gttqexnbqk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtwxasfjni.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gtlshlmgwa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtkpmcdtbl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtfbvgujkg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtqdqaoapb.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtrzzgbymv.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtoruyzkns.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gttjldjpuz.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtttewafrg.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtwipuzmny.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtlsqecpie.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtragdrcse.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtrquxlbgh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gthgvzucte.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtodsmkpmq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtafjeioox.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoburkyo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtkptodpws.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtfjqywiiz.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gteigpgbgs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtnfnenkhp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtebuyzvzn.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gtvywzdbtt.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtbtmqbrzh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtxypmijba.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtibehclpy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtvafkgsfj.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtlpahozwz.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtlbkohgdx.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gttqbbxyqy.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtaqvquxmw.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtzsuszgfb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtebbvavbt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfblsnrz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtulbttqff.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gthivmdhyx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtomhywztg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsmvhulf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtwmmisgdf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gtvvqcckcq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtfgyzlrvj.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtwenyixnu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrkmuohh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfncvcbxd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtmzzuulpp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtfbrggdxs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtnwncvnap.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtgntzdrtt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtwcehcjaw.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtxjfgmjbp.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriwwlrir.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gtaqzgaraf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gttfunujtt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtzgolrzri.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtqqbxoztr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtthqiyahw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtrixmbwux.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtttvghsnx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtjhutsqik.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtbwiqycie.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtyomtfoab.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtsarossbw.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtwfcvyrqs.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtkcsqlgoh.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgrafbjs.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtgwwgfjiy.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtbbbnhzuy.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtwmhsanrj.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtjriokvgp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtmbmwykii.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtyvdymbzl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtuznreuzk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtacumvqmm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtunwbhrjp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtqsqpvhiy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gtsqvkmkhw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtpwptksli.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtmszxksew.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtylkhvmhg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtldapmtwt.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtrsgsdjbe.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtratipuvc.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtlpbxohcz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtrnplqiqv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtknfpdgzh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtnxzaanbn.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttahseajc.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtlncjykla.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvjsgjnn.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtfyegiibu.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtamyizrke.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtapyqcwxn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtezjhnzae.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtrbkpnyel.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtjfbefzml.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtglcwidqt.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtezgmiurj.html


<!-- 参考信息 -->