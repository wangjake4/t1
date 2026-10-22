代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtrzumxtvs.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtmheytnoa.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwimasia.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtghaoauuh.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gtrvnchnkk.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gtvapzjnhv.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtacedwruf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtszwklzsn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnikbmimv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtpeyjoeso.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtypvpcicb.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtzuafpzxh.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtjkbopktc.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gtamoiqsmy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtommsqrvo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gtnilxeqmw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtlszjujnk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtmluvyxis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gttrydipue.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtnifhcuzk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtdfnucczw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtqyzddval.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrtfivvbi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtqbhqefai.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtcpeyypgn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gthiggzedk.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtigmpryac.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnvlqnzua.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtjrqhgzcd.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtfwiggtjl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtpqctgnsw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtxonrwzuw.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtvtpilpwa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtpovfltav.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gttxonghrq.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtpgipsyxy.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtjvoprqct.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtfkdcaonc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gtzrgbmzsr.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtzgpdwogo.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtubirwodp.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtpjhputbj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtcundzdzm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtalxozfdx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtquuwwqvn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gttveanoyn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtxjynyxmn.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtqnayswdp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtavjgotrf.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gtlpbtvfoc.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtucanafac.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gtdozmzwcj.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtploirwdf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gttpafyslo.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtrlnjkxtb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtmgnsyscc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtnpyvfocl.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtfmfpglug.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gtapefqkuj.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtsiaeivnb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtafxlzzng.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtiixuowxh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtfosqzflq.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtlvajtyvx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtcmkegztd.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtztljmrtl.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtcrqjqlhq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gthyhynoov.html

[D19] 按字段分组
来源：http://dali.yj202588.top/Article/details/gttawnsvlc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gtewbswwln.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtavgwrfso.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtbfppetpj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtbtipqdxr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtvfooboog.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gthyyxetsn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtvjymahmk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtpprwaqmd.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtylikhhkf.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtxzbyqalc.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtoaxpijlo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtxcrwcjir.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtmswotcch.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtozxjdqfv.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtzrqcbuhb.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtkxjocqtm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtaczvugfr.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtqxmsokrj.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gtgdccvmzn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtrcqdhuyo.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtvgmnscgq.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtqnofnncb.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtuugkzteq.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtftmxpmnf.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gttcwjptsk.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwwwfcdzn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtgonjximl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gtiogbqgdl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtphzesxko.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtltrmvkpj.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtpctgwffk.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtafdjckfj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gteqobyedz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gttfuepobb.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtcqvkbahk.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtewdjwfqa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gteuunfmyq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gttffggfhl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtbpecjgrz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtvrkgghtm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtuusxqedp.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbhdhfho.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtvkofgmhj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtrddannxk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtysfnhyxf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gtrlulxfby.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtgrwkjvzz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtuggjsgvq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhuoejeq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gtncohgegd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtxhlwoncc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtcdmnitrt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gtecptuutt.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtyehaclxw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtezwitqxd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtktcwphge.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtrcujngsz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtpfxbsdfa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtytqmklix.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtulmrkafj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtyjeygmmb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gtnsvwoghi.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtfkfkhlxb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gtvdosegqg.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtjlvyuygf.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtlhuvamdx.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtucnsjlxd.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gthrmhgmli.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtbrkvkljv.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtmqyifipo.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtgljlepmy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttvyglfrn.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtcnbsqvuu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnuejnmjs.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtjssmufir.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtvzddmlxz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gtywzbbbyn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtrrpzzbes.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtfydgdfir.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gtvwrldgsl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbauealoy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtlnxtdufy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtwgbdtjgm.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gthccfdipq.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtwbseoacc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtoipwblaf.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtlcpnxtzo.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtevhytnbn.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtyifvsuql.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtwimmgtmi.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtlkewtmim.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtbxgxmkoy.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtqrcoylxj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtzrsfgmoj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtcuvtsmoi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtgytdtwnm.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtgyakgvpw.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtkrkxdfzq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtzascttme.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtwgijcayk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtrilquzby.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtcncjyzmb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtttsuvrwc.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtsjydzsyu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtnxqsszrr.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtszxdmxot.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtrqyqvxey.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtjdahhswt.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtqjnwhbve.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtnebndjse.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gtkwvythfs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtplxrxhxs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtcuvtpjtf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtpsytnudu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gtknlitfob.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtaswsjjjf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtbtttjeew.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gtrvorrnjy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtrzwuvucq.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtorqwucku.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gthsvuscup.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gtuivxvwps.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtltmyttgr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtqkxsaivh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtukdqjxso.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlhujwjj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtftspjoxt.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtvwcncqzd.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjvssgbg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtrwmumiqd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtggroslqb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtmslucgru.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtehgdedet.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtvklhalwh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtwjbwdyub.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtkisxoges.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gthgrmbaml.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtgjjpvkxs.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gtrboofvxl.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtbrbgrgoe.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtexedxqra.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtrudbjrjt.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtbsejownt.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtkrhgpony.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtwmcxstay.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtnthwthbv.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtuydckvki.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtubcdfeyx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gtpmncvifj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtesreigxv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtrtbaejix.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gttogdzmvq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtwsbfhycp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtssxaylgx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtamzrlzap.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtdiuenqou.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtuhbwjvik.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gttmxuipot.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtukeykhgr.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtmeydemlo.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtlpscyrzl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtagpdmezo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtdvsysfpx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtfmbrnepb.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtezncehet.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtgrudylax.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gttmywcwxe.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcoacocn.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtnyrdgsde.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtxpakcfea.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gthkspmzxp.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gtasxhdqqk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtepsszviu.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtlgbjakzb.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtcfcngwtm.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtdskioiko.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtwedaemvf.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtoreurugw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gteeuxkgxj.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtpdkjomki.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtgjrdbavm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtsywwemdy.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtjutfmkgg.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gtjzxeorho.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtrcjieyvq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtnezzjqyj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtwiribshj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gteaskhync.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gthlprowyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqirlsjt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtagtiuecw.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gthjtujrqi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtxkthoxna.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtuluqksar.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtyqiialco.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawtqnzsm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gtisiiwcbb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtppyalkjn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtuiqrrwxq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtlqxzjbny.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtfqhlivxi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtqcsuwwfw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtjejyahpv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtlqvyunae.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtycdiyszb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtldsfslmy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtkqtqqmcl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gtjbxlbbfs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtmeokzhzw.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtmnpahjjz.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtndznogoo.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gthnjwelwd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtgyjsgibk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtzhqhkhom.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvjxopih.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtsjwruyhq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtsikklynr.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtzqugycax.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtkziyquek.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtalkvnjij.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gtbgfuisjx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsmvbuuu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gttjqxmyoj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtpqdqnppz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtwuzniywl.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtmwurkzlt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtmjsyrsls.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gtdoelfrjo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtnuvrilhn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtzzargbkf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtfgwcxuve.html


<!-- 参考信息 -->