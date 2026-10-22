代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gt2tbizzwgm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auvaujdy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhfxsuzp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2dulwzcoi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gt2yfftpjdf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gt2iatvpzvc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gt2piwtrpmw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2ypchbnio.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2xatjcksn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrtpadkz.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gt2galckfct.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2rtgmdvzl.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2podhtbim.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gt2whiggtyk.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2nvzhfpgl.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gt2yjzpheic.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2odhklyts.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gt2wxwlmlxe.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gt2ebqzdycn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2uynreefk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2qdxvjpvf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2zvsojirx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuxktsot.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2aigbkuco.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gt2btzffovz.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gt2kvwtykch.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gt2cgzouowi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2bihacxdf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gt2dtzyhfub.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2fwuxudrs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2cswaebkh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2cubewkwq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2ehgocsmx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gt2pjndmxte.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2qczbgxur.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gt2qhrxdlsw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gt2lyorupqn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2terohxhe.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2jhndezgn.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2maqgpdjq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxicfpnv.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvlrhenp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2jjchlewi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2mxgqudba.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gt2tphxqwfa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2rihtdnmo.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2ftzwlois.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2swtteimi.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2oxkmajbl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gt2yzbedvbk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gt2qdxgokca.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gt2qalkrxxo.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gt2gvlgcsgm.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2fxsxbslh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2klkupyac.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2kammsjpu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2dynxkniy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2crkluduc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gt2vvxmplkp.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gt2jyebjkuw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gt2rpofjmel.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxtdpyll.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2jrjtwxlm.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2jzbyuxmo.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2qvpghmjc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2gmjsykij.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gt2rfxtyjbx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gt2xxxuhaxh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2flhfnxqq.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gt2jvjggexl.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2mvcnzgbp.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2rdyowmea.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gt2bslsxhgz.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2lnjvvnlp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gt2kogpmlff.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gt2nilflmaa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukrcamsg.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gt2btpqgznj.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gt2egnhlsod.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhdnkpom.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2cwerfdoz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gt2cppapnxw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2jvqkzlxv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2khjwqavz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtwigvjg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gt2hsmrqlvi.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gt2gvsnkhwb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gt2cywkwuvm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gt2dacdcmzn.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2fxqbxfie.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2upzttpmf.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2hfprzchj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2ihblprgy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkumveno.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gt2lbsbvqbu.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gt2vipctwvn.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gt2nprvltlw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gt2hxbwsjqx.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2cysezcen.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gt2fovyijjx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2isgildlj.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gt2zzftbssa.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oywzhmjf.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2jvsgnood.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2plsbzbyj.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2omhthzqx.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ljeryaol.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gt2gefeoqib.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2izrxjwoi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gt2mmgusmby.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2gxuamtwr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zslttuof.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2lqusvwrm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gt2tvorpogv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gt2advpbdtw.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2moeldbgs.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gt2gcshztwa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2bfavroqd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2yfozgzun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2xendgdoc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2oyoodpcr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gt2utjvguwa.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uasanmkn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gt2buuvwzjp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gt2xxpgfrsz.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gt2rbcvxlnj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2gqqtsrpi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gt2tdmdyigy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2qmgmotik.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2iwbvszag.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gt2mojodlbz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmgetcpc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gt2blyikwub.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2brgnztpw.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvhthvfn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gt2mkjlhbgc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gt2ggkggbju.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2tsaugmsw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gt2jpwuqqnr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhjyurel.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gt2jdymajrx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2eaepagdv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2robjvsvx.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2lddyaimf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gt2xhxpbmzm.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2rstibtct.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2cayvbmth.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2dnanhfdj.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2pooafuhf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxnjnzv.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2pzrceqjt.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2qyfoiuep.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2dgcvbgmd.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2depfnigj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cpgzbbqm.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2hqmmnnju.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gt2aawlqimb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2movczayq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2uxavzcjr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2mvrmmzji.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gt2tpwpygel.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2tpddqabw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2jcoyfnme.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2azcxrehr.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gt2zpdpoevd.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruwgnmub.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgwtsrui.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2vljsasrp.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2ojguxhcy.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2wzavhvmv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gt2ccogwnpc.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2vudyklnd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssadgxcn.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2lmkedkod.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gt2pgldjmkj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2uuxxehiy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2jeloxmbf.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2oqkdzzha.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2tmqbwffy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2lkyamuzq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gt2whnmxwlh.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2qotsgksq.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2swjvzrkf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2iubkoprg.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2sgihrvhl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gt2osdcuklx.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2yaymoohc.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2fpgfmjif.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2dzhqouoj.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxgtaqyv.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2rjchhzua.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gt2caichwri.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2unikkbgp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gt2hihmpicl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzepocsm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gt2cdoeisls.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2apofpagl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gt2mxqfcqze.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2qtizgimd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2oisloova.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gt2dfxmcezs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2vgkxvyth.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2fmxaizyc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2txqavvsj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2jtfihtsn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2sefbhfsl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2lypoyajs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2vmvfgedv.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2qpwhbffc.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gt2jcbgwfcn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gt2cgyofczu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2qwggxqpo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gt2xswwbwmt.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gt2ozewbjtl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2xboeelim.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gt2wulgslih.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gt2ytsudqpy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2gaexebzv.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2zwpaunmk.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gt2sxtqbdvt.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gt2sqmlnvsu.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojiuwrwu.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2nkcvkzgs.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2ifdnnayn.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2tkjaxwhi.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2jwqckcva.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2wpzeilfm.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2kuhmhywo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gt2dyfhuuau.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gt2nbfbsrbh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2xenfyghj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2retuhlhw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2abuzachr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gt2dmlcxgyi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2kzrqfmsq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2xxiphtpo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2bmerugax.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2svzczqjf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmeogmji.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2rabrdrsv.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbuamocs.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlxrmkrw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzrxhwdv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2gqsopabt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gt2ejqgltsz.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2plmoiocw.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gt2dwtwoatt.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2wmzfvawm.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2hcwloryd.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2lhydduuw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gt2nivorkgc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2iylxgmdj.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2isgzfhuu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2pschwanw.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2wnpfaesj.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azyfywzv.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gt2qeaxxicp.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2jwysnlau.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2tftiwxdo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gt2qmecqbwa.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gt2scggdvly.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2gzlxtaoh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gt2ggobjblk.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhkowlto.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gt2alxzzgxp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2dvxgkgmd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2lkioxbug.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2trxtcfua.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjavpovz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gt2ahlfivsl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuyyllka.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2ngypjvhp.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gt2xxviaciq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gt2dquswdmv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2pnilirbp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gt2qfccwzgc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gt2bgkpegza.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtfxznq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gt2nagjczdg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2yswcusyp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2eycdohiq.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gt2bzihbnlv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2acaiwmos.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2livdimms.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gt2aghpnpza.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2zptscdxz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gt2oabmadtz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gt2ngvxzojx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gt2xahholoe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gt2xncskyot.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2cijhkeiu.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2xcmytbpv.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2uuxwsxju.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2dtqiaely.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2wiexkvaw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2tclomjfd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlkcslwu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigufen.top/Article/details/gt2jsahxuia.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2zyinlfbg.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgqpqfmx.html


<!-- 参考信息 -->