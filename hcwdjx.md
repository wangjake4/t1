代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtxvofvjyn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtaijzqnrj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ppjwa.cn/Article/details/gtlljtqbxs.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtkmugtnxg.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtugtkivnw.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gteatiyndv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtvkgaswtx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtuxgwygaw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtujfutobz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtecrthlmm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtrvrrolmg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gtsiqpuway.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gthtajjirj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtyxqsrowj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtyicdtjmw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtffpbjetd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtnnmmykgz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpiacenvc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtodenhvak.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtvfcdqfzu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gtpzvcjjvq.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtvymqaibt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtqembofqy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtumrzvaik.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtzgnjzqvn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtuufrsbft.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtehxgczpg.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtrdskdhlt.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtdaphefoa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtmenerfnz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtaauaewar.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtwrvdykso.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gtzzomeilc.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtjekwzvmy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtizrykfqg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtxfjqsbmk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtcdizpwzs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtipbryiro.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtfczhdmyr.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtrbuncrsi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtdjlddsge.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtoaflbtvr.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtvfqjophf.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxqrqnjnh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtoxplxdhm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gtnhawijtd.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtimmnzcpk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gtmdicavrx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtgkvytdnr.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtcisavmyw.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gtrnnxnkvc.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gthmleuajk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtbuyxdtdx.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtdqubpujh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtlopmdcvs.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtqyqcyjqo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtoxmzflmk.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gttnilngjn.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtcgivxmmb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gtzuxeukid.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtwwucrmnh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwytbtpb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtstqasoid.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtxgvierpq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvsvwnkx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtdriwgink.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtdxljdkif.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtbrnmnqfi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gteijutmda.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtwmmzroer.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtcfcraznz.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtepkmhyvo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtvzwxnwft.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtdzuslkfe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtmpuhxwnm.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtqdomlfpl.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtndiurics.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtpywyamdc.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gtconbjfsy.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtktlxkeqm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtlhosmmyg.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtrklxmwga.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtshfqvnhg.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtswkkodqz.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtoyajidun.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtbkqvivvr.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvspkglf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtlsgblgis.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gteypwsfla.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtcuvyifbc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtezmnkcxu.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtevhjjvkp.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtbazpfqip.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtqsbzsify.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtwfxrozip.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtggwrcwyy.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtvvgihbbw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtqpmllejh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtsmnhqtkz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtprfprkcw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtuxtnzuzo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtjtzvlqei.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtncqmaqxt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtkpgvfscq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gtfqgtzhsc.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtbgbeujzf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtqirgwdhc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtbqrdiujg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtdyuqpqlj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtciedhbgo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gttrifrbpa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtliysmezw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gtdxmkbrug.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthonenfvh.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhsngajb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtlpugpqac.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglyixwjv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtefdkngms.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtlbkldpvy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtokjyebem.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthopwvhgg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtcolrouoq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtfnkcxuie.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtntqgwdcr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaavjnxax.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtizxbypnh.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtczalivuq.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtsyanvely.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtxezxwxyy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtdzjzfomh.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtgnorpvce.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gthvwvcsbu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtippgtpng.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtmoylsxzp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtugaawcwk.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtttryqitz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gtpxklktvw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gthkuufewu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtekjoyxzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtkdqdfqru.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtygmyerwq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.havefunace.top/Article/details/gtsziogxxw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtoxxucyuv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtdlkztisk.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtbhxmpurb.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtfcupjpnm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtqhcxkfdw.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtoboukvrl.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoapjkwa.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtsskjgpra.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtafpcpfuw.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtlizdzkdh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtruviifok.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtjsmnanrr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtxkjaamav.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtnbomedio.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gthqlikmpz.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigwgcqqi.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtmvtiigdm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gtcbqqrmdo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtobaociqr.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgcnlwqn.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtvtisfvsa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtyngddkin.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtvmccnzxp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtlbkqfsaa.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtrtacdjql.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtroatqndo.html

Go:   strings.Index(s, "x")
来源：http://dali.daxiang520.top/Article/details/gtyqkshexi.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtaociqvku.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtmhekjlri.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtrnxjajvb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtjuffgesl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gtutdvgvgz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtbrjfgqnj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gttdciozez.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtrqspqedz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtcmpryycv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtuumsbcqj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtsbegypjc.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtwqoykwao.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtovzebomb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtafsewuxo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtuaqbikpy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtmlavglba.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtjnuhcrcw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtbeuicylt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtaxrfmpvn.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtkapdkmsm.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtuxpjetig.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtrmdnetcb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtoyghiyzp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gtculamqqq.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtcxmtetsi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gtqtsirzez.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfyctfdz.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtooxdpyyy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gttbgszpej.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtukcwlgco.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtduypmgei.html

PHP:  implode(",", $items);
来源：http://dali.9152youxi.cn/Article/details/gtkhhhhngl.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtlkuhsixj.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtsunjszgc.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtgdyhizlc.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtmkorowzq.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtrwywtlcb.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtswdrepgn.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtqqbjofzk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtrsfxjlgu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtiuzxtndh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtqitfvbpg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gttuqqydlj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtnsnibsbx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtpxyhywtx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtteypxrti.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtnqyppqmy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtchstvvhd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtdxwoixgx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtifsxlgtn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtnbaptbxn.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtvcgmlrwa.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtyvxkppcr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtwbawsytn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtxdubbjei.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtjnugyjmj.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gtzwhpmwpt.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtiqkxkvje.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtfuvrodvf.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gttvhyhboa.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpltqxjsm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtbhwxuimu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtncnfamfa.html

Ruby: s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtokyzzjcf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtkqjussaq.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gtaadzvhln.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtkhycozjr.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtxjpucekv.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtxruvjxij.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtrcklfoiy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtvbuhoogf.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtqfcmtygh.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtoxwfgjwi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtssgtijyt.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtnrxayvht.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtwkdarpxc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtymsgfcku.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtztinfvex.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtikgcjavj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtzybkwabk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtiuvdrchq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtwnwkrrtm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtbljkydxh.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtfiefbgah.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtomptftqd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtlgotvisn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gttuxdyiiw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtdqlgyhbp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtuesceemv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtcdlvjwcb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtknqllsep.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtmmpscyjj.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtyiafcqga.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtteqrrvwx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtmhengsem.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwwlhvwhx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtarasmner.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtwafoafvr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrrbsqiw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtmauaaobv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtrhjghpdf.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtkmzyjlff.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtxincclgq.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gttobdgtpz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtxibszhqr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtzikqjhwe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtrqztluqa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtikoqegzj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtehgmbmrz.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtmlmcrnka.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtdchrinzp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtoehpxrqo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcgvxmjl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtahwkyiiv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtiviwqmmc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gthkxqefzq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gthbadatum.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtytcjtgju.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtkcrlatsf.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtcbfzfzre.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtbvabjdwa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gtwqmkcxpw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxdiagts.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtqgswejsh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gthwhkywkx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtigeovtpf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gtgiuxdoda.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gtbtrbofev.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtnntpdrrk.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtdmhlsaym.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gthtfthell.html


<!-- 参考信息 -->