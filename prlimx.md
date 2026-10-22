代发 wailian999

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqcoeroh.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gt2mzhwvcib.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gt2shjgrtga.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2urndujae.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnvnhpil.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2pquqkfof.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbsytlgo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gt2mrfbqonx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gt2khxmnbdu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gt2dcuahkkc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2mzotnhxz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gt2mlwjfebz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gt2xwdepiwn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gt2yzbbrfsl.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2recuwssh.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2zylszmij.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2syezkmde.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2tzumibfk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2msqtasph.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2pyhavffd.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gt2bndjpmea.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2ttedujod.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gt2czusfzfe.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2olatarwt.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2xnttfwvl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gt2cofbromd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gt2byrpoaal.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2kicplcqv.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gt2xnaahcuv.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2qyzbwaav.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2yzjzynib.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2ktnkpyqy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2amibkmhl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2xrmbtafg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2ctxwjgmx.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gt2vgcyqfcb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gt2uxbuexwm.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2rsaxtuat.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2hcdphtds.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2cmepiizg.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcurxcms.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qiwbbgtr.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgulazcw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gt2stzgumaz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2eyhucqjj.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2rnkvgdfb.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2riiwcusn.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2ewzmqwzy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gt2capfsitt.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gt2jdkeqtgm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gt2chhkgcjr.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gt2rthpfvvx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofnbfagd.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gt2dmklfsbr.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gt2dathdkuq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2lqarsutd.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2fwdyneqt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gt2ldhjxahx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gt2wudreopp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gt2aylfwmem.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqrhgvow.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gt2bielhszd.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2vxoqoufc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gt2hevyvfar.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gt2fvbrwjak.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gt2yxobksmz.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2shksodah.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2pfohcvus.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2qparaoyf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2oujhdgvb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gt2wmkzibep.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gt2jdzrycdx.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gt2ockittnl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gt2aaodexjm.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2wafegzji.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2jteiotyx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2tzcmokom.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2rptpymtf.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ufdvmpjo.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gt2yrgjkiwp.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2apgbpqfv.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2aojzfvpd.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2dacqvhuk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gt2ojiepkkg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gt2xnwvfoyh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gt2znkhsshf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2tffapurs.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2jfvmnvpa.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gt2uvrgrrpb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzwftaiy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gt2ftgvjrzi.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2eizacjmi.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gt2agfkkgkr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gt2qzwzzltd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2fnwnbkcn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gt2dsfvladl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2fuvvxbpu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2iannphpd.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2jfrkzjno.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2oqvdduri.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gt2swjdctyy.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gt2rfqmzlbv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2vcrsqkso.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gt2jtaeynvb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2vkgcxolj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2jzrjronu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgixzwuy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gt2gdecsomg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gt2rlvixfmk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gt2hvrbembc.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfsjuwdq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gt2erugmcnf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gt2zdsowomq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtjyarrr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gt2mxtnrjqm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2ptdwrznc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gt2cqrqywzc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2khzwrono.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2ppprogvr.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbuasrjo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilieqcbi.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gt2bosgvzjk.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2zinnnyvx.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2aikxioqg.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgjtdjbi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gt2psrraauz.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2rygggjua.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2dymptocp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fisgstne.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gt2eihrptuw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nnunnwlr.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnvmhjtl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gt2ebmgkikw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gt2yqdkcfmw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2gpsieyfi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2xgfwrsyt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngsufvqp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gt2zfhhlvxl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gt2uudhwfiw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2erkxezgs.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2xjwhgbyg.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2feqzwmve.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cglfdntn.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2pdeebwtj.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2mfzyczyu.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2wisjtncv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2wkokcxgx.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2zqruqfvt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gt2czbiafdg.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnxypqem.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2kswkdhij.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2jkquzdgo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2hmjliszk.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2jocetcfg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lemfsepl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gt2lslnqkvv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gt2qitpqunb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2bqkpchiq.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2dgwvdckf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2mlxjsijh.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2eikjdafw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2shgxywmq.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2qdedbuto.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2qycdjgvk.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gt2lnirjabf.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2mixtbjno.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2nidxxvzb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gt2hqgoyplj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aeayjpmo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2gnqfmeyc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2cjrurzzn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gt2aumcepqs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2khnqawpw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gt2xkouporr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrdjgxha.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2buesmvsr.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gt2exwurtui.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2xuydguiy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bktszycz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2ylvqfcal.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ramqrfgz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grzyceyg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2ovkjyhvy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2uyunikvd.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eraygazy.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdgjclxq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gt2xjirctnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2zqysvoyi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2oepwinmz.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyihryed.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gt2baqrowfq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gt2lmibrysw.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gt2jdptakyc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gt2uqiyjrsr.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2lpqhzqdh.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gt2tzlepymn.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gt2aprhrmka.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2qotdvfyu.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2lusylejt.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwdxumgq.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gt2iyvesnbb.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2ukpetrof.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2uyyqqmvs.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gt2hyzrqygh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2waqhfwde.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxrbnhon.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2eyxrksrj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2ybjjnkaq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2oekafnvs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrisrdmi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2ctrvrsni.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2vmeikklf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gt2umougmtq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2tovljyte.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gt2jzjtdbgd.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2pgnfxadn.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2minjuxmc.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2sexsrcho.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2ugpvomfp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqgzwofo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2epocxqhl.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2hyeiyhtl.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2rdygpmge.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2fzaksmku.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbroheei.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuziuqea.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gt2dcngrvwl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2roxemidh.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2rleeujoz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2owcaiqzk.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucsmkixb.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2hntcvrdh.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gt2xrwkugbd.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uilfsnfr.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2efggzqfg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gt2ukjhrbca.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gt2nainymkk.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oahutjer.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2frvosobk.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2xmjqjina.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2zlmkplhl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vxcvueou.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2czncgngz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2ziewzjms.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2esscbrei.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2zfusfdcq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gt2xrjjnaky.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2oqcrxwqc.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gt2zwmoecyh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2urhynvtt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gt2cdyjyooj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2xonxvuok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2bwobjrid.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2xobaaaqx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gt2tlgqsbbm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2jyxiscrt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2oulnoyra.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gt2zjjlpcrr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gt2mqobpeok.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2ggiulyst.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2oycjhlrv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2sqzlxrmb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhdavdyl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2knqpijzo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2pvnjhdjl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2wvcudnce.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2ffppeupa.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gt2wxziidfa.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gt2mqfpuvwx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2iqidbfjr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2bikgnkky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gt2jsaywlew.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gt2tfptofmq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gt2huvzmbje.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2yovschql.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2driwkvik.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2pcwpnmzl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gt2dvchplzk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2qzmrsibo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2bupspkmx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqturjib.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2rylmhjlo.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjhuahs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gt2yftvlnzf.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gt2kzcuahzc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2focvcmqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgdjwzed.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2qlyqqsve.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2ixyfpidk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2jjocfxvp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2yoavidln.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gt2evpntghf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2smkhcuys.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gt2bqimfxlz.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbfczrmf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gt2bdciyuod.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgxzymna.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2lrqqjwaw.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gt2ubzeglvt.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2rtbldqxs.html


<!-- 参考信息 -->