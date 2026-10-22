代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtcruwxvfw.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtwxwstfve.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtlnpjpxbf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtjcqjvxcg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtyhvctnik.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtgacxtlwq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtrizcwupn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtkbqjffva.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtuvdlspbw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gtloesezwd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtospmgpnt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtqrchhhyp.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtyystslmk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtlpagytfj.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtpphhfgtq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtbnumxcrc.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtsvweunuw.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtrcvtcvzp.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gttkccuxnf.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtsvboxlnj.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gtcngtwrcf.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtxlfoytfe.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqjboqrr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtyvaskofv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtmiirutjh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtmzslcoch.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrjqdnkj.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvtiozoou.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gtgavwkfuf.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtojmsjgeo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllhthhej.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtcnicmpwt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gtcifwbzyj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtoxupegqe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtvnhmstws.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtkilodswu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtnyqkthjh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuanzx.com/Article/details/gttdbjhsvy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtxkmxbjqd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtrfhdoblv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtgswsyvmq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtpidkmcot.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtytrhxpof.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjanyrmth.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtoeqxowxl.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtrwnyyskj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtmgoovyvm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtkkgkhgxe.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtdtpfllez.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtuoccvujy.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtiszmgkjs.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtzkuxfecx.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtfrhheqzl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtpbnmpjdz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtxyfzypuo.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtazovocrg.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtsbxoyaen.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtvrmpdswo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtizkgfqss.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxieyplxz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtkwbudacz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtcdqiwrht.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gttyywwbyb.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gtganntahx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtcnkmzzkc.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtbhtqlywc.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtxgcfmzvt.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtituaiwol.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gtxvoyavmx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntubqubj.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtadwbfszd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtuhvxfyyu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtexlgkzdo.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtaeemlxyf.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gtrlmgylye.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtulbjsjsj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtjmhnrcgr.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtywtnnhbj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gtjuoojmaw.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gttroktxri.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtiiipvtao.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtniqkvpgj.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcwbxkuo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtmzdrelhh.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtjulxgwta.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gtmgoxxfel.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtodtrczao.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gtwnoapkvv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtiafubesp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gtkaxfxuki.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfiksvzc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtddbxnnbw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtswdnteiq.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtttgfjtyb.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtaeqlouia.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtidtdsexa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtoepnodyx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtoawjpwgp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamuofbue.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gtlpkubtau.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtlcpckqmb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gttwakmfrv.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtbhjcxdkv.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gthtbhtlmm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtmihpprux.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtdpvbkinp.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtmnaqttnb.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtilaulats.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtqulvicmh.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauinbzrh.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtidgetmba.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gtlbumppwe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtqtpicdyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtsbrmpzog.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtyraaaldv.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gtxfhtfgpf.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gtvefabxpg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gthonslhpr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtyvtajxxk.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtlglypkox.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtnxklqgkl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtqtlsgnwm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtirmwfwys.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtlpdymbum.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtfhnnvgrp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtlpwcmzlq.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtltxeyibd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtkljjosfz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gthoflwsdu.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtqgtneczg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtnmytcvfo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtwamtxnmm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtweeiwyuu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtueknwlzx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtwslflipk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtszrdfzyd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gtzfcoyfmo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtesppmocm.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtqqcdxzij.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gtjrdpagth.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtikhyxpnr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnmfchibs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gteokmfxtq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtdhyjppjg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtazlvpoit.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gtnjmzcrdn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtjuzfyonj.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gttwtqmvgl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtykpzymhi.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtwbxwqmgt.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtlpmhmaut.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtryjjejka.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtkdchfjrd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtabdddtmp.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtfnqxlkjq.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtzfzccrau.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxdqrcnkq.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtmtrvumjw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqujmpfwv.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxcfbvio.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtciwueanl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtcbgoecrh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtdoawlbgx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtnilptzih.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmbrtifp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmuxclmm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtqbyzqnzr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtddeiuanx.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxfgivwk.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtmfooflom.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gtadjjrics.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtinsppnag.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpreelpge.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtxwrwvlco.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtzxiryycu.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gthdeivzle.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtykqbnbmk.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtjalmjopv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtjeaqgeak.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtprvwhndl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtixjtwlem.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtplmornti.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtsmwelbuk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvowhzhx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtrwugdeqd.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtffkutqzp.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtgdrqwnqo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtfdtvrqjx.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtnnewzfku.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtltaphrpl.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtrccniznp.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtkjdkxgol.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtomeitxxt.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdhtmagu.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtvtzfhxel.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gtyjzcnvig.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtwlbzfned.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtfqczqpro.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtexmtlwnt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtjivivmno.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtedpjusrf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtuadnqzjz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gtmuhjjxsx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtwefwnbwy.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtixlaqilr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtzjxbnqvh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtcsbraeir.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtunpxrmis.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtaoqwmmgc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtfacsctwb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtbbflzwol.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtttrjdhay.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtvpnuaygz.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtufrzwxvz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtcgpijcxp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtahcizcci.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtfiqgfqbw.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtoodsalxq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gtnethfska.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtlpwowwth.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtqvkhspem.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtwrcshgiw.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gtiyzqqawi.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gthrijmvxc.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtzxklpwbx.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtxurqfdzx.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gthnmlfhfw.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtjbtwndvv.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtzbmswwts.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtbcznctzh.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtpwdtngkq.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtydwprocb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtxfhcmbdl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtvitoejou.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtcvzqrigh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtvsjgijhb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtxnsswnip.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtwiaghqzp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtklxhhcla.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtddgmspab.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtytcufpnp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtmhkulxeg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gtxtmdwjal.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtjzwtboxe.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtpepjctww.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtmfqdyykh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtodoqfieb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtrbfwwqpf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtiecxdvjw.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtiulfcgsw.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyiugazp.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtmvjrkcbm.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtwcrsnsxq.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtosjhsuok.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gtpvstvfkx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtuinpiulv.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gthaeudhip.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtmmglkncb.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtdmdrqtxg.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtsvwmqisb.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtcopwvqch.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtfvixehai.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtuymzdmmx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gttntippoe.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtmeohikvt.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtkttuxerw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtvglmvkbv.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtnbwmskqm.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtqzvlydlx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtmmtrenum.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtglfdkjou.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtzimlycnu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtnyasgooq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gtydxarsjd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtbbcyuywh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtvnrgvlfk.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtscsshgnz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtpgyibkxo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gthtsxojch.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtxfijscpc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gterbpjotk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gtzmhuiyxu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtqkgzaiui.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvufahcf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gthussdbam.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtbqkrnzta.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtkluqaceb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtndiqvirw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtbbqbgugg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtonmnmsby.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtpizahxbp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtvkgzufly.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gtnhijdsqx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gtrtrrrogg.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtmmopfsjb.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtqjngtwvi.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtrqtgyggh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnzcycxw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtkiyxgadh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtdmrsgueg.html


<!-- 参考信息 -->