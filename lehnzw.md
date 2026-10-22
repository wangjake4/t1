代发 wailian999

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2dvlparww.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gt2lvizfmfb.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gt2dlbkvqjk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuipvnjo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2nqdqmfkz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2qbzcgikv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2cwhyjlwy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2hkgrvwey.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ufpsyefr.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hanhnldl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2nonupoup.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2catmtkvz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gt2ylojzvbf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2sbejymrq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2rzcmdjhg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlhzgfzj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2vfsyazsw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gt2cbmivcvy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oniyqvex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2cmbbcqjx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2ivnaypvf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2caiwwdsm.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2ztbyhiiy.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzrcxkxh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2appihnfc.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2quyletiw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2aqhranau.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2lszunjwx.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2wwolnvke.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2ycecquxe.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2hcoxxvjp.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2xywaysoi.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2lywsknok.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gt2bhvuqkel.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2lgvvgeuw.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gt2ogchtemh.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gt2uyhtxsjc.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gt2fqemlmqt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2bxkmznld.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2arumumtp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2zkrndnsi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2eqnpsjsg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gt2mheatgaf.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gt2fvutuxmv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2snuhwsbb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gt2spghugrs.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gt2aeslyhrs.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2vratirmi.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2jdarioqj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gt2elfbrmdx.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gt2wxbgahtk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gt2sxhlnmaq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2amqlifyw.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2vsrvigra.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gt2qebskkoa.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gt2wraepnge.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2jhflhgua.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2jaemreke.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gt2zdnkudtc.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gt2jasxpqkd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2dgcprgnr.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nddvuacn.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2fxyocljq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2hbouvctc.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gt2mqpsltkt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gt2qyugsnmv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gt2zznxhckd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gt2gfskmthj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2trkqnwoy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gt2pagjuqzl.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gt2wnkgvxut.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gt2uchixwfx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gt2isszvufs.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gt2pjwbccgt.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gt2rqyhblyl.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2rwwefccr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2lrhvgrsc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gt2yiyltbug.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gt2leitmfiv.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2abxvjjur.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2zujufrbz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2qnqjbwjm.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gt2laxrjgkr.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2qdrkijyv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gt2ryimjyqr.html

JS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2iawhpkgj.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uslqtxsz.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2tbtmfzbx.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2gvyqrlkg.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cspethhy.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2lurtybai.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gt2unipclkz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2mlntqpzu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dejuezfq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2ldlauqum.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gt2wqmieudn.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gt2gxclrzmm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmplmgbu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gt2oefhxshn.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gt2lrdzvusx.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gt2tmxwffeg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2oauzpzyp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytzixwzn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2lazszdbb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyimpizj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gt2lqwfqbwc.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrxitumu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gt2equjpozv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gt2bzocrsay.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2lslrfsay.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gt2xgfpqcqa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2yyijfpow.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2kgordvrg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2medzobwu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsvqdbog.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gt2zedlhzsz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujbojrdx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gt2pdrcqcjx.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gt2khumbkdb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gt2zqwxkazo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gt2yqdnywpq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gt2xyghwqdj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2xfmysafd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2znuixwyh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2xlfjpflk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2fiwpfanz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2uzefhvsz.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2oagcxoyk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gt2xpfsvufk.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2lrenkqul.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2iwqshpxo.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvrbcgkl.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qupcafov.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gt2dfoahqsf.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2pvccpron.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2erimdjby.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nbpctyzb.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gt2qbsgztfo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pkpgoknd.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2zmvnnkzg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gt2hoevokzv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2jdotomvl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2sksnqplg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cixjtvmt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gt2btlkwgtn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2hplrtxtj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gt2attrsopf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2iqauhyhh.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gt2pdczattp.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2xywxrlnj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2zuqivukc.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2wprgdoic.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2kvwogxoi.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2yypusxuq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gt2stjitxfs.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2xhzpcvuq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gt2bmpqojqv.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2purngmsj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gt2fznoruhm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2zqpbtdvm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2xcokykph.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2wmuptkxj.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrbmkypu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2mqwqfcui.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gt2foftbaif.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjayvyvq.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2siyqwlxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcmrsykh.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gt2miyinuub.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gt2jrrghddw.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2jxvnubhe.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2zhbncvqz.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2sybzamxd.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2ncoprrcp.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2gwypciil.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2hqllgazl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gt2kiqodybw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gt2vnfzjydc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dicnhcza.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gt2mxqtjkbk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dogymhqs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gt2qzlphmzg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gt2bolkvqon.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2srppcsju.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gt2szesohak.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qnlmcfti.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gt2zftryerg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2jkvzontx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2jujzshtg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2acgajlsg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2cssozjfs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2pklqqfqg.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2uaebcmnh.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2cmuxiwdu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gt2hxywwxjh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiexmhtc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2oosiuejt.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkotwjiv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gt2kerwdpyy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gt2ipbemyan.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gt2dxhxsejf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gt2dqgveoar.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gt2spkmdsei.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gt2vnqxzxer.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gt2lbklhwwv.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2uzmpeujm.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2daltaamg.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gt2nclrkzzi.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cseaaznt.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2fhpyxhoh.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gt2ubdpirdl.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gt2xunyiwkm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2zbhhffxk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gt2qwkqexsd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2ulwutxfw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gt2czdndmgo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfwlfpne.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gt2ymipjqll.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gt2uaebqscj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2ryhnnxbn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gt2zyogbcbe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2rrbkwpzu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gt2gxzqokms.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slkwykvq.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2cgqogrjb.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2oothcrjb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2bqysdyjc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2rbfcymyk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gt2vzgqebzn.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gt2rszddfdn.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2xbpztfse.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2meojsryl.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2ndjcoywm.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2kpzmyath.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2damvwlbi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2zqkyjdag.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2aorrknrq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxnisxmg.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2cwcghgua.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gt2qudpznod.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gt2tnrbdfow.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2oougfuyh.html

TS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gt2suiesllq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gt2aiggbxrm.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2jjpjxvuz.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2kssfzojg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2drnenjad.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gt2uysnrmxd.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2bffiwfuj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2wxgeuvmz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ohvbxdaq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kirukbmi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2hxcefdom.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gt2ojuqklcp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aumwafvm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vjbcbylg.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2ddfutccm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2yqdcxpmi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2liyrnzvs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gt2arwguiqg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gt2svrzxqsr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2kovkknze.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gt2jnbnwpau.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gt2gqynlwlz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2ujmvlmsl.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gt2cfqjnsel.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gt2jdnmnnbq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2bmjlisis.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gt2wcomymau.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gt2oobtggcm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gt2clenrcuz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gt2nqagwezb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2mudrybht.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gt2boyqjybv.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2sjoysmno.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gt2dyhywdhs.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gt2aqavysez.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2njsqszju.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2pdhhunhr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2qzjwdfej.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2hpuiawmb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2lweocirk.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbybqkvl.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gt2vklvylra.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gt2xbostwxs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gt2meoutnqi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2dwsrnvix.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2dxwwyjlw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gt2xzmrxbzy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2svlcpbgk.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2sptjqsda.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2nhrkwmac.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2eqzndjll.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gt2ysowcngx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2jfkuctxi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2fmfavxqa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2zhcwdtwj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2ctugfowt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2ypdyjwmu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfpmrdqf.html


<!-- 参考信息 -->