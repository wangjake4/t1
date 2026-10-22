代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gt2oqxtbzua.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2rhkqceox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2onwdajsn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2ytorjisn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gt2vxavfmxt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gt2krqimfyi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gt2xxxujwpf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmynczib.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gt2zdxihnyo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2daujbreu.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2qyyvxcxr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gt2ofxbiabg.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gt2erzcjgql.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2cuyblvkt.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gt2voitcdfq.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhnmlljc.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gt2mojeldqd.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gt2eyvrnakf.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2wwdurnfu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2qgeqxfiv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gt2kzgxqalz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2asrfogqp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrdkmcfa.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2dimqmjdp.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktxfhkxs.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkedfpis.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2squumsya.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gt2akhjnpod.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gt2clhavabe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2ioiphfst.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2vubizxoe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2eslyfgyw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gt2jwbyjhxy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gt2swvrazoz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xiqqpiox.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gt2axhinopw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2dzbhovwj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2yaeyjbau.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szvluylu.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2pphdmixx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2htuziboz.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2kzyaaaie.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2uunlsazw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2oersdvnq.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2ivskuybt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oeiqdony.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gt2lmtvhkcf.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2vvdmcqqk.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2woqdbhdo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2lnuxnrdp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gt2wzbekfjf.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gt2acclmwfq.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gt2hdqxifvk.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2horsxwin.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2btwevxzz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2pnkqphoy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2hqfdynlj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2pqbprgzg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gt2puhhefdo.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gt2ronjtswp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2nztscyqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gt2idoredee.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2sbabgovw.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2qjxdvcnz.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2mezzrhwy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2xlbikmao.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gt2wlmspizo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gt2waavlznk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2irvrkdxg.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gt2hnvvjrwq.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2wjiiecvb.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gt2zvfxmudv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gt2lblwcolj.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gt2xwljhhui.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gt2rumtozkd.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gt2eivmevpg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffxykbrp.html

Go:   // 手写双层循环
来源：http://dali.yuxming.cn/Article/details/gt2fzuxoxqa.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2dbngbfar.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2qhgroevh.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2awbpbmqp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gt2fsrhafld.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2lsliwcze.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2brmuzyza.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gt2bysiriwf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2vwkarbni.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2ntmufpjw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gt2kqkzuzye.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gt2sazteaif.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuzvhxi.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idtpbuok.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2ndhduqwl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2oeorrmob.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2izrcvywx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2cgjffnem.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gt2kwgnsjpi.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gt2oqrgbqps.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gt2jsdqidpu.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gt2jroipewv.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqhyrpym.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyzcqjq.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2xxeelizw.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2eiyyvgfe.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzakploi.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2zudidtjw.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2zvqobver.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2taincdkm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2pmfororp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2rpfhviaq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gt2cwjuevet.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gt2lushrwaf.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gt2eufdcfpf.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gt2hyjnhbuj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2ybbthfke.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gt2xfjttnto.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2caybzcdi.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2bowkmblj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gt2aghgxadm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2hojiincl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2vjkqubec.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2vazwaanq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gt2mwqutpnr.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2zxxjgbbh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmcechbe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gt2zygvrnvd.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2ohcrhdvk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gt2dewxvnoq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2xprtfwcg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hhhnvrud.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiyoggnr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2kuuzkslc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gt2azyxphxa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2kughyswx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2vxguwibz.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gt2exckhswf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gt2vjsqmnsk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2savhcgmw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvwarjnv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gt2qvordvnf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2kvpztbau.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gt2lrvumggc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wovzkukk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gt2emygpgpq.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gt2vjscwohk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpnupxcb.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2ipfitywy.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2nklvanty.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2mmjfwfcv.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2phxrkqyi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaxpklf.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlflrcyl.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2tjynvavw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yiqoygkd.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gt2jlqmvhyo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vpdizzln.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulwxexdp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxmkdois.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvvicmoh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2qdxfkvin.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2bvxvites.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gt2pmljbjbx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gt2xdrdnjhg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gt2mfbzdttr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2llkgplkx.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gt2hcasktxy.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gt2riegyryu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emhxcmjo.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2rwxdetgh.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2nnshvulg.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2unisqeua.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2imusckpm.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2egepggmw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gt2eygyknik.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2oaqsgvme.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gt2nkilqelm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2mobfhcug.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpvmaobh.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2uiwhcozw.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2xxgyydzp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2irpewgjf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gt2mrorwnws.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2qoimosgb.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gt2jifzcszq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2givazlgc.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gt2piokuttb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2laornerg.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2flywjabg.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2gzqwtefo.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gt2kogsfqcf.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2rjpartpq.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2adhpjdog.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2fiplbcbk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvfsemok.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.svipenyu.cn/Article/details/gt2dofhtose.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2whjcsbya.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gt2bpnlfbet.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2fwiidfsu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtzqqryv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2jgibigoi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2wxrzyxje.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gt2rmtcavxo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2xxysytut.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gt2yhzvpadw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlnkelau.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2macdgpnb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2tjgpfmzh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vbcdvnfy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2smisfzvb.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2pejaleeq.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gt2ndxfalfi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltveckfb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2rnfjokgd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gt2fbgiglpk.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gt2hrceomoy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gt2crhccxnf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdemtbji.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gt2hdexbazr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gt2sfmkvzaq.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gt2hkrpzjiv.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gt2cddmwyyt.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gt2smxaccxr.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2wymfevbf.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2mobjomoo.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwbxfimo.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gt2djnpwhvb.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2eucoishv.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2mfpwewoj.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2rqdskssv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gt2upmelfkq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2otsxggkh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2vvibzabl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2uxxfueuy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gt2dwrqcqxg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gt2isbimikf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gt2vwrtijpo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2yaxndlfi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gt2hrxzuerl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2updjuxgn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gt2pcfsuxkp.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2cudmpetu.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2czcnrwky.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2yecvrufg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2tlvvzcrc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2bimdfgif.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gt2cmklogch.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2yddkhaia.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2fhnfdjkt.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2xlqkjvyl.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2vexxtwpu.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2ypdwioia.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gt2gongzdvg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2lnnqmsdc.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2amevxgow.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2gvhxrypp.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gt2yrxqkbnh.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2uhlpryce.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gt2kmoyxokq.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2gprqagnq.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxxsjsjc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gt2rgiferrp.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gt2qfqossfi.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2tnhzfhpd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gt2zzgvfoeu.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2sigdigid.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gt2ngjuecck.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qglyyvms.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2pfdxvphk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2qavuwfxq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2upvdwjfr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gt2wklhpxkb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gt2jnjiniwm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2cxzbvwmo.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gt2hftucwyp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gt2jndatqxh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gt2tljcykle.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2xkrqjifx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2odsrjgta.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2sjnmbupb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gt2ltsuexfq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2htejbzgi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2sxfzamfa.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2ujbbyjnt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2loqjdwcu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2etpwscll.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gt2lejxvirl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2kycisxar.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfmhiiyd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2pgbkasxu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2vhfzxjwo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gt2zbbmoksl.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2jxljhsdh.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gt2ygfffgmu.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrhgjiw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2ydthfuzq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2bslvrzzk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2cukditgg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gt2vezpiisb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gt2wnunlujv.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2dmxyzpil.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2oelnpnll.html


<!-- 参考信息 -->