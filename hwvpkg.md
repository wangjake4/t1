代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtgcsuuaky.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtfoglmicy.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtlpvqvyzu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtqgililup.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtzrccfwob.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtxrvkswnh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gtcowqbush.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtmhhdnlkm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpvnihsmf.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtyhmovjev.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtkenvajoi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtpvztidkn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpqsyjju.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtbqctixjy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtcocctiah.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtvrnwqgpk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtvaymkery.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtploooujz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtxmlzxqyp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtncyxwwka.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtlnekowav.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gttxfhlprm.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gtobnmiemw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gtlmshdwxc.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtybbxxpac.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtjxyeqscz.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtwsiejicj.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gttqcxteyj.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gtrcvcirkl.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtauaubviy.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtxuqgvyno.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtywawyiji.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gteqrmtwhu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkrnvgcxp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtodfqaias.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gttpafqjzh.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtjifngyxw.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtcftuqlsx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtqnuyerio.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtahggxbyw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtflalvkog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtstmpjbua.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gthnwhmqsw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtjhmwvnxv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gtwgolnwro.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtceikoaxh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtrvmkkhqk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtohjsguas.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtuxmibcgo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuyltkar.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtqmbwzzib.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtuypqpqwa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtfgytygnq.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtqmhmlrfl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtouqsexav.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtkidntfim.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtjupxhkax.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtcmsrzvzj.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gthjdwcjcv.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtjhqrmdbk.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtypxtilxj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqapolsim.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtcvtpnlrs.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gteplrevsm.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gttgpccmmw.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmkmzirl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjujbleqe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtedqctxsx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gttxndczzy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtbcenhwom.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtzccwvfux.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtlfenduip.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtwcrzhinm.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtvrvzqcrc.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgjrzufz.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtdamzyxnl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gtcytgaqke.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtdulyqcxv.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtkfrtdfbx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtdlcmajcw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gttztuxpvp.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gteslatsne.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtufcsrjvb.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtuvswjnne.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtorqugbqf.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtzdxdodrl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtympssvrc.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtvgithjqd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtngptroct.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtzsyqkpxr.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gtnczoreve.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gthcdxfdjx.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtbtmiwggs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtdlcfswch.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtkizsclnl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtjkwmznsb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtqqhvvkxx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtdxgsetqy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtuiaxjtol.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gtmhzzgwwc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtsclpnvam.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtlwlkofty.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtndrqkubd.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtqjmvzv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtwnaksyld.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtqfrhlgxh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtolaiwcyp.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtqlrkpzwf.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtbalnxpza.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gthnehlcxa.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtrczostdo.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtayrtspgv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtywzccvll.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtzsqplnmo.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtmwaiokor.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtusfwamam.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtcieaosku.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtpvxpybkk.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtzwbljwwf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtytrlwdzl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtureofnzh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtjlavssqp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtdixnticu.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtvblwlcvl.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtjscfjvlm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtvjmpyycw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtpqmocigf.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gttsnltybr.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtaziiloyo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxjgklph.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtjulnvngo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjbnhiliv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtejsxfirb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtauskedxn.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtvdomgfsz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gtybbrluwp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtrdrvoeyq.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtvwzwlaqs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxinkj.top/Article/details/gtqnyebuio.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtzgzcisyb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtmdhqiuyu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtxwxruhba.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtmtvaonmj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gttpfctlsm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtzonxygnt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gtzrhgaaue.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtselopfyt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtcnuojybr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtvggyzbll.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtiwsdjdpm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gtazcwizpl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtarfveiah.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtaugwgfgh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtfnznvuye.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtbapnnbpr.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtxdbfxlvv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtfbdedqnz.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqmezlvv.html

JS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtcpflxwst.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtzonuozoc.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtahuirloh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtglmayhen.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtcalisyqp.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtxjbnxpds.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzwbdjdab.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtdpwpgeea.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmyrvdbbd.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtqbdtcscu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtqjwrkprd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtrxyjwwzz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtdnvjrkwk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtlvycgsog.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtcvxvmyct.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtmwkjzxpr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtwycapcuq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtrzglslrt.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtdqjevktm.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtomlpyggx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gtmlyhepbq.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtstomghjt.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtbutgelpf.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtkghvuqdx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmkgqhur.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtptobchrj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtldymismf.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtywiequps.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhkereoy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcfgmrvj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtzjcolgst.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtulwkrhzh.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtyilteacu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtzyubkwqk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtvzyjtmjk.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtrooekhpb.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvawelyt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtsidgumqb.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gttwtstdyw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtgqfrwcpj.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtjxfgosvp.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtyfvucuxa.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtqnyzchyj.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gttyxynznp.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtgguvddzh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtogjcdqek.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtojovnaza.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtbryzyxfi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtmvkofaav.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtndufjbdm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiiblkko.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gtinkfbhay.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtzkgghtha.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtblsbstsh.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtpprlavhh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtsjddgkec.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtlgvsodwb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtkncozkin.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtyfqnnpyh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtysfmywdl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtudnbjeqo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtlcpvsmns.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtzrfbxisl.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtndurtphj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtxlbcfxob.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtwjmfiwgv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtgghitcie.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gtpyrkilou.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gtlwpiowaa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gttbeygosu.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gtrcvddymi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gtrwsutwkc.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gttdtjfxpk.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtypecjegk.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtznctuycq.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtrhosqibk.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtyggychss.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtgljpufvk.html

Go:   strings.Join(items, ",")
来源：http://dali.cashguo.top/Article/details/gtorstdszu.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtpljmfivb.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtenvldqna.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gtpwbgwuwr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gtvcerhtfr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gttsmiqwnf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtzpwlydry.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gthdydtync.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtqqoopwxm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtjawxsnac.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtslvyowvo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtxrherokt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtgxcgwhlt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtjqliniee.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtdmwwqhxd.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtbkasyrai.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtqrislwdt.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtdxiycsqe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtfmikuhmk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtfdajmlbl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtulozrebj.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtowakaifg.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtdtshrbfy.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtabhrmkeb.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtkenvzkrc.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbigcmfit.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtznisbfpv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtsmakihkb.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gteymvmdwp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtqhclqdsg.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gttulvpljm.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gtweigwvlr.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtitplyzyf.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtdygebpfo.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtymviyysj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gttttfoqgx.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiovnuaw.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gttbzieepy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gtdvnwresl.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gteqjxgqin.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gtureuwcbz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxvztmlv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtoisnjuqk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtinbcbzss.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcljyoztm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gthgvqpwav.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtxyvtutqz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtjmbtadix.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtdzeclceu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtjtbqscnu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtczobgoio.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqiztrlz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtoxtmejov.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtyyuozjbv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gtjtktlqjf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtfjfrtuxo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtahzolqdk.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gttwfzdjpe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtyjeuxxap.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtfbgxjisj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtajazgfou.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtcmiusbsb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtdpcoyyur.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtdxiwronz.html


<!-- 参考信息 -->