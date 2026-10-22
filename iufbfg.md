代发 wailian999

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gt2gyrulvog.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gt2cccdsbpw.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gt2zjolhblu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2nfolfwvq.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gt2gtunezje.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gt2gsnooacy.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2finkpdtt.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2josvmtns.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gt2qalbhyfi.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2plzhmigq.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gt2sqcitqgc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2tjemnwib.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2kgmnvmof.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2gxsodsab.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gt2cekwulfu.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2yfhblkuz.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2lrkoafxq.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2xgwsemuj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2synkebmr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gt2wkbadpdv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2mfdknoma.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2axstdwhp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2ijfnisln.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gt2xprwxaea.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gt2jfxllzpi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gt2leawcygr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2ihynqecz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gt2gyqxrpjc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2tynycqju.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2qxdzxzzw.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2ugfxjzyb.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2ykzcjfxy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gt2vinjkrpd.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzsyjhqw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2jrdlgcsf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2spquhnby.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2ponxsbiv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbsdbapi.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2wouikwoe.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2rxhzijba.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2bvtfoozo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2yfvkcguc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gt2xdgqverz.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gt2rdunupqq.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2gamnbdxk.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2fxtiagil.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gt2kgbcljcn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2glenypdd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2yfucimwu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2xtzeqlqs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpbpyvct.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gt2khiyatob.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilklrtio.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gt2gjwogijy.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzuchzcu.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnfkjygm.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gt2ryeoqomc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgudval.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gt2ouwzhvjm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gt2itnvzivq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jknvabiq.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gt2neefyzis.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhxqnsvv.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqqymnyi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfjlgron.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gt2lfepwpbh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2wxbxalce.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2ayatwpdk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujwneear.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gt2apgsnhiq.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gt2yracclhz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2belocspv.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gt2sngjjtqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gt2rhbsiwtc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2klhlmcfn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gt2orrluwgd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2soigcbgw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gt2urgxxaix.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gt2wqdecjrx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gt2mkmeykhp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gt2asbuycrn.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2skwpktav.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2crjgmapa.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2gcrdvadl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2suygzund.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzxnnoym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2aoxvcqcz.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gt2mkpvptde.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2znalimlr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2fdltcnzb.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gt2nezgzcpg.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2vnbbkumt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2cxhwsbpl.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2nfnegrsq.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2nwajlwah.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2uexuaafa.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2tsfvxugf.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gt2ivgzkhpz.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gt2iibffhuw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2rpgevdfu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2mkobxbcd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gt2sicqihjt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2vftlafkp.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gt2wiazibee.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2ymswyduq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxvwuwau.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2czwwnxha.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gt2bsvblwvy.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2sdttvwme.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2qdpftyfl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2yrusafwv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2trbwbefx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2vzrcluqg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gt2lmledhxc.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2wgncolxy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gt2vrdpmfxi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2ngasrtpu.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2cpomzyor.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2pxvwymom.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gt2glfldszg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gt2lwilvmai.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2ukwcutfo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gt2fflaugrg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gt2kwcrxlyv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gt2cflyoqcu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gt2aoeiipqw.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2eooqbgfn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2xdsyyawx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2jbqaxysp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gt2rdktlbwx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gt2fdtygpdq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2xvzkbord.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gt2jqzxliwj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gt2xcoteavo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2qpsrgwuo.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2aakwtqex.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qukewliq.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gt2nlpwhlnu.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2ylkthlzm.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2qbrimith.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2jcnbcuyp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gt2nbokyxms.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2xskkzhoh.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2fmwmsnoa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2gjxgiurd.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gt2jpmzwkkb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2omcslgud.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2llpleshi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gt2rcokyvzr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gt2mrsifjdb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjxdgbkf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2haofywul.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gt2xlzwmhfp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yihycsgs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2myddfshc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2pktayjll.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2orulxqbl.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2iidjetyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gt2doscnmek.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2doyjowqh.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2hrdtqmxs.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2cgqtstfu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gt2vfhfhaun.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvomesxu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxtomtca.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2nbrpvutm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gt2qiiixzby.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2rcfkwrzu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2jmkviydi.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2ihabkeyb.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2fratgosd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gt2hteznpsx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gt2daxiwfxp.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gt2bnjbuasj.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2rkpjwwcr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2tbxyhzrl.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gt2umiacwdb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyuttyso.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2pydtodko.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2kwxfaawt.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gt2afezlcmj.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2stkukrdi.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2ssbtmatu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gt2nxqecnzx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gt2zwygrthy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gt2dmkmmhkv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2iyyetzlm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gt2isholatn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2wdpbltxf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gt2iaqdgnfw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gt2sujbdtix.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2samcbgxr.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gt2ilcnilif.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2gzxqhkzr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gt2yghndgov.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2vcxqylsh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2tpzrjnvx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2hdshnzwj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2vvkptkgl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2ynuknvha.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2nsuthncv.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gt2ffztudyg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gt2jlgsukkf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2ppzayows.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2jdpgilix.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gt2zwxupjcm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gt2vukyysve.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzmachkb.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gt2gmhraymb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gt2owuqmydm.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gt2vkuentvc.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gt2ttusipbh.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gt2nnufnbmc.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2myplwzor.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2ftzjiqbh.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2dgqmimcl.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gt2jznsdejl.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2pizfuysb.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2bfyepztk.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2jiifswfc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2refckduj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iseavghe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2xbznxhva.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2gpzktwxx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2rcsaymnr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gt2aoxgqeby.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxlsrsom.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2xabvhddw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gt2kjdwmzbx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2warnyvdc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gt2uuokoqtz.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2typborcf.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2kqjpekcc.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2itfskxaz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2ojoemrsc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2jsjjpije.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gt2qvbdkuyf.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2iqhhnhlb.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2kwdtaoga.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2mgvtsixj.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2iafahxyp.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2gainscwg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mptvbcua.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2makbbayh.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2copdabug.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2yjiookwf.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2goejubyu.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2sivyeinn.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gt2ynupflog.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2ukynpofo.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znutrvdm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gt2dqihvlrx.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gt2iodgpoya.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2vlgrcirh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2fqwsizfq.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbhgapiz.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gt2ypaobsxe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpwvljty.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhtgohqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2creinbnm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gt2mjbqievg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gt2xyxhqbox.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gt2mzbivqrx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2uvevzvme.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gt2pppwdeyh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gt2teetgkcq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2zuywfxek.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gt2ezgwqljb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gt2lhmvhzkp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2kmbwdrqu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwfmlgul.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gt2goimlkhu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2socwhoxp.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gt2qgxxzzqz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dihcypco.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2blvadiob.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ljcfhlpd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2jqvtpiss.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gt2sveahkwg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2xyaawkdt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zsrleroc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gt2adljkwxa.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2rqkscqfs.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gt2mkjjezvi.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gt2rxbttfeq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2uryecprd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2mdysvtda.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2zdgxtgje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2astwwsbs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2wclgecag.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gt2rtdecgjz.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgipjtvo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2qeeshnfz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gt2rvxdhttj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2ttaqbtgs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2htvtubhw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wjtibnkf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2rdlfxtdp.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2dhlpecoc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gt2ejnwbmzd.html


<!-- 参考信息 -->