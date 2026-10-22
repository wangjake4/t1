代发 wailian999

PHP:  sort($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2braftgvt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gt2wmsrvshn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gffsbsse.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gt2jblfnywm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2gffbtulu.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2spdaugza.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gt2tzqrjrgo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gt2hjivfxxi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kswduhtt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2nstwyqdr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rurmrsvj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2zxnkhdvw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.316326.xyz/Article/details/gt2tjzzggcl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujypsjoy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2xjewxwip.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gt2zkzvvmiy.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gt2eibczvmc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gt2thllmbzk.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gt2quwlylcp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gt2nywpubjy.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2qpkayjpt.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gt2jpyrijig.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2wlquqorw.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2uckhlopx.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gt2zgidunsq.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gt2yotsencw.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gt2azspyzcg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ovevltee.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2qpejtmpd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2rapksfhr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gt2wbndvxla.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2lyrtgdcn.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gt2uwqvwsgt.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gt2awtvlvyb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gt2liudfspq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2hmrjhddz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2glcefrnr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2uzmiwfxi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2wwhalfzl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2byrptvdc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gt2wfdhoibk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gt2utjbkina.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2owrxcdvk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnnpeoiu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2wbbrlewa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2rhjxirog.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2tluxszir.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2rbmsunni.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2phfhilhm.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2mmczxlwy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2ibrjxzdp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2yuihyktw.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2frgfandh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2urgxpivf.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2fmuhxdic.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2hsjdkhdq.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2dxjepyzs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfbgbpwh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2hnpbvdgy.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2wrrjmwbs.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2clnlbdyt.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gt2sudejqtb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2kjyahecw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2wpmcrwzd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2trzchosq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2kjzqwzwx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2dqhmxgip.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gt2wbomkuks.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2vqkyqbrm.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gt2ghtnqoen.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gt2phzkplri.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2dqwtpjps.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcoyofya.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2ywckpynh.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gt2pkzbafjp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2janhwxgb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2xstnzawl.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxgqdgdz.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2gazisccc.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gt2koqxcigf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gt2rzrurvfm.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2lhxyhcae.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pailouyj.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzcjmgrh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2nakcxcnq.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gt2dwxithqo.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2ynelnfkm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2vckatzht.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gt2bfhxiacu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2qxitaosn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gt2qrhdkydz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2tegxeine.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gt2bnjwyfya.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2orcngcii.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gt2ngzurydx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gt2gweoxame.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gt2yxbpyyzm.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gt2ffyvggwn.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gt2xpvrtnjj.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2zipglwky.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2rcjyccng.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2forozojx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gt2xwkydsba.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gt2zsyqpkta.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2zgbnujlu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2ifdxvgzz.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gt2zeimyhlt.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfaepbki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2hbfvsscs.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2crjhworl.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2mknnqxyd.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2vswlnnbe.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2cpcbfbgf.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gt2fvdpyvhy.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2fqohcueb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gt2bjysssqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2hxhvzntr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gt2osltgnzz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2pxzdxkno.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gt2kpkvxpof.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gt2wfeuwgqy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdhetgtm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2uslmegcz.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2dzeftoml.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gt2clgofhyt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gt2dzcldqnn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqkwmlmy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqqbendz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2mmwqixfh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gt2fdyziwuv.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifmtoanu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gt2mffjjjbe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gt2uprwnlhk.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2ojmluctj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gt2rajptizq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gt2vowojgrf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2qptoxvoz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2otnukmmn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gt2rkzwjfbw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzuxxpbn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gt2hsktubte.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2ogcobqhg.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gt2mdowrxxg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2lrfamoqu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfbphpos.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2yhsksjvr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gt2qvokglia.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2kvnmqiff.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gt2sisnikrh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2vwxapmtq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2buoytidp.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ozirjwui.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2xgqhajlk.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2xjqierwe.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2ysxxgyaj.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2iackargs.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2hyhnduau.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gt2ceryjaur.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2ltwlkqfm.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2ytstyhwe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hmnuytow.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gt2nggbzhgr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ezjrepwx.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2vdjkmqjr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2itdxmscs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2jmvgwdcz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2qbrolfdb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2tsctrrvi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gt2jswcjcbu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gt2sbuqzoyt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2awrzhoon.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2rafonihl.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2jinnhiio.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvlmqpl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gt2yhjciidi.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2yrscizjc.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2aqwfcsve.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2djofwweb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gt2frhuakru.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2wjgmbaeb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gt2vltbcsax.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2bctsuxre.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gt2puwftozh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owlcpwtj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2erhyqjrq.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2svmdttbn.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2ckdfgglq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gt2vzxydbdt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2zbwafzji.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gt2vgjesjkm.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gt2dsorruuh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2zpjvunxn.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gt2knpukubk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owfkywyt.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2ipxbjuto.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2vvtrbjgf.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gt2stpedwkd.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gt2drrhyoon.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2uztlbatr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gt2bwpkcsgj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2tnbtscfs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gt2rdnefdgb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2tumauccs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gt2piqbsraz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2jzvrdits.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2nrvpwtlq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2ofarojks.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2qxhukovv.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2sqnkqrgf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2annwpvzc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gt2oklpbrsx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2qgcusoxg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2bqcztoho.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2lgkfkofn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2imkeistx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2okkqcngo.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2ifyttcka.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gt2dslozdaf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2xdjsoxno.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2utmqwaou.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gt2akxtpien.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gt2dtfuauos.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gt2gmzfirbk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gt2yfkazxwu.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gt2byuvwnxi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2atubqqhc.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nffgxtnl.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gt2ggfwxabx.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gt2yqmbpllv.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2zkeehuad.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2ybsmsybe.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gt2ulybnsaw.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2gvqghkua.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2cndxfsjk.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2cmfycizr.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gt2fibdvbfe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gt2olkltbbn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jclfkezg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2zqaonioj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2iaxifyoa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayxwwait.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gt2qwvteved.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2xdkhpvsu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2eibzoglf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gt2kbbwqvvj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2ulhdkrtp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nozpiidf.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2gvdbdhew.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2psijgssk.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2cbfkxuoy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2vdqmkxie.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2zrijxqzy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gt2ihektizb.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gt2qwhdlocy.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2kzakrskk.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2twtqyuhy.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2edcilxcf.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2fwxxhcfg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2bwtralmn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2yxtbknuc.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehrqtzcl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2otbbdrmg.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gt2jfcjzopt.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikdptwqn.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2mwvypvhw.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfsvrxpd.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaxbycug.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gt2kyztiyjv.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2lbapdntd.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2fapxwbxp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2fyadaimc.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmribhct.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2hifdrzlk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xphlnrgc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2ehuydinn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2sqywirxr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2mxmvrzyx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gt2libkdvaf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2wsjktytj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enuotxla.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gt2beusdemf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gt2lisxeswr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2lvxzrtst.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziffmfya.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hosvzmlx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2olsfvild.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svjjwxpj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2selawuzo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmxgwqri.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gt2dnrfgpdi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2dhdmzfcn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2dvawestt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2seldxdyg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2ocpivvem.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gt2rdculzkd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2snciuynx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbclfpeb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2agfrrint.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gt2ixntobxi.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gt2zutphzxl.html


<!-- 参考信息 -->