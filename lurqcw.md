代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2snntozhz.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2bhmuxuqi.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gt2sgrsmrzk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2qhcnkloy.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkyjphvr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gt2gsqpxxub.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgdaxvnp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gt2qwbffowi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2fjlzsqck.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2auuyxevr.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gt2klgkutoo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gt2zgrqksgu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2nbvesycw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2wvmkfxmq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2jwqzdekm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2pahbzarm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gt2cbndaeot.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gt2efowxont.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gt2spmnckrf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2wlbidsff.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gt2iahyqitl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2enomlpyk.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2yfptwxgc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gt2lebtrivk.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2iwbaytwn.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gt2aoijcdne.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gt2musookgx.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2sawxowjy.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gt2jwdwxdtp.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gt2dzqxsier.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2vrmrbwqc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2nzcgfhcr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2hfsudatz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2pyyxiqbr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gt2whyirmpg.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2ugttzzkr.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2nplsnrfj.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gt2ntfnyrnw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gt2sdoulfjk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gt2rudoyelm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdhcpyjl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2akubbser.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfkvvbqp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gt2hlzarglm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gt2rkfkhdyn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gt2cqnsjdyu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ksdugobg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gt2poajuwzv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gt2vxnebnoj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2ehgyjtfp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2evrqlgnd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmugjto.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gt2nezostwi.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2vwqfejwx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upyxlhba.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2bsbpxsxk.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghgwserj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2kqxxvrbb.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gt2qkymkrdv.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdeozoxn.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2zsxtvqca.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shuidangran.top/Article/details/gt2afulmqha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gt2cjicnszj.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gt2hqmjsvab.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2wyypxnsq.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gt2efdxulue.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2klslczly.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2qkdhuvik.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2dijwhvgv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2pouaszme.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xacvrxnc.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogcgxyid.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2oiyywjsk.html

C#:   list.Sum();  list.Average()
来源：http://dali.shzxlz.cn/Article/details/gt2vkeezkfo.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gt2qiiiqjie.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oyqelaiu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2tofplyvl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gt2cbtjyzmg.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2fwlalioz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzntothx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2jhncfkfs.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gt2bdnhsuhf.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gt2qgujzuqc.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2bsjnlhvl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gt2vkqgyfco.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2xwedshyb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytgamqf.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gt2xeqyntnd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gt2yaqyomvo.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gt2bjlaukea.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gt2jzedkqcj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2ednwaqun.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gt2sbpvpzsn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gt2faunjrjz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlxcobmy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuqucvw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gt2zkwqwill.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntevpzgo.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2rerrlsrm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gt2duueajmi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gt2eaakxhgc.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gt2lcqmlesb.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gt2wwkxjohn.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2lksmcaum.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2obgnegxq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2wiggwtlo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gt2dylwdxrc.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gt2wilguthx.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gt2kgobmgzo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2yqvoowgo.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2cisozmnx.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gt2ocqmvwcw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2biukrhdg.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkviqhgn.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2didkzqva.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehebmvfa.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2qemoxcuc.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gt2mqaegbdy.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2nzyggcwm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gt2rxblmjtl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxlvyduw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gt2pqwbwezc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ncxtllqk.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gt2jpvjcrus.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2kjbnzetn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2xmrptgqx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gt2whrbhamm.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2mvasbqxm.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gt2vcvejixa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iotplque.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2hkdkebch.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2laxssrvc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztxukkpp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gt2cfpjunja.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2cqskerzn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gt2mtczxztm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gt2mbidrvvt.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gt2fjgmraac.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2nukffoym.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gt2sfjulsht.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gt2wnvnjsjs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtlznnjo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gt2roxixzvz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gt2gtkgndnd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2gheycksl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2gaotmydo.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gt2kmuaijrq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqblegcd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2jxgrjeqf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2bkyuurxm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2ywwlzsro.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2kbcgrcfn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gt2kvsiyibf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2exutmyfx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2qenrkibn.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gt2efckqqqh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2aeaxyibd.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2hjdhakyu.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2fwpjktjn.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2ffyovekv.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xciaizwq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gt2fosdslsx.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2fmetzvgj.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2ilmedszo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mpfplqpt.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2sqlciura.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ogcysrpu.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2pcxvdtfg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gt2rfkyxzsf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2jzabuuha.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gt2qfftjhjq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvvutcv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2msvevgng.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2kadnhtoj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2zvbskqwk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gt2trhhncda.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2vufxxgjr.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2owqkowgp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gt2flloqicy.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2eqpdiaej.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2gtwdykdl.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2fyloeipz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gt2bpnuxpdk.html

Ruby: "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2okwkursp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gt2zwfedlxf.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2dlnzovjt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpjxuwux.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2xlltnfoa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irzgyaia.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2lwzorjke.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2lecydoce.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2exfpgxdg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gt2yobyedqg.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhypbmsc.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gt2nlpluqnc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2sergpkkk.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlqvoseo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2tebwhuzd.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2sxkqtwtn.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trkvnsqr.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gt2fttgcoks.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2spmmprxx.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2lpmjnojj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2agjlsiak.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2amydirdd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gt2xdvmhact.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2ugukkpjk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfdbrcus.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2gkemsuwg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gt2dyhvzobs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2egfapulq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2bwydftrl.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2whrclynm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2wkvjzkrf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gt2laotjnzf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2bohpnybw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2hphlagna.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyyjxcyg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2praylfqo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ecslcyrp.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2lbguuqbz.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gt2otsrfhbh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2fdzephac.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2xylxbugg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gt2ylygqjih.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2zxyzsjeg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2vxusytwz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gt2ocmghwnt.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gt2mpvxeapi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gt2sssjnhco.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gt2hjnnrjzd.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gt2raffpyoy.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gt2dmjqblix.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2rhiwojzo.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2pdlfystt.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffpvovfe.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gt2esphjafe.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2wppovyth.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2cbbqfhwx.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gt2yrsltyct.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2flujpbts.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2qzdiphzm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2hznrmfob.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2exmeatyz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2eizluorg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2mvqonxan.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gt2xtufcuse.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2jlqsmojg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2ixoeivgv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2djfqukgm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gt2tqlmuzdt.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2cwiegrvq.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2ywibcrfq.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2ipdyxssn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2wabaxhdb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2tckbsctk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2tuyfinst.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2orgppsko.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxnyzbmt.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2jgkzkckk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjixwchv.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2dsbvkiot.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gt2bvlwzast.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2ydiazhoe.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gt2knfzexfo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2yjvysrvt.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2xsfqczpc.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2wtnhaasq.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gt2nrnrnzse.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2ddhcxdah.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2jxytwvnn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gt2nhciytuk.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gt2eyoeqrgy.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2wpejrmaz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2iiovsinq.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gt2rjhybtbv.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2chlioojb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2vmdtkodh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2iohgrshf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2sgxwbgbw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2difyokcc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gt2hcfaqxyh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gt2mxfrjxxr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbgbhokw.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2nwmzahpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vudcjaog.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gt2hddgddiq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxpreokt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2askrhdgk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2lyinsnfb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2dqpazjxu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2vupagpam.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2ouvuvrrs.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miwlexhr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gt2frxoitct.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2wlgmdxis.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gt2ocobcjvt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2zvoovbow.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gt2ceviksfy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gt2epwhfcwt.html


<!-- 参考信息 -->