代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtpscwrvht.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtqqclawze.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyuyjuob.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtwbvqeunj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtnddikofo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtdiuxpqkj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtelitchlk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtzbikjcve.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtovemfttk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtjaqtvmhl.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtuouanzam.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtfitqcnlp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gtjutyfsfn.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtwocyetjk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtaaesomcu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtehjftnwh.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gthtyrzlmx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtlvwztkpu.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqrxzwyv.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtcnvzsyty.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gttzxkorpi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtdhnoptne.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtjiqaogkc.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtlbaalfsq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gttfzefnoz.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtdsmmcnij.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlgywagbe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmklpvfd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtechrsbsk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtiaozerco.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtovcycaus.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtlnpywidh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gtgtqzmsrd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gtqkkpduvh.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtuzchwkcx.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtkdkvccon.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtfkjmwwxr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtmrwhojyj.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtmwhwuwyp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtfqvpppll.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtehtlimfu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtzeozgnzb.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtnqvzftcm.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtapgosnqf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gtbyiuewqu.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gteiflvvoo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gtwhlcxxna.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtewehuqqd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtcqjacwur.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtzvgonzxf.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtpvqojnrb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtnoinkkew.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkfnhooh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtttihitvk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtmahpmxsh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtiqirorts.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtqlotxoje.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gtjjowwgwa.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtuitgzzdh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtzudsfiym.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtrxsbsqal.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtoonoital.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcioxeyjg.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtfwnyckza.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtqwfulcig.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtilbkwnrs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtvsgogrbs.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtsmefsqcq.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtlgfvvnup.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gthgyldcif.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gtewjrrktk.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtkbrjqrhg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtnwdqzbpa.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtsxycqzqf.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmmomvyv.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtjxtjuzzq.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtdfryryhn.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gtehoqmnsq.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gttgphilal.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeahgzwt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtoujhxszd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtudhhjwxu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gtrrhundls.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtdmprzzti.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gticcbjwwu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtbroohwsf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gttqxpxddp.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtknisrqbo.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtfdhqzzvf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtkipzmjju.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtdvhpipfo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtdeymuzrp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhccjakv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtlvtiaktl.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtfhaadbtl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gttwpexnct.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtlzfykgvh.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtyxlcjqwk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtirfrvxks.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtufoouvef.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gttsrrqetm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtnktafybo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtdcytmsmg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtpkwgkfnv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqilxpbg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gttpdqkqcw.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtwxvliviv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gtkfrojcpf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtantnkado.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtlcsxofnk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtpnkcdoox.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfafsmaxv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gtumwhgebe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtnyqjkils.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtyeovxpae.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtpdlmvyhz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtltwduedw.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtgnaqtbpq.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gttmqhtsgd.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtmirfxzgb.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtawqhackr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtrvaglnul.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtborolyky.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtzkmivcdk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwoutskwy.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtpwgazjhh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzdyvmyz.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtxvvarfgy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtxofmlfyv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivlsbgyb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtdjsbxfxd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtnmkhdljm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtdyinatrr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzvhyanw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtrnxmwnke.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtpapangzb.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbxleqtfy.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtekblgkjo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtheaholyc.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtntovhtke.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtlhhetrui.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtdftlcpfo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtgtjtzgof.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtfepujqdk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtbfsibvje.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtxziosuqv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtifyfyark.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtgmaohbzr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtaiufrwkk.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtvdyhjijp.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtgahiyahf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtbmdjyclf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gttlsccfea.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtsxhprhao.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtsktphrbk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtcvyzadya.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtpdmtzlrh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtasfewdlx.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtbqyngxmo.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtskypsbyv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gtxvbakdvd.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtdidpknki.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtpuehnery.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gtnyqjfmxe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtgkvmwpjw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtgzinhucz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtywiwixbg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtslgpbhyf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgnmeifc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtkeqbjmhi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtjxuwsxqb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypprztbe.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtupnajmqj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtemtomasb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gthivuzqla.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gthrbbggck.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtltafqjhy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtinledbfw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtolakhvoa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gttahbhgro.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtmslmkvbr.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtcbwhnxge.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtgedkstja.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtwfcxewwz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtiwhqbkbl.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gthidnpvjo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtaachedam.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtlaelhfjj.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gthrgphsbj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtsogwbjfr.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtxzhjnals.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtlospsigu.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpekjyrs.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteamoblgw.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtjbwsphgj.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtswjhxzxq.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtfgtoujyx.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtffpujwss.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtxkglqqts.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gtpbouwocb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtdtszaawd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtvrxhuxmu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtglzisjwz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtjvtujrdp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtwxmynlza.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtbohwauer.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtabsfbivs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtfetaqake.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtiooqepzr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtllclulsb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtjhaatigv.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtwzftdvzm.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtjeqmpior.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtqbnhnwpu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtgqfyllmb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtlukgjgqz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gteulggywf.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gtzxavlsmh.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtgahbwhmn.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtoygdmuwg.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtdcdqdxik.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtimcjiufs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gtnznjyfgh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtucgfifsb.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gtxfuzwfgd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaonvpag.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gttggjqvxz.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtjetwfjci.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gtbggltdvm.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtqvwiolil.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjniqmfsb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtrmjxmxxc.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtrtdcvftb.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtnkpjdbkw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtzcsiryus.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtanaspvln.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtitfutfiw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gteyxqzhym.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gttfeyuvar.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtkgigjqfu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtoxvjnrst.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gthemqkjqw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gtazmquvzt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtvhhqlytl.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtwtpwqezs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtzeodwmvj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtzfkayjnz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtybkwcuon.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmvhbajik.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtwvuaiqrz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtslsqbyzf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtpoifhkji.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtuctfuhvv.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtyhmekjjk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtkrrlqpvs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gtchpkclbw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtprsncnpj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtosfrtlof.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtvgjuornv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqiaimyuj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbutgdiwn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gtjpeewatj.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gthzvgntfd.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttimzxcua.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtgucknbtg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtabdqppkf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtbrmjjqub.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtfbvujzrw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gttlhqbsog.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtklooltwr.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtobhkfasj.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtnlrdeniu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtesfqooyn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtcizrjtts.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtevfcgxix.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtycnrdooh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtbnuapclq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtiwgskdbq.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmictsrqh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtaeakethb.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtcneyyfav.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtzpqpfrzr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gthybcpwmr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtxdkilknq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtxhymvsfh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtieiwenjo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtazyqlaij.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtbdrjxney.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtybgvhrqt.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtpaseomjh.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtdkzqfuic.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gttamsefwi.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtpyoedcnj.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtidnoazcp.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtumfrwtoy.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtlyzxjkja.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjplwavg.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtihoggdep.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtrvlltjue.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtqmkakays.html


<!-- 参考信息 -->