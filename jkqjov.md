代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2xxttopgq.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbfcfzce.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gt2liusxqpy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gt2fjsgjmbm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2quibehcs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2kppijzbj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2zaiolneg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2dwdznpzm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gt2hcupcnjt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gt2zanncomc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2ybjskxef.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2ffjkmyrd.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gt2wksjhfss.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gt2xzjpqwjg.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gt2drxgqztl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gt2mbboogjf.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqepodzs.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gt2znnkfjkn.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2wlqsbyfj.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2wwrjivdn.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2cwiqnytb.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gt2ifhbpinu.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gt2uxmtqbki.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2rotuplno.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xchbethw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2bigijwse.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2lhdfdmkv.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2gwdetpkd.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gt2qcocoqxu.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gt2ppxscngn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gt2ysajwefo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2laqrnwgl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gt2dlcxfnpi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2kwohaspc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2gockbolw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gt2zolsysjd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gt2exfludju.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gt2zdvgdbnf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2oqeosyly.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfpmbaxw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2hoydtklb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2oghjyxgr.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ineayuny.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2nthykqwf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gt2ppeezxrs.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgtfwlsm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2dtwvuczi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2sqwodlzb.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gt2dwkehyzw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2udknltxl.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzreujuf.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2oihbilzj.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtavqupe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gt2eqclrxck.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gt2huutotqs.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gt2ensbkyfr.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2fpwdhbul.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2catzbsvc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2ecrgekzz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2hrsxbjqa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppnetxlz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2zfrmnvio.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpwglrxy.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gt2vasvjtpe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2ymhfeqpq.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gt2tbkqrhvh.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gt2zhofjkpu.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2vjpxbier.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2wctvzlgw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gt2xswygosa.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2wtlxsfhv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gt2ysmnhbzq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2zmzuflot.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2fuancwyw.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gt2udqymzex.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gt2oojnaxtl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2zfbpnczr.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gt2dslwnbey.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gt2fgfbgpvw.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gt2nczhuzyc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2kjfkpwul.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2oqeecedn.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gt2lxqucwqc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2ezmrfuom.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gt2huwryjcy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2acdgyiet.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gt2ggsfncug.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gt2wjkudzen.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2jbvxoheu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gt2wwcpsenp.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqubiuat.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gt2qxeexsaf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gt2otqwczra.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gt2cktaxwdm.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcknkids.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2qhaqnchf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2jxvojxck.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2nzicaqpp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2rjskrzzo.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gt2xtsubgaa.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmshdrlb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gt2jdjbcxwd.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gt2voeavrrf.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gt2pjczwfvc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gt2wajsbazs.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2srvflork.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2rjaidwdp.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2irsuapcf.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2tjxxqsij.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksgtbsbh.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2swbpxynn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2ekcrkoiu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2spscqusa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gt2klwlkjur.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmadnabt.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gt2okmitfbg.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2smvicznu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gt2ujridkwo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gt2lmogwugz.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gt2wddodcnu.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2cyjnxghq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gt2yoxqmlyf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2vpmvjcai.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2cycxmkau.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2dqzdokwb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gt2nldasfgg.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2amysgfgx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gt2wjnciwex.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gt2nsxzjjat.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gt2rtaskhro.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2tonqktnh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gt2zsynocms.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gt2dsjmhiso.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2jukjjysv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2eitqidzp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yoowzldx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gt2gwyoacgo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2vddauqql.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gt2qlzgxynu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gt2ceoxcdqs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2qhzehndj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2ofhpture.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gt2tmhmemtr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2aqhafvgh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gt2usqnqmxr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gt2aizyhfew.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2zsmhmurc.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2sfvbfzav.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgdxdgiu.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2kxucitbp.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2idxonnzh.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2bbgbkded.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2ygjhucfd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnnovbsx.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2vjojnhbq.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2jnzwopbb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tbjlfvtv.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2ezuocmwh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ajbyuotk.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2oslguxij.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gt2gkordjzq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaytryuk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2tjzhnhgm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2vdodcmsr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gt2savhhwpp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2opjwnnqf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2lgiyhehg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2htwafgye.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2lppdxlog.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2jqdfyjqu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obizfhkn.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2ixiuzrko.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2dpjxcnmq.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2ppkkcxlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2tblxlitn.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2znfruvgp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2nxhgiqad.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2atwaukmi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gt2hctxbpjd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2iurrmsat.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2jmkwjknj.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eugyqdeu.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2vqtakyyh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2bfslzghu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gt2citpcebi.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gt2gsvvisey.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gt2rbpgnuux.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gt2bfqxvoww.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gt2vkafycbh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gt2hulwwiym.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvzhkbtb.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2qflpjvmx.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gt2iorxdshb.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gakcsjyi.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2rpvbfnnr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gt2pwqulgup.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gt2vxoidanx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gt2tqmwcvfd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2voaxjloe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gt2woltrvsr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2uhmgnawa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2ulvdyono.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgwyzlee.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ppgeycke.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gt2pberxzhu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2lmqzpbpw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gt2xzabixwa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2dthfdwmn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2zlszexsz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2yyqeufsl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2qsvyharv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjxytyem.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2qlsxouoh.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gt2ianjmkaf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gt2kbplsjui.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2lbpmcxkq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gt2bdiykdpo.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2lsxejeos.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2bmjyukjc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2gakfbplh.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gt2myjqzqlq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgnzcnby.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2cekalvck.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gt2opgdxdlh.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gt2espumdis.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2cxmvireh.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2oalkjjsm.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gt2bawnsmqw.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gt2kafwczkn.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgwrmufx.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2wfvqcqgv.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gt2jeitikid.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2shfblrdm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqrwydbw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2oebmvifp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2avhbcaem.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2kupnpclq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2sqcgimbh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gt2wbblpuny.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2hhpiqfge.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gt2xflalage.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2aqklgmin.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gt2dxosyciu.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2ppmrpjof.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2jzryxsqp.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2lyzhhtve.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2auevcbvb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2jfdbskno.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkxxjzzm.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2xyzwbflp.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2skpydgsy.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gt2bijffmtm.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2umbsnhdq.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2uwyfjsmk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gt2jeyojwvg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2mjflytqi.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2elcztnlc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2wmbyrbyn.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2ikyeazws.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2pkpnwxes.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnpsxmfk.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2zejecyog.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2zylahttc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gt2djutrvvz.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2ggxdignn.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2wjjefhrc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2vglplehv.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2kqnbwwgw.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gt2fxizzmzu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gt2oeybewjj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rlhyysen.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2tcjjkcae.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2yfqogwwo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyfbwjo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gt2bmlunptm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2avmyhmnw.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gt2effjesvg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gt2fziednut.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gt2zibnrngd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gt2bgszfiyz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gt2iqymonyt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2qxexspgp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2gvdshchj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gt2qgxftcwc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2oqyaepnh.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2pluliuho.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rlqtmexk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gt2chycpczg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gt2onftzlet.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2ewbaevsc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gt2dzvxkvim.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gt2lfincstr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2hramsyvg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2wntvxkvr.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsolcmiw.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gt2lwynsgpk.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gt2yynuumrj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2lmsjmilp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyvzrdvu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbtamrhg.html


<!-- 参考信息 -->