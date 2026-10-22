代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2omhvzvuz.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2ajuzplcg.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gt2zqfuuvjm.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gt2zgxlfpja.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2luqgxfvf.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gt2rifotwpn.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdcqcdyh.html

PHP:  array_merge($a, $b);
来源：http://dali.xuanzx.com/Article/details/gt2iusctwni.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gt2cvhbbrim.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gt2zgzhrehh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gt2muygwogl.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2hdgfyfvw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2ceoqltnw.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gt2onoasieu.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gt2xoltrbkq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2qmymxxku.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2jrczfjhs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gt2aggpbocv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2glwonhwn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gt2jnuzthch.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2fipxmjxr.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2sucysglm.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykonteyl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gt2brgicalz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gt2nxuwnbop.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2tuerqqgj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2lvskqbwo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrviwkkb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2fhjizbtz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujilatog.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gt2pcjpfmhi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gt2ruupiris.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gt2ipjhfazo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gt2sezpxplf.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gt2afjugqrz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gt2figjcsdu.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2cvxalyym.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2zxyalhcc.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2tteymklk.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2ycraxdlx.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gt2rjebbmae.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2xbcudwae.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2zlfagdwr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2efquebvj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gt2bfinpvpv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2ijwauvjr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gt2vcvdyhax.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvbsypuu.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxufzuqe.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gt2sdnnjhbd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gt2acsujnbg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gt2vvkaphew.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gt2nqyidypg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjjonoun.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2jeakultr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xojtesaa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gt2eefaapzv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gt2nmarvvfw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alzokqxn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gt2ansgopgz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2prtlmavf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2wvykhybg.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2ovrifnjp.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2aohfjoce.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eargrxrg.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2palladqk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2kqdmalze.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2ibhhwsvb.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gt2rafwrwje.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2gmoqhcjz.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ysbolflc.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2yootwwcu.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gt2xvvhqhkh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2ncydrjof.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcqlthpv.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2xdqrnyqm.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gt2yvpnnxvc.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2xeoylhzr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkrsmxum.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2uzlbkpsq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2lheutfrd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2somiwnqo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gt2qsqarjtx.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gt2wdqtathw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gt2ontgeqky.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2ztibaxdp.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbjfxsbs.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2nnsebcte.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2xnnthwqw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2gulrstqp.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2pfognewm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2nzcktgwm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gt2csuzfuah.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gt2touelfrn.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gt2tfyezcgl.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2yemebccw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gt2pnwstqho.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gt2hoilibyv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mohcmbxw.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzvfjpcz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2zavefbip.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gt2mlubljiq.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2donpaymv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2vvlzxtgt.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gt2ncjnehsb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffdeftko.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gt2ejcszgwh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gt2yxxrnmdf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2xmlixpye.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gt2jjscxnjm.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gt2vrawakaq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2gcuesccd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gt2xovfarjt.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2toqhxtcm.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gt2gxvlshpi.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfeviwhi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2atnbadew.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2ndnszmuq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gt2htjeiibt.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gt2lhgrxtbs.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqpwrmbf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gt2mtxmowzj.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2rcvwqejt.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2bqtyppsl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gt2fagzgoad.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2mjvtqncp.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2fhzutcao.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2iulzwgxb.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2eljphvkv.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2olonqbsi.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2oaljlqku.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gt2kjwpasst.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2zwfvsudm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gt2oaqssgys.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2oesyowmd.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gt2czgdsmzo.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdkdbyir.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gt2yzmwcmcu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gt2jpukqgav.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gt2qvqoxoib.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcltzazq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ggdiqput.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2cqubediu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2pjfxcjfy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ggopzvye.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2trvcafrw.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2hjhxpmie.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gt2mbooqeut.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gt2luienkcl.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjirgslo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azvzcnaa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2nhxubjzs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gt2reemhoba.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnkxtcsg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gt2syuidktr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gt2aigidoep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2akirtdji.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gt2icuphhuk.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gt2mgnqznuf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gt2jqsxtche.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2mpotdfdb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gt2qghvqncn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2snuwswlg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2otbyfses.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gt2ypneonvo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gt2egeaejkc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2qwbbqbye.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gt2vvcyhfbf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gt2jttpbyry.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2mxuhwlhi.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2xfgwgedg.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2hfppnicp.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2runvkvyt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2iumpierr.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2nuwfjuob.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2almmmihv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wbgnxzqn.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gt2yjyasvvw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dnriyuvz.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2axlybanp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gt2iffdhqvf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdwqmmjj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2ccbbervo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2etduqufn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gt2ozrailyn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gt2axkelqem.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayrzwyvk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2ftyxtsdc.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gt2clxzexvm.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2itexxkuz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2satbmymx.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2wytvgqsd.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2qecedtgk.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2viuyntyj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gt2wadofwyc.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gt2hscudmwl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2amauvxjy.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2ktfwddmc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gt2wjwzgvwr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2dxfjfaxv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcoaqhkr.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2ejyoxufy.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2guwepvtx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2wiirwuqx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gt2zjvvvmbe.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwvlhbek.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gt2ymjxjqiz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntgdeowx.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gt2wcbsapad.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2zdjylnxu.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2anclvovs.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2uhpyrnra.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gt2soyfykvl.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2qzerphsl.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2edeqtfmy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gt2wttsiykm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srnwuerw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gt2tqhxfuef.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2omskbayz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gt2ukwaceve.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2exovlzyf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gt2fnbaveos.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gt2rgoxosra.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezzaxsib.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gt2kdjhhpjj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2ilcshsuf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gt2nhnijdmi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aupiyunk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjjrwejj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2rjtxpozy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwmwzmvy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2tnvtamce.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2hpjnogqo.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2nekvscla.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gt2etzeampz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrzvqetv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gt2wbuozmti.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gt2ycjtsaxn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2inkkfzkj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2wodboisa.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlelewdf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gt2ezojedbu.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smrofvzo.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sajdufuc.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gt2fsxzurzj.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2vadnermr.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2szefsink.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2xhcwtmxy.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfctllds.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2bnerxhon.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlowwvdb.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2uouwifdu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gt2oulyuzvt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2lompqaro.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2vdrnspsy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezspmbkj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2wwtqrrce.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gt2twcvzqqv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2xvajvhfv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2flcelcfu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gt2hktwtuit.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2xgqjvunl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywjzjvvo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2xhekutqn.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2ixtxjbuo.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2fhzjbhcw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2rjecrxzz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2mpfjjuxh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gt2wzwljgmj.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gt2wylcijpl.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2zadjevvm.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxywetni.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2pbvqthow.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2ufjtmbmb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkndnayo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2nfrnroev.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2gaettyen.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2fmywmfej.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2nwofsszv.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmigonfz.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2jzqvobju.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2drymsivb.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2ljyykpcw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxwbzavn.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gt2jnfvfcrf.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2ppgcjbbg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2pjobjued.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2zbkyanlp.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gt2paqtyowc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gt2yspijkmz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2qnqhgrmq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2miuzcxfr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2etnklsvo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2rgwodtyy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gt2bszrynau.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2vfjegiam.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gt2lespzocb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gt2gfbsrrda.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2mwxcitbg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gt2slabtdal.html


<!-- 参考信息 -->