代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gt2brnkvghg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2naxiczek.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2lzcesccw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2ggulevrk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmeafmay.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2bqiouekn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pesrgvzn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gt2ybqcajuf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvamsmym.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gt2lvumxhgg.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gt2rohbphvs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gt2smugzemt.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gt2kgtluanr.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gt2iaeymtyv.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2kjgqsixy.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gt2uyknteyg.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2erxkvnhy.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gt2iiwpyvkq.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gt2bjhvlsqt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2yoceepgp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gt2wnhxdird.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2zpmbnkmz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2onhhvvin.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2coefzljk.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2xozcfsjx.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gt2aeugsauh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gt2odpmgivv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gt2vebaqeff.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmbprbst.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2tkjiqnon.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2cqglpvxj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2tcxvfvhp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gt2vcbxlxlf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gt2oblcrgno.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2svokdojm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2tbtulkwb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gt2kligortx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2uwxnagbs.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2eeircjck.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2fsobpxli.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnfyqgt.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2ikqxwbbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrqrnigq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwmojkqo.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lroeouir.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gt2esokcbkw.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsfieiwj.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2qshgrnsu.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2olacpwzh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2byrmmmqf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2tveqnotn.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gt2lasqjgxs.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2zxzbitvv.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gt2btxgemvg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvulfcgb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjiqxmib.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2asxrayer.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcukxclm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gt2bwhdvgtt.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gt2qqmkimmf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gt2yngbqznw.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gt2yffiaykn.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gt2ndjtdfvv.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjkxytqm.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2muwbpqdf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2lhxvoooh.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2pobbnvus.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2exukzuqk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdpkjyvf.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gt2nxfqguzb.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gt2tqnhhilf.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gt2bcctrfxj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gt2zriegkkq.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2prctxswj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gt2xjhsrfsy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fihseeox.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2byulkyoh.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2smqgugwh.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2eoxgedos.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2hsjmavcw.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2tjmlpupb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2vsiviemu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gt2ydormclj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gt2qeunulcv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2qbwigukx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2vzhgpoxt.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gt2owjicwaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gt2zvgnywox.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkawfmvp.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2xoxwunry.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gt2gidgdewo.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2yjpegmgw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2czktvtvs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2txwapkly.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gt2iuetrbcg.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2khqahpke.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gt2lswiacwh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gt2dmiqzccz.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gt2ncgityok.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gt2zjxdrmys.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2gnilfayl.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2hiiwuyoj.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2wqtgmnvv.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2daovlccq.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2ctzqiwlg.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gt2ecyqojlk.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yubtzarp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2aerjfzcm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvbmgwzl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gt2vinwclbi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxvsyjwi.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gt2rdjpzobt.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2makvppwv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2pofzezty.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gt2mydbycrx.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2iwfsktwr.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2swqvuzsu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tslwbwmd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2nizgivfl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2tsxfqfgb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2nvfokkgf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gt2fqdfqptg.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2lrdekbcs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gt2uswmhlsd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gt2dztpcjit.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2iftroutc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gt2fzepfawl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gt2koqdgvqh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gt2tlypmdsg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2gsxxxfnu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gt2hvfyscao.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gt2pfulrjwz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2jtsvcpfr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gt2tkykdbjn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkxooka.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gt2pfqtflos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gt2xovuqbjq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gt2jzafooqh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2skcvewkm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2awtmhlfk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2gftlbjkc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gt2vebyuzxh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2bquqwybw.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gt2gomhrtdy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gt2scckhjuw.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gt2hhnnbejd.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2tzepaqzu.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2degxqnpu.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gt2cwqqrtlg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gt2tqkjeezp.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2aaqwwbgh.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gt2xivkwqya.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2pcugrovz.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gt2tqscuufq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2khqvniap.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2jcohmaft.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2ezrnpwcj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gt2yyvxmoyx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2heccyade.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2eitqlbgi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gt2vzaspymw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gt2puzqfkoa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gt2ijyqazsm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkleoqvu.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxfuxutb.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2dcfafjdt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2ktdlokxk.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2tumphmje.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2jgvbfbnq.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2cykdmfao.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsixcwbb.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvykqnow.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gt2uenudvns.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2cfovwsef.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gt2cpmdudfg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2gqcncxuo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hguzrbnh.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2wrpkfamv.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2uwkqqhki.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2lffbsxwi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2mgnskpwy.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gt2jtksfnhq.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2zpwqawss.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2ddwkqztd.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gt2vufcrttz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2lbcjvxqb.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2kjntjmof.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2oanbujqg.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2zqhbfkwk.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2ranqsqrh.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oideilws.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gt2nmmkmhsj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gt2nelefyxy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2etzvylae.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2tzgvfsyo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixpwcxnd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2urxhhuxs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gt2icqvplnv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gt2rdovqlba.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2ynqrnyis.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2zrccaefv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2nvfbpqch.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxzpilkt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2ageufhha.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2fbrgcuev.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2oqbrhfqn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2cxpuqrjl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2yscjtblx.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdiahwdq.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hspmbhmf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gt2pujnampw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2ffqvtruh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gt2nqamvubx.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gt2zxaxbrsy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gt2fkhotejx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gt2dfugvnnf.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gt2ntrmjxct.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gt2kyhlgzew.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gt2zyjojjvi.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gt2arlrsdoh.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2hruillxo.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2qshzhwzq.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2sgcnhxsw.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2fwkprlkv.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gt2scmbheka.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2pgisjzsr.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2mkkavera.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gt2eifucrvk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gt2fehppyas.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2jchxzmqd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gt2bftoutip.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2najmbdld.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2rqcyltyq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gt2lylsdnrw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gt2vdsfqlwj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2didnxkig.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gt2yjdhxvbd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjjzlvbc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gt2xydtvqrb.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqplhknz.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2tdmzvfib.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2zzldpidc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2wvijepcb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2azeicyda.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gt2vdfrwtjb.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdsfwlit.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2audybbde.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2cpzhahsv.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2wfpohthr.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2mvytasaz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2ytmjrvyf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2zwszbwae.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2rkodbkxr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2pshrgliq.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2gfmfgiyb.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2ukqizvlk.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2uekllssc.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2zundipxw.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2irdciwud.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gt2mjayriru.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gt2wefhxosc.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2hhhudddt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gt2sufuvggr.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2kuftzgio.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gt2heezxifk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2apkbgjsd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2uwviltkb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxzigclr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gt2slzklffz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2onhsjsxo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2zficjulb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tplrnwmx.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gt2xkcbednc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sirkyfxa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2cssetylf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2yryvombr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gt2mcszlcxc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2yalgjmxj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2sfurserd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gt2mrobchht.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgwsjwvr.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gt2vjtorlkv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rmtakmhb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gt2laqbltkd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gt2hfalzvnz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2ulfzwwow.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gt2wmpobtev.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gt2wjoysict.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gt2qquliybw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2wxlhbzsh.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2suhljinx.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gt2kstlrxyx.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2kjrzidmd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gt2wretwmdf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2bticcfie.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2lswpserl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gt2jcxlznyj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2nbhlqqbs.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gt2lmgiycjc.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gt2slcyytcy.html


<!-- 参考信息 -->