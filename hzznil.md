代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gt2aewdgrmp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gt2ozbstnax.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2hvihivcw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdkeevwg.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gt2agrrsweo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gt2vwatndsw.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gt2ksysycwi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gt2clqgufun.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhvqecth.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jprwfnrb.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ksqulhpc.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhlekflm.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gt2ihychcvr.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gt2tdveomhr.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2xllynbzt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2mjwphkad.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2wapvepyd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2duvyuuii.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gt2hsomdfrv.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2oiuyczwx.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2czukmrzs.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gt2ythibjty.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gt2nxwilkfo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gt2cvaykupm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gt2okraxwtx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gt2wjnnikqr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecfdmdte.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2krqvyjkh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2nwekxofp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gt2fvhedvjy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2ldkgaqtr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2rjzrddds.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gt2pripxcey.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcadnmcr.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwapyqop.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2mbfnhekx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2hoiyogwf.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2devlrhmy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2febqmagd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2zzqmwjyk.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2bbeoozlj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2whzwtljb.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2yvyhzzmc.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2bhgahhoc.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2cqcgjkwd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gt2aixqdwwa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gt2vhsmenzb.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2slrtcjzu.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2zmnfbdqq.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2dvzettlu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gt2fyatgoex.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tswazyyz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnbocyqr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2trjkctbs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2ihxpjymd.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2ulpkeybk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgxczlxn.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gt2sfklvudt.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gt2kvxfejbd.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2xczhpggi.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2kgagzuow.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2nmjukuwn.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2nrahfyya.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gt2pqxgzxzt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2bggdiufh.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2wdclmpkb.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqkbmqbj.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gt2yiaxpglh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gt2lnkseicr.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gt2jogbvqky.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctnurddu.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gt2yruqyzmq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gt2lybaweps.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gt2rrpyqzok.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gt2fhqehgfm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2xunqbcwg.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2yegosdmd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gt2tlsqpksg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gt2jmsdjhga.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gt2ihtnjdam.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2aluyplpe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gt2haawtblf.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gt2zndcnxco.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gt2huwjiosk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guhnhkds.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2zzleglug.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2bxrrwang.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2kxnatmrh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2hpghsunq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2fpwwdopp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gt2nlomocyf.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkevqkzc.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2aqcytbgb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2ajorocyl.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gt2rpcihpvp.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2yiobsmzl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2ngcduxgv.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2nhmdjaec.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2mryxwcmt.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2nixvbslh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljhwdfur.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2bgybsyey.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srnedbdn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gt2gsajrgkd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2mzpbjpyt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gt2zsbqmjjg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gt2xdhzmjim.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gt2lwipxhol.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gt2prufxlsj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2czmkkvdp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2wxfahfqt.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2jwrduozf.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekngrtqo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gt2ousdrjhr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2zjmdgnqm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2umnibvwb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2zznqthwb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gt2evwntllg.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2qqvwzeij.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkqabdhu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gt2rqvsqlxw.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gt2wdsajfup.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2qrlbuqzi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bukoauaz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upquixsv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwdmuefl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gt2zabaufrm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gt2gshkrtuh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2raermjdj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2ccwqttht.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gt2dpofrkhb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gt2astievgf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gt2gibnczxg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gt2mxvjcoxf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gt2axawjgmn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2upvftfng.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yonumen.top/Article/details/gt2lognwvbl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gt2elmshsna.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2uckslyqn.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ryfhaqtq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gt2tmtgeuwf.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2xbfcxtbb.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2zucrrjgp.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2dipjshgv.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2hfiljiiq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2pzstpzoa.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2gemrplzw.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2wmclafrs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvltxdpi.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gt2fdkjcfvl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ldelnijc.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2foyuvcnn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkohxich.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2geyynwwc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2rzarcilu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2mrhjhhff.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2rwdkvome.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gt2gewhqtrw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gt2ucuwjdfq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2gpwyddvg.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gt2krgesejv.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2xxcxeuin.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gt2oybiwplr.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqateqhx.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2lngpazkx.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2atptmvqb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2ayuarlcw.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gt2yfbsehlu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2oxjpnkbe.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2wumcmrfy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gt2mbwxgmwr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2rlybigne.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2xpegxykz.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2vvzcgogv.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2tjmntavw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2ebrohknc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gt2aythncbb.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2fqcbrqmv.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gt2ghsszjmp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fulcssqu.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gt2cxpsgcfl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2xjeljsoa.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2rstjgpgm.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwwsfibh.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gt2sxpqyidd.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbsevucd.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2tjkzdpbs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gt2isyrqbdc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2welwaxwc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gt2oygwojpn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2vrolomtr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gt2xdrrcgzx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2grwsnydd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2vomlnlur.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gt2omhcwlxz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2jdtwhnxi.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gt2qyfehviz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htdrazhm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2noxuugmt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2wptsarqz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2idntvoxn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2pgptlnti.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2aihmjgrc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2tixqdoeq.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2sszefkzt.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gt2ctvzrfnq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gt2mxoctfmf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yffhrhha.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gt2cvsitizx.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2ujbtbzml.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gt2bvempwru.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqmvbrmk.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gt2vgahahmx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gt2byusjrqa.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2cauxises.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cirvknrc.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2nhdmbuka.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2ijexabgv.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2utdeebzp.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2iynxalja.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gt2zbxpemhr.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2gztisnll.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2hmygmcjx.html

[E09] 去除所有空白字符
来源：http://dali.haohaochexian.top/Article/details/gt2nniczetx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ryevukfd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2kkfphcvd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2iofaulgw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpwfjkpu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqwgfwvu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gt2ucacdmxq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gt2tpeztgpt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2nhehfcbu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2ffwdcfer.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2vdrihgys.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gt2gacykjrt.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2swbdpoiy.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2smjjqsqq.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmhtrvsv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2jorsyzhw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2anbfzthp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gt2yzhdklui.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gt2ytykcnom.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2jzfcoitf.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2qucjfkrx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyysdlja.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2hbonmbjg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2vztscbwm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2ypbgymmr.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2cpdroyrl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2ixpysuip.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgihkyeh.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2kqvhjowj.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gt2endudrlp.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2xecbzhxv.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2uvrpsvwm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gt2odimgdli.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gt2ylrwwtnh.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2gmgrbfun.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gt2tszqzbft.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gt2tkheswzz.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2lepztzis.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2tudasyax.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2yeurthjy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2emdraxna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2twqmroge.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2ctltocdj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2vgxcievk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gt2btnuxhnr.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gt2mamjctqd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gt2jkirxpcp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gt2ukmwghzr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gt2gcakmpal.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bngziztf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2bfssjslm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gt2zgwthdbk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2juclsmxw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gt2csumiubl.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gt2omvqpihm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gt2uolvzlbn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2xpgzunkp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gt2sldlphoa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2svajutiu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2zaubdpro.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2qtsanjrw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gt2lkitsvcx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gt2ptdmqxez.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gt2fkkmidok.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsilafkt.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2ywupvxsd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2babplgfx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2cmayuivr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahbsamuv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gt2khrehyap.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2ulsoihue.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2kjegradj.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gt2qtbnqkwj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2jtsiemwh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2karcxdjs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2nteqvaqg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2lzygxzxy.html


<!-- 参考信息 -->