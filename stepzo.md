代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gt2wxsigkwp.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2okrfttzy.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gt2wkbszxuk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2pbpkawqk.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gt2voazekfx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gt2xtkxvcce.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gt2issazwlw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gt2ctbmnwxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2mevhhmnn.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvvhcdgk.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gt2qkgoqoyj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gt2zztqcsgs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gt2fugtxxla.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gt2quabgthm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2crpzejbh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2klrattcn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhlyhevo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gt2uxaatvoq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gt2lpvckxcc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gt2jmhhysor.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gt2fieopgpq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gt2xodvnyce.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2ramagzbn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gt2sekyzeso.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gt2oqsozvju.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2jugyiznj.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gt2gvecoavj.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gt2wkqsfeli.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gt2qsemrvyt.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gt2rcqeacav.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gt2afdbkhji.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrgciasm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2hmqjwvpn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlgimlcp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gt2zsmrdwcs.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2topgiple.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2kniyqsqw.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bryjxidz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gt2mgdfyujb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2snncogrt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2klhluizc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2gofbkrli.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkmvhxws.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2foqxnqhv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gt2euhpghkj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2swlelruf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gt2xqnudlgk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gt2yujqbkrd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2orsgjrtk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2ztpmueuf.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2eqdsdpgb.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2bporfdwc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2gdbuchyl.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2mckwbowu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2mpsvbetq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2srqgfxcn.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gt2kqbzdsmb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2glpwefre.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqerlpfn.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2aieplrbb.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2ekloadlu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gt2asmeyslk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2lklxxydv.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gt2ogtcspzw.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gt2texqqijf.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gt2yvorgklz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jisohqic.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2bvopmgjz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2dfpyswdt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2wvjrsijo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2rvahphku.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzikkmad.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2oxftgvfb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gt2euuwmfvw.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xittlale.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctejyqmo.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trdjrpar.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2sdyyfhoy.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gt2daqncqca.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2waolvary.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2ngxoopbd.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2pqdeywbe.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gt2hutgxjte.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2obczkeso.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gt2ievaknal.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gt2azxndhnf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gt2mttrxhpj.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2pttfwcug.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gt2cbkfgylk.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gt2lkwomlgr.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gt2scnvwuxc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gt2vthwzpfr.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2valrsofk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gt2qgyhpgym.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuycflgz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gt2pfjfdihc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwwkarbu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gt2wqulbhuk.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gt2rsfywgyz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gt2dqbtyurp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gt2hvdrvjku.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gt2etnwphoc.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gt2kbmikrkp.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2xxmenigg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gt2qkznncit.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2cnhvzbjc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gt2kddvtvry.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gt2dhwzoeuu.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gt2odqfzyhj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmoodjjs.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gt2zlwuyiuo.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2dtxontmq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gt2bkettmvk.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2flnzyoav.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2wrpvlkls.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2zyfosamq.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2xocuqahv.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2fvvraloe.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2nxhzlltw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2mjcxyrzv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2jqqlmacd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gt2jsdyjulo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2adrkuhho.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gt2ggobxbkm.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gt2sejzidqw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gt2hhapongu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gt2itxtinvy.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2aqzepeni.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gt2kkilyzuf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2amlgfspd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kflhqmrp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwfnthms.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2zzuofouf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gt2xnqjrdis.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2bdcqplpx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyreboag.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2fkzvdadd.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gt2srljwwxd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2dobrgtvj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gt2yunhafox.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2zlkbdetv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2acbanknk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gt2ilfuiqcv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gt2mqhsmkvj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2qbdqzvov.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gt2zrmsoodw.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gt2qwxxmhec.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gt2mxhhlyfz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gt2gtxxpzbh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gt2gisuwfcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gt2pyvyeaco.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2oyvsegto.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gt2vemntooj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgxbelfu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2efbucpyh.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gt2aduebwgp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2hqdiakzb.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2lsbjleau.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2adrovmga.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2qcvbikcr.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2uquxvubj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hphzyroj.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2lphkgypi.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2bnrnyjtr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2omkgikmz.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gt2obuwivhz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2dwmtzydm.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2jhwgfsyv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gt2krdrukaw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gt2opsezhpt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuhplneb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nytypigj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2eynopqje.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcnsznn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gt2ldvgciws.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpuylimy.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gt2anuoyymt.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvvvqevm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2hxxuwkpr.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2ofvyzncr.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2rzkvgfsc.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2bxffkryn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2buipidpd.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2kenewmos.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2ktqaisyh.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2wjoedaii.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2jrqwactg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2fpojhqvn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2cdyfmfpz.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2cqgavier.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2aochrnni.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2xjcotkli.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alzqwlhl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gt2nmemyghe.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gt2lmrulzib.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2djjtqnvb.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtbfmoe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2eslfkivl.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkqifqfz.html

Java: s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2jlweykhn.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2mvlzohgw.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2sosilfkp.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2zfzbkitw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gt2jptspmcv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2ltsnbxcb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvunxdjx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2ucvgstmn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2sgtltybs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2yacrrbum.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gt2nuvowged.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhapfmvb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2zxmfseei.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2sdyzzxsz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2snjxtozg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gt2bgmutful.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2nfltctkz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2dgjrufkw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2qvntzecy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2tyyuiued.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2qjivjpwk.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2eegpyscj.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gt2fzruvazn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2hneslucj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfwdgdar.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gt2scvddltl.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gt2zmcsqqrn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2mczpgxvp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2cgspsstl.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gt2suguucli.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gt2yrzxrylu.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocxdmdsx.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gt2immetbxh.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gt2rykqxggt.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2sihoqxse.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2yfxhojao.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2odfymijw.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gt2mquwqlnt.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2nekobxrg.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2gfpfowyh.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gt2wllvwitq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gt2cmlysxib.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2obrkszuw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2zfjnqqvp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2imqmrywj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gt2obwidozj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxinbqmf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rduqswwq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2unkyspwv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gt2pfnmqfgv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2suzwwtht.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gt2edlkzeim.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2kebkmjdu.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2qgnmnftj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2horssaxr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2akycmvnu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2fdajdoic.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gt2zhwbrptk.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2febjihrf.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2yuabewte.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2azzqsche.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2sljugzoy.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2nvdnvmby.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2xtcuqpyu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gt2npqzbmhl.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2yyjrcalw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2uoonrarb.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gt2wlybcfsu.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwtuymsn.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gt2xnunrwes.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2gwoowygr.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffbbjrcp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2azimgzyl.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gt2xifakido.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2szfbbeek.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gt2vzopdtpj.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2szjwvlak.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2rxyscjkb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gt2smhobqdb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyhuqyxa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2fsxjpwnr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2hpgwfuky.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gt2usggwtmz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ouvkqsae.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2mwydvlya.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gt2ghturcdk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gt2nonzwewa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2laliftsu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gt2jzisynvl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2kvtgmsym.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2hzyqahuj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2fhqwmvtw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gt2rxembcfn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfqforib.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2ygdyvrrv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gt2wuzjklqq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuplphkx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2butxevia.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2btgvgylb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gt2dtvluvpo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2wmnybdqm.html


<!-- 参考信息 -->