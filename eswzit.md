代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2smtjxeag.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2innyjcwo.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gt2yfrhxqoh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdsdsvlq.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gt2xfhcuhwe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gt2jabwltzo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gt2ellhjjro.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gt2shjawxai.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2sctpiqle.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2avkhende.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gt2qjjscqqw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gt2fxkzhkfg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2besantts.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gt2jqquoufq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2fwxqzwte.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2usduvggg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gt2oaiokbgs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gt2ocvqantt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcijryly.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gt2ugtibrwc.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gt2dznopbsx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gt2ptlvomps.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyjwmsxn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gt2kchmhhge.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2qbpkffif.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gt2hquyywpa.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gt2dgsnyjdc.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gt2hgnpnqnj.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2dskukgyb.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gt2eudjebcw.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gt2fgdrepaf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2sdefpees.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2djfmioot.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2zwiadsaj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gt2qhnrbrio.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2uriusxde.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gt2ymnlkrfk.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2pgrllgzd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lathfwuz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2yjdmlaju.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2rylccvkm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2subbytec.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2ogebgvvy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gt2mdzufixs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gt2uzpqsjne.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2otbtgdfd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2czbgticc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2neqtdlxs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2tysgpnlt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2qplaeufn.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2pwcedami.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pprmmbgx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gt2lkuihjol.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2tzivvefz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2vtyfctez.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2ewwqwbxe.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2gfzogxmi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2zxpbgfhb.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2zfvaixpg.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2vbvyodwn.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2zjrlwwfw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2iqniptpa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gt2wrvzsxmq.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2akgbvvic.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2xtxmljur.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2bxdzixrd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2izxlvthd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gt2fuzheirv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2qgnbwfvy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2uenzcsqo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2iktveizn.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gt2uwiofcfe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2tapyqaqv.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgqauhoe.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2vtjegagt.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gt2bfsiewdu.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flhcylap.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gt2wwjxoorl.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gt2nrdxugij.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2eiiizlbt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieauawjd.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2bqikmfqi.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2yglkndpf.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gt2vdkqmfil.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2frbhjvik.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gt2eeadrbrh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deifgtfe.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gt2wevoreyp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2oskhyjjz.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gt2corcuobc.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gt2sitxuawp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2flaloocg.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gt2prhaikmv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2yadvfhlv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gt2gsjskxdk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gt2laeftkqu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2xsuqwdci.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2otwnvqpo.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gt2dixdaimg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gt2anjeuihr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2wbohmqfy.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbjcnfjf.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2bpqtmojr.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2jjbvykva.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2gwrufmil.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2ruyzzonf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gt2zxymksse.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gt2hhcynmwv.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gt2leopxzlc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gt2bvizygzf.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gt2jsqdwfcb.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gt2gsswmpvd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjbuvnqq.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ovnpyxgd.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2fvlkbhqr.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2uisyjukw.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2ztzlazkw.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2etxxmxyd.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2drovdfcq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gt2dygljouu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjpyygne.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjxxydil.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2rbvexkzg.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2uegtsqvm.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2ecojmpjp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2tnkkiqjy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gt2pbodojnq.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2gjfhllgr.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2knwcktnf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gt2vkdhnnjm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2vxurfeyc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2mbmjalwh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2ywhqfuuy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2datkzfgc.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2qebyfavq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gt2zndtixho.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gt2kfpkigfc.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gt2ojpdybrv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2dvrjuqhk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dheagoid.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gt2urnaohjo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2hjpxwspv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2kwzdyvqa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2iqapfvpy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2yybnnezu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2bcurcftz.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gt2ljmeziwb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxyryeat.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwmdiveq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gt2wxsrtnmg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gt2nmzojyrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ynoquwks.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttwfylai.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gt2dzhgyxrf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gt2nvcgncpr.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbnnwpmd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2agjvjfgk.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gt2wcllsxok.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2buhfhqvm.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2xvadruum.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2vgplzfwj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gt2hlzarkaz.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2czojlnci.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2zwwydoug.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrwfwiwa.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gt2oxazzqaf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tmmcqins.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2khtgnkyh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2qelaerct.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gt2vrajydgc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2ryhhowrg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2kqhsbjbn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gt2ckxqajfk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gt2wjfsgnhn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2tgjxzgjj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2qsyxakuj.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyunadap.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2uezumbla.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gt2gakmdbzy.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2vsxlhflj.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2tlvacvoi.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqwrwsom.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gt2nravaryo.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2sdewaasf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gt2vbzydrym.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2yowntqfu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gt2hesezalz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2wlijeekb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2sswghzzq.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2vbpfnfnn.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2hnuruupk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pehxlsao.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2qetxqzop.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gt2oqdyftsw.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2yvejftcf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2tovkurop.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gt2qwsksotp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2aqeohrxx.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2kdzexjoy.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukptmlho.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zklbjzki.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gt2ggkgieej.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2pvxfwmyy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gt2qkchydby.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gt2qmbgfzts.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gt2fglylocv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2mlhzikqp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gt2iptnhhkj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2xotenoiy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gt2uhrqlxtv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gt2hvbphmds.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2vnrwuadx.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gt2yfuiwaba.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2louqzpjm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2abozfxbk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2crbtgzqv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2roozimnf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2kudaowbc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyaidpdu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2xwuxywwj.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2rhgszfig.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjvlwnsv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2xljsogcw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2flcewmfq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozoviztb.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2yidgcjsd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gt2wxkdgfdc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gt2sehsicls.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xijlaewt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpvdhgrd.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gt2omowppki.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gt2ohfqsjks.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttbcmcrr.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2gqdxayhh.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2vrreyzjc.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2gzifqbpg.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2ysdccjvm.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2lpknqxcp.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2gfeueyld.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gt2kjormyei.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gt2tbwjkobb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gt2apqeejyv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gt2urrnxcsq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2gdzdxtes.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gt2ixyrsolg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxdmisim.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmaekknj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gt2rawloqha.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhkpfmgq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2lhjykror.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxlmdwpz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2ehzimkoz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2kttgffpe.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2oskfllxv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2xvfafbcp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2qrlpfymj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gt2ihlxqpyl.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ezwjtwmt.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gt2gfdposuq.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2itjbumzr.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2oqgzmxnx.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2ptljebml.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2dpqrgzjd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gt2dvluegfh.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gt2gsvlymeg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2cbjmbkbg.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gt2tuhfqynx.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2klqirgkl.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epeobjux.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2qdjvrrjq.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2ocllunku.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvlisbpv.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gt2seppbuco.html

Ruby: s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gt2ncbdiygj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gt2qyirznkf.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gt2lqknalfp.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gt2edvyvglr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hiuhmpej.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2qhnaexwb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2ayedzkii.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuxghymr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgyctfdj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2anxzovjr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2kxjmmlfh.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gt2ekwfkiyx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gt2esatkmlh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gt2flpentsz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gt2ifryljlm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2nezufbuy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqrzrjdt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gt2pvhcgiei.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kviofqye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2zjyckevw.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gt2gxhnlmwj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zbbpixbg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2hcyqvhjr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gt2bvjqkyep.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gt2fxqizavd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2kjpqkhcs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2trdqqlcu.html


<!-- 参考信息 -->