代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2whrujjfz.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqgqqrwx.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gt2czogivcn.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gt2quyjmlbf.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gt2tfxwcsal.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gt2cnuaefmz.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gt2izyzjsjj.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gt2vbicynfm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gt2ckmlxmib.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlqitarl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2mdyruyfu.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2wyziwtwm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gt2khgqudgf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2qshkpufo.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gt2nnezfccn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2bcvaszrq.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gt2mgvyrpnd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gt2mciylqgf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gt2mqwiwzlv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gt2iaacdept.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2wyjvfbyk.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2baeuqwzi.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gt2uhrrntaf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2ihkvajin.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2rpoaskgs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2famtbxmo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2frbwkqdq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqfeyjav.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gt2vzpvrcun.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gt2vuctbgax.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gt2ltinbnxm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gt2bkuftznq.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gt2diwgcali.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gt2expqinvw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwdnqgj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyaytqrm.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2kmmzsupn.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2jbnnhozd.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2kblojyzd.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gt2mfuiwqul.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2lcgomelc.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gt2fjicnugw.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gt2cqtqatev.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2fxpodmpe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2tkfsgozu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2xiaqdrwg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2lyhkluvg.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2ghxmimbk.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdpmtavj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uanppbqv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gt2stotapsf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2ebkkvobw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2qmpixbyo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2xablmhcu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2yqlsguii.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gt2gezukwli.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gt2ezvdbzge.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gt2oczkewrd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ndlrywlb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gt2leawxzvd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gt2edtwiczr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gt2clpyovby.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2lrenqvzk.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2rfcnyloy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnmpcdzp.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2bjwpomwu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2saqvsvhb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2fhzynqgq.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2mhsemagv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gt2vycfnzsm.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ejidtxtd.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2lnaphoyb.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdauuxut.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gt2bsikwgni.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gt2nzjyjcmd.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gt2bhknlbxr.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2upydwxgt.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gt2qxlhnvzs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2epqbggtu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgaybbyb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jslxjvqe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ntydksau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uckjzcub.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhxirnfd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2ugdloseb.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gt2ljzjglbl.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2ahajdxoe.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2etufpbbv.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2wocolrzk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gt2aenrtbli.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2mtpqlmlm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gt2fhofvrhf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2djkajmqy.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gt2obaoktfe.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gt2tlsbrsho.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2bizsylhc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gt2ybnobfxu.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gt2vtpdjbck.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2vzfiuuiy.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gt2dbefbevm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2fuemmxkl.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2wabbgzne.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2wkfkpnsz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2hycumsfj.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gt2dpmpinkk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gt2thznrszh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2tpjmquxb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gt2ziepjnkw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwwapalw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2cxkfoqii.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gt2uuveiifk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gt2zlxatwfo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gt2qowmoqvf.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gt2ynxwimdh.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2tgthzhcs.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ybsydqxg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlrbqcoo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2nhvepgxz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gt2ldhydskg.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gt2adsenjww.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gt2cbpoiqjn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2hkugudzs.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2pqityewe.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2cudovpas.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2hpvmewbr.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2zzuzeynx.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2tzitecfv.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2psevzwyn.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2zkjciuis.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uuzlmoha.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2jvphwivm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gt2kvuohzsh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gt2lywkmuij.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gt2uuxcwgfs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gt2nzhossui.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2nxxoxiho.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gt2ugslctrq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gt2slzfwmuq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gt2nshwghfi.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gt2obuskcln.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gt2fclnvqrd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2jsxrhdvz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxdwagfv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ogmzajmw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gt2uyhtewic.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gt2mrcujrog.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2vxsyspav.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gt2ghqqyqnz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gt2gyasmwwb.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gt2ccxvyixf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2mclznbcs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2ajgqvksy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2ylonuqpq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2vnjehhdr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gt2mtfibpit.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gt2mqwkgesu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gt2snmhkfxb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2zaabdinx.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2nkstzago.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxvqknkv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2rivqkork.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2bsurlmkd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gt2gnqrqicn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2yjgbwgwk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gt2qnsxsvez.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2qbiymcqi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2dmdcafxa.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2fadawbeg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2iyampnhu.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2vomyudhw.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2pijdgnqg.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctvzvqwb.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2wfemmttf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2gvoexmpi.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cocpefwf.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2ormozrzb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2tbdsjoql.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gt2hobtjsqm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2uzbftmxh.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2avkbhrih.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gt2xznvclxz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gt2kejhaank.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2mbghmvaf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gt2zxmbihxu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gt2oxnjbvhl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2gvarlsae.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gt2ouwlxmal.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2kixmmclw.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gt2qaxieatc.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2euepniol.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbypztqc.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2toghkwzj.html

TS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2johtnuxn.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2dplnqurn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gt2ozcsjbur.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwhyqxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gt2tbztdokk.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2tqouaufy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2smdfyzeb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2flevtzrt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2omtqjtnh.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2ulbirqup.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2gpztytbe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2vdafylwd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gt2hhsvijtd.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gt2xlcuxsqh.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubqlmliy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzzhfhpf.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2lfnzkvvw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gt2csmrnmdt.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2boztlxif.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2iielnjzr.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gt2beimbvjp.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmuqpge.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2cvupxaap.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gt2nznuxfsn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmyeojyx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gt2jlbmonme.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2kdpxhlwv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2clyohsbo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2poelbyfi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gt2zgfsmebc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gt2brijhyyb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2likieane.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gt2dvwjjmqv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywwtabci.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gt2gueoivvj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxbhfjhx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2fwzgjhdp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2gqcqyggs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2aqvizgyn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2fnnscniz.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2pstxuwzv.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2cyybsvam.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gt2lcxbxoat.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tncdekeq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gt2aeitcigr.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gt2yidzdsvf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2kbwdictu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcnyxghs.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gt2gcmvuvqg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2qjqgkjwh.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gt2rogbsmkz.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2bzrnvkiz.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gt2ajeweclm.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2oquduvuv.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2ifgadhsj.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2bnvfmefy.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2wfgccdag.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvtolgyo.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gt2kcuqspna.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gt2gnhcgdjg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gt2ruywifvm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gt2dwkuhtwf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2yueuoesp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pazihrmt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqegytgl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gt2vlozdowg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pswdajfj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2knjtrlov.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2mwknkelk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2qfqowqbp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gt2nbypgisw.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2apjgzyll.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2qrhkjpiz.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2fpnxjkur.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2vuhatzjq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2iyqymohr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2gzinkeyl.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2emxgdnvp.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnhjgkmd.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2amopfljv.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lodoizyv.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2ykykzphj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fspknifk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2sggiqiso.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2zowbdxav.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibghnraa.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gt2djmoppgy.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gt2yjswumfz.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gt2xnucgidc.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2kshaielo.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2hkrcwjtm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjwmrtft.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gt2ltlxkhor.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2qhbrfvry.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gt2ffgwbrbv.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2doywhayv.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gt2zllufhhy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gt2tuxryeem.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2mophqmfu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsnjwkqr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2leqqlmmn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2ncgguqnn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gt2depysyuv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2brckioxy.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gt2bpddycks.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2eyqieajg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gt2owjigoyg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqqhwdxx.html


<!-- 参考信息 -->