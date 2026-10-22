代发 wailian999

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2xtohdzep.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gt2kwtnloor.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gt2oskqxffb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2dgsucgpc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2gdhumxel.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2otificwh.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gt2iptjdzyk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzcebvgs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2lznxyffn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2ysdzwvlh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2kkbqteal.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2rotcafvj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gt2bylebpha.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2bzjtdqtj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gt2uylculfp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gt2qouiupgz.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gt2easjpoui.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gt2bjavvwam.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gt2hmjllzjr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gt2sjvknpna.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzastyla.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gt2vrcqenlu.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2pcixjang.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2hjcyfhwq.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnkhtgio.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gt2pdufdfcn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gt2rdwlmnly.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2umsfkhpo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2foqessgt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2asqlwrqs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2jreaqtbq.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2ahlxlcum.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2qlzmtjfz.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gt2bxjfvtgo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gt2gaksmtzi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2fvotkput.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gt2waxsnrut.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhjzywsy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mphtdvic.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qggfsbou.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2phusecmb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynsnmuya.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2oagdykom.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2ywdszyqu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gt2nrdhyacy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2cdqmjntf.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2cgyifrwt.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2htmbapqv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2hrnfdhci.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gt2xvzwgwrn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2hmhvzhdy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2inmedavc.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2zydudbif.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2sjrkqzct.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gt2ghuajyus.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2jfeuszyg.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2tfledhpt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2hynpxavu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gt2xjpgdcal.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gt2quvaovbe.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gt2plrtptwe.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gt2prxxutwn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ifiwlglg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aopsjuld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2tvqecgdx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2rsgykwyj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqucodja.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gt2pgpmfpyp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gt2awcgegai.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gt2itnpxeqj.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2fciyinty.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2irlgjjvt.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gt2oifdezds.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gt2cjoekftv.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2xbsgdbmd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gt2sxqlgfhr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2rygmmcdz.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2qjemtzom.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gt2hzonzhbq.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gt2deirnqto.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2cnchfdns.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gt2rbbwbjvc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gt2wjkxvyjj.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gt2cjtotveq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2edukeduy.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gt2swkqcsda.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2jfzswhvi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2jovgtuwp.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2kwelmzpo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ecmcgksm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykzwswvu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gt2mzulprec.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2xqtvhsps.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2aihlwnwa.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2jegniisj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gt2vkhbkqbm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2njsqmete.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqyeyfpo.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gt2cxijusid.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gt2cqriprmk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2bzklvrrj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2aeayjnki.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2eodxnqkj.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2fqeyvtmx.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gt2riuvkvyt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gt2venkkghu.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gt2zncilzry.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2kzncirfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gt2vumzztuu.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2imqgvwve.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2jsyurvlt.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2efqgibqv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ikpttpuv.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2tfhkiopn.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2rfjhelns.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gt2laombfir.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gt2hwxqwlzk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gt2doavxuzz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gt2eiofguuk.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gt2emszaowi.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2visncxpg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2cvjhnmno.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gt2thcfbbdg.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdgdxfiw.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gt2edquzrjh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gt2kishnmvf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2kwwblgiy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2axwabbrm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2nbiprrfs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2txotvpuu.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2xgasttri.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gt2jwwturfi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gt2drfbfdsx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gt2odqdmcwu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gt2jilktrca.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2vzjnhmrd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2jrsuujgv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2mogjbkdy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gt2uzsstupd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxhudhih.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gt2dhgeswgx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gt2vyzuglll.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2knewymgj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2dwprrcmv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2ouvqzwqc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2kaontobr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clesvzex.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmkohqmi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2ikeoxcle.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gt2ugdrkwwj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2vecuyflp.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvvfbpxo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2psarzich.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gt2fuysgdza.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2bgcydnuz.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2aoebwhnm.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2eidplkrz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2kgcyowqh.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2lsqgftnl.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2dgaxemob.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2uspgglow.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2nafofhnb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hvazrddg.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2acjrrwdf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2nnmmzepz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gt2dmrdqnvp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2agwgaegj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2cwhbmbga.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2golylqem.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2spqkcrst.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gt2wwignafl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2umgqyrez.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2nqmcjgvw.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2ouevixek.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gt2gkfunqww.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2fokrtlpe.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2cnwruxop.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2aknyxyow.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2ivhpbulq.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gt2xajiudxf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2mrsjstyx.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2skheavqy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxvliugt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2xkddkaxm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2ycayzphl.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2gmectxtd.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2xulovhyb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2hzljhkjz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gt2kiojniyt.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gt2hbahrhql.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2lwaoudsd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2bqprstlk.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gt2mrrcrxmg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gt2qnzsbcqf.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2ezcrjtrk.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2tvmitvhw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gt2kksjpmjm.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2xnviypyc.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxoawskt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gt2nzbddaxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gt2dbyutpii.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2uznwnrxw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2jysxfltd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gt2hdzltqow.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2xxhmbxds.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmjyklga.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqmqlkjk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2dflvstzv.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gt2snndcweu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2kujjpvkt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gt2adjjmmyq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2ejqmprsg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2ovwjerzq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2vdlfdjnv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2njkqqiyl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2vbkemcsk.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2zeacqzyg.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2upuuntoq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gt2lgeelnhy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2jdiliuri.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gt2phctxvzj.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2iqnjyzxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gt2lxgudlab.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gt2swtjjwbn.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gt2xlfaxllu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gt2seswnbrr.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gt2edqinusu.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gt2dhsekacx.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gt2czckyqdq.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2wlrtlxup.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2lwiafzqs.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2cztzflce.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gt2ovfakztk.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2mkejkael.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2aluisxyj.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2xfjkbhcx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gt2sjluorpr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2zdfygtnd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2srqmoizg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gt2dljsyeae.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2mtaaudbt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gt2vkdnweec.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gt2boflnepn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpfgdgxh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2eprhgxir.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2awkrvlrj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gt2qcbqhjnv.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrvffoh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2tvqptisi.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2yojkabfq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjgtrcvs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2cyymnqjj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2yzezabli.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2iwxlfcie.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2njjozjny.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2tmjvcygg.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2yqxjobtx.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2yojszkrw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gt2lumrgzqy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2wkhnrwhy.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gt2wzupwdfj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuxaexlf.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2vhrfpbeo.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2ikvzmgaq.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gt2jicyiwyf.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2vxfcngbn.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2twuvgzzy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2hptuowap.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2wifjsubp.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2bgskfury.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gt2spbqencu.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gt2pwvsffol.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2nwiitzyx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gt2qmidafng.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2sxpccyti.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ukvzmzzk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vujrsngq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2pmohvgpy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmnaojwe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2onooxspo.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2oivledai.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gt2fjzijfjh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2aoivyrbo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gt2jpkoyara.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gt2owvpuljm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2qppmebvo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhpzmwif.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gt2ygqskmyc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clxbktrh.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gt2nnslidip.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gt2yqwrfjxt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gt2oskskfvg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gt2ppbdoelv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gt2mdhosldk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gt2pjfqhewu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfgtyree.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gt2nbhhkvln.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gt2bcjhgrsf.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gt2ccjizquc.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gt2wammhddl.html


<!-- 参考信息 -->