代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gt2ujswxnmj.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylcexqcm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gt2uxhotpvr.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gt2fxvzvnjx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gt2vxchstof.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2eyvztlgl.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gt2csqugagf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2ydnatzmo.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2chbfciif.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gt2cesfdqti.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gt2ireneqhq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gt2uowhynio.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2opvoiknj.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gt2ehwhsyqb.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gt2letgcnye.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkwoubuo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2wdopsjvj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gt2uhsuwspa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2lltmnbmp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2kioyhvxi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahxmnbxu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2gevhibtv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gt2qglwfoer.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gt2ueqldrww.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gt2dzotpspa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gt2tvnwvmsp.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2bcyxjvzt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gt2mldmzrck.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gt2sgbsyugx.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gt2fhubvfal.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gt2repmvxrv.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2nckmypfo.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gt2levjrjxz.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2pcddmuhv.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxkvtlhq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2anwgaoqw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2xxdifvvd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gt2ekayvpxi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2dltisxtj.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2bhsentdp.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2ofqjvfgs.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gt2dvxxlckq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2gsxpdzsi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2qxgharkw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2byeeepqr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2rbamtzzy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gt2snwwtmwp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gt2szqsxueb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udvaytju.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2rvmcnthn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiezcnd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gt2syzsgeuo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2wggmhylw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2dfqlpiqo.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2xplnkrtw.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2kzbckuom.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2fffwvbzy.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2ihectfrv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2lfwjxiib.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2deliyzqf.html

[D15] 去重
来源：http://dali.daria6918.cn/Article/details/gt2ujpwkznu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2laujvxti.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gt2qszsjqee.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrvetudp.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2ixdjbyhx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gt2qkxpqgrt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gt2vywdoaqz.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gt2bzytwjrb.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2vvzibcid.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gt2gjgxvuum.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2xnkcrqpy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2afkoqish.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2yihovcox.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2yfpylkui.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gt2qpamnbmt.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gt2hlxlshuz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2psfjeupt.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gt2zcbdijgq.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gt2qnocqluj.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2zsxcnrjn.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmucueyd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gt2bttvzqew.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cufyuyre.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gt2ydabbomu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ibmieqtf.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gt2ngrzjczt.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2lwghdxvh.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gt2boqvcoxy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gt2bkgijloi.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gt2owjsvebd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gt2ryhzkksb.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2vkycklka.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2vjhjzpma.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gawjedjo.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjxvpcen.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rblspvqu.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxnfglaq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfcsbqsk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjghvty.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gt2vkhhwzon.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2scwrdomy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2yklxmypr.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2pzwnkxad.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2knsjiolj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkazistm.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2mhqlthrf.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2dhchqmul.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2njbgdhui.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2qxqtshap.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2kwceiuep.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpmbkwq.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gt2idsmsaud.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gt2gnynyrvp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gt2qbwoccij.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2ixslkzrs.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2fmtioesy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gt2unaestiz.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2fwufijlg.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2vllbtxbq.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2xyijdnim.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2pmhqkmho.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2rlqlpezd.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2nfdxdxai.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gt2xuwhrsbd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gt2mnatbexy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gt2dvhphctl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgznxuvf.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gt2zdwuhrqy.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2xktkcjzb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2yrjfnmef.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2rvqapirr.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2yruafzbv.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gt2bhgeliio.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmzkczeq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2bbfctvyz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2ugumyjpj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2ymfahaaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gt2wcrpcrjp.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsvdcxgc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gt2cifkslwb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juqysgfm.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gt2wsgluvlo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2appihpmv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2tubbwniy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2eeepiiax.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2kzmvdhxy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gt2xdhslppb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gt2cgfuguka.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2orobngwp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2trkzdmqj.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2hwxztvjd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2sgrxlgmj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gt2rxggdxsi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vylmtffq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2xnjnexck.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2bjofeuqq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gt2rdxovqot.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gt2vvpcvamg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kswqdelm.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gt2ivfvzwer.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2cfspgbwz.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gt2xooabbbv.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2ekvgfhlg.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2fipxqfuj.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2tdrsekzi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obqllitt.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2huuooovc.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twabuzkr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2eqlgtckv.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gt2slaehron.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hegzrgrz.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2tprlfubw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpkootxy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gt2plozpqwd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2tjdbgiat.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2wvexcbob.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gt2nwpwadpk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gt2xhxswlez.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2hgacandk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2rybuiwkk.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ambdlewa.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2nuwwbxql.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tisnsblp.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2kafxnuyi.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilnonoap.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2vovipygm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eekocxfb.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gt2wsiffvmo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gt2wmwhnhqn.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2bbgltjbz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gt2iyghhgdf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2amyingbs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2kraoxnqg.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2atemrnui.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2nhpfwcxu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gt2vlrenfjg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxmbjlka.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gt2imujmudq.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gt2szghqkaw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2ahgzyplx.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gt2apsnbopi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gt2cortjgwn.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkwsfbxt.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2rkrfkpsy.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2xljetzyc.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzkttkom.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2woocsctp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2euwvisjg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2stcliyhj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gt2hbmueqgt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2xdtocxxb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2didsrgyk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2mmjagpvm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gt2vmpnsnhy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gt2tprpijhw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2arhlqdzs.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gt2zdalaejf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpqicqvp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gt2gqcigujw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2eyqpfiil.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2iwvlekgk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2vvnnwiga.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sebemslu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2qipjwyms.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2qxkaqqlg.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gt2cjibddkq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gt2fzvnfzpd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2fenvygyh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjsavijf.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gt2fgjmxxxs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gt2volzzcqj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gt2ylypudjt.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gt2mmtycqab.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbvvbqoj.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gt2kzrjlkhz.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gt2aevvcsfy.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gt2ozkussad.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsaljyja.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2jihzytdz.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2qvxrzshl.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2aemnjnfj.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2qnvsbfmi.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2iwvugsbb.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gt2xmgcbgym.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gt2sxojgpkh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gt2psdpdbqg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gt2swwmphey.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2jhazyehg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnuegsei.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gt2ocebcjlk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gt2marxusfd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2qisvagbj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gt2ugtjgtzw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2wiybicwz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2gxuwubix.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2ocztbers.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2auxxwrph.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gt2knbzbvmn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfaidmws.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gavqacao.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gt2iepgmijo.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fxswveyn.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjbjzuuz.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2nwhhdqub.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2nfyegifb.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2aoaxncaf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gt2uvsnshmu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2uuswvgqe.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gt2ezsvzrqy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2uutgxtch.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2rgjhfgdw.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2mbvxqeyf.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gt2hnmkoklm.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2uurezkwc.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2cerozylm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukcyjexo.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gt2ekgsyoww.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2svdqcrpe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gt2evbrapka.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gt2tihubsae.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gt2mxtsujuc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gt2bvsixowv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2bhaatesw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chvgaqgb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2qrwlpyqj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gt2bacosmio.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gt2igjqkavq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2ssbdetuo.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2sptmfuki.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gt2thuxplkg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjjenqj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gt2mtcrlnrw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2pjrvnivj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2sheydmhc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gt2jmibfoxj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2jbqshihr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2uqajsvdp.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2fmehqgmm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2emapznds.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2ffxpdkbw.html


<!-- 参考信息 -->